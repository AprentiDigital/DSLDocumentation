---
layout: default
title: The Slipka Proxy
parent: Advanced Customizations
nav_order: 5
---

## The Slipka Proxy

Slipka is a proxy service that makes files downloaded by the browser accessible to your tests. If you’re downloading a report (for example, a PDF file) as part of a test, that file will be downloaded by the browser. Since the browser is running in a container, you don’t have direct access to the browser or the operating system it's running in, and you don’t know how long downloaded files will persist. Selenium doesn’t natively support a way to access downloaded files.

The Slipka proxy sits in between the browser and the website that is being tested, and it’s configured to look for certain types of traffic. It can inject a response, augment traffic by adding additional headers, and record files and traffic.

After calling Slipka to set up a proxy, Slipka returns the proxy and its ports. You can then talk to the Slipka proxy server on that port, and any files that Slipka records will be available later.

### Open the example project

1. Open the `Tutorials > Advanced` folder in the Possum Labs DSL project and expand the project `4 Using Slipka`.

### Configure Slipka to intercept files

1. Open `English > SlipkaSteps.cs` in the example project. This file gives a sample implementation for configuring Slipka to intercept files.
1. Look for the following line: `public void GivenUsingAProxy()
            => WebDriverManager.BaseUrl =
            new Uri($"http://slipka:{Proxy.Value.ProxyUri.Port}");` This statement is necessary to override the URL.
1. Next, configure the proxy to intercept certain files types. The `ReportAttribute()` function in `SlipkaSteps.cs` shows an example for how to intercept three file types:

```
public void ReportAttribute()
        {
            GivenProxyLogsResponsesOfType("Content-Type", "application/pdf");
            GivenProxyLogsResponsesOfType("Content-Type", "application/vnd.ms-excel");
            GivenProxyLogsResponsesOfType("Content-Type", "application/vnd.openxml");
        }
```

`SlipkaSteps.cs` is not an override file, so any changes to the implementation must be made within this file directly.

### Docker-compose

1. Open `docker-compose.yml`.
1. This sample docker-compose file configures a grid with Slipka and shows how to wire up a sample test environment.

### Using Slipka in a feature file

1. Open `Features > Slipka.feature`
