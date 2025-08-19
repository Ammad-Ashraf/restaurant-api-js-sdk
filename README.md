
# Getting Started with QR-Based Restaurant Management System API

## Introduction

API documentation for QR-Based Restaurant Management System

## Install the Package

Run the following command from your project directory to install the package from npm:

```bash
npm install restaurant-api-sdk@1.0.0
```

For additional package details, see the [Npm page for the restaurant-api-sdk@1.0.0 npm](https://www.npmjs.com/package/restaurant-api-sdk/v/1.0.0).

## Initialize the API Client

**_Note:_** Documentation for the client can be found [here.](https://www.github.com/Ammad-Ashraf/restaurant-api-js-sdk/tree/1.0.0/doc/client.md)

The following parameters are configurable for the API Client:

| Parameter | Type | Description |
|  --- | --- | --- |
| timeout | `number` | Timeout for API calls.<br>*Default*: `30000` |
| httpClientOptions | [`Partial<HttpClientOptions>`](https://www.github.com/Ammad-Ashraf/restaurant-api-js-sdk/tree/1.0.0/doc/http-client-options.md) | Stable configurable http client options. |
| unstableHttpClientOptions | `any` | Unstable configurable http client options. |
| logging | [`PartialLoggingOptions`](https://www.github.com/Ammad-Ashraf/restaurant-api-js-sdk/tree/1.0.0/doc/partial-logging-options.md) | Logging Configuration to enable logging |

The API client can be initialized as follows:

```ts
import { Client, LogLevel } from 'restaurant-api-sdk';

const client = new Client({
  timeout: 30000,
  logging: {
    logLevel: LogLevel.Info,
    logRequest: {
      logBody: true
    },
    logResponse: {
      logHeaders: true
    }
  },
});
```

## List of APIs

* [Menu](https://www.github.com/Ammad-Ashraf/restaurant-api-js-sdk/tree/1.0.0/doc/controllers/menu.md)
* [Order](https://www.github.com/Ammad-Ashraf/restaurant-api-js-sdk/tree/1.0.0/doc/controllers/order.md)

## SDK Infrastructure

### Configuration

* [HttpClientOptions](https://www.github.com/Ammad-Ashraf/restaurant-api-js-sdk/tree/1.0.0/doc/http-client-options.md)
* [RetryConfiguration](https://www.github.com/Ammad-Ashraf/restaurant-api-js-sdk/tree/1.0.0/doc/retry-configuration.md)
* [ProxySettings](https://www.github.com/Ammad-Ashraf/restaurant-api-js-sdk/tree/1.0.0/doc/proxy-settings.md)
* [PartialLoggingOptions](https://www.github.com/Ammad-Ashraf/restaurant-api-js-sdk/tree/1.0.0/doc/partial-logging-options.md)
* [PartialRequestLoggingOptions](https://www.github.com/Ammad-Ashraf/restaurant-api-js-sdk/tree/1.0.0/doc/partial-request-logging-options.md)
* [PartialResponseLoggingOptions](https://www.github.com/Ammad-Ashraf/restaurant-api-js-sdk/tree/1.0.0/doc/partial-response-logging-options.md)
* [LoggerInterface](https://www.github.com/Ammad-Ashraf/restaurant-api-js-sdk/tree/1.0.0/doc/logger-interface.md)

### HTTP

* [HttpRequest](https://www.github.com/Ammad-Ashraf/restaurant-api-js-sdk/tree/1.0.0/doc/http-request.md)

### Utilities

* [ApiResponse](https://www.github.com/Ammad-Ashraf/restaurant-api-js-sdk/tree/1.0.0/doc/api-response.md)
* [ApiError](https://www.github.com/Ammad-Ashraf/restaurant-api-js-sdk/tree/1.0.0/doc/api-error.md)

