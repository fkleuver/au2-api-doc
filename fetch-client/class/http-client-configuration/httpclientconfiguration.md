## &#128366; Summary

A class for configuring HttpClients.

| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | - |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128366; Summary**

The base URL to be prepended to each Request's url before sending.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**baseUrl**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128366; Summary**

Default values to apply to init objects when creating Requests. Note that
defaults cannot be applied when Request objects are manually created because
Request provides its own defaults and discards the original init object.
See also https://developer.mozilla.org/en-US/docs/Web/API/Request/Request

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**defaults**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128366; Summary**

Interceptors to be added to the HttpClient.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**interceptors**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

# &#128712; Method(s)

### &#128366; Summary

Sets the baseUrl.

**Parameter(s)**

| Name    | Description    |
| ------- | -------------- |
| baseUrl |  The base URL. |

**Returns**

The chainable instance of this configuration object.

**Chainable**

## withBaseUrl

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [HttpClientConfiguration](https://hamedfathi.gitbook.io/aurelia-2-doc-api/fetch-client/class/http-client-configuration/httpclientconfiguration) |

**&#128966; Parameter(s)**

_**baseUrl**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Sets the defaults.

**Parameter(s)**

| Name     | Description    |
| -------- | -------------- |
| defaults |  The defaults. |

**Returns**

The chainable instance of this configuration object.

**Chainable**

## withDefaults

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [HttpClientConfiguration](https://hamedfathi.gitbook.io/aurelia-2-doc-api/fetch-client/class/http-client-configuration/httpclientconfiguration) |

**&#128966; Parameter(s)**

_**defaults**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | RequestInit | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Adds an interceptor to be run on all requests or responses.

**Parameter(s)**

| Name        | Description                                                                                                                                                                                                                                                                          |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| interceptor |  An object with request, requestError, response, or responseError methods. request and requestError act as resolve and reject handlers for the Request before it is sent. response and responseError act as resolve and reject handlers for the Response after it has been received. |

**Returns**

The chainable instance of this configuration object.

**Chainable**

## withInterceptor

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [HttpClientConfiguration](https://hamedfathi.gitbook.io/aurelia-2-doc-api/fetch-client/class/http-client-configuration/httpclientconfiguration) |

**&#128966; Parameter(s)**

_**interceptor**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [Interceptor](https://hamedfathi.gitbook.io/aurelia-2-doc-api/fetch-client/interface/interfaces/interceptor) | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Applies a configuration that addresses common application needs, including
configuring same-origin credentials, and using rejectErrorResponses.

**Returns**

The chainable instance of this configuration object.

**Chainable**

## useStandardConfiguration

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [HttpClientConfiguration](https://hamedfathi.gitbook.io/aurelia-2-doc-api/fetch-client/class/http-client-configuration/httpclientconfiguration) |

### &#128366; Summary

Causes Responses whose status codes fall outside the range 200-299 to reject.
The fetch API only rejects on network errors or other conditions that prevent
the request from completing, meaning consumers must inspect Response.ok in the
Promise continuation to determine if the server responded with a success code.
This method adds a response interceptor that causes Responses with error codes
to be rejected, which is common behavior in HTTP client libraries.

**Returns**

The chainable instance of this configuration object.

**Chainable**

## rejectErrorResponses

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [HttpClientConfiguration](https://hamedfathi.gitbook.io/aurelia-2-doc-api/fetch-client/class/http-client-configuration/httpclientconfiguration) |

## withRetry

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [HttpClientConfiguration](https://hamedfathi.gitbook.io/aurelia-2-doc-api/fetch-client/class/http-client-configuration/httpclientconfiguration) |

**&#128966; Parameter(s)**

_**config**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [RetryConfiguration](https://hamedfathi.gitbook.io/aurelia-2-doc-api/fetch-client/interface/interfaces/retryconfiguration) &#124; undefined | ✔  | ✘ | ✘ | - |