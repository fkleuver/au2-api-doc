## &#128366; Summary

An HTTP client based on the Fetch API.

| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | - |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Decorator(s)**

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| IDOM | ✘  |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**dom**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [HTMLDOM](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime-html/class/dom/htmldom) | ✘  | ✘ | ✔ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128366; Summary**

The current number of active requests.
Requests being processed by interceptors are considered active.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**activeRequestCount**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128366; Summary**

Indicates whether or not the client is currently making one or more requests.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**isRequesting**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128366; Summary**

Indicates whether or not the client has been configured.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**isConfigured**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128366; Summary**

The base URL set by the config.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**baseUrl**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128366; Summary**

The default request init to merge with values specified at request time.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**defaults**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128366; Summary**

The interceptors to be run during requests.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**interceptors**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

# &#128712; Method(s)

### &#128366; Summary

Configure this client with default settings to be used by all requests.

**Parameter(s)**

| Name   | Description                                                                          |
| ------ | ------------------------------------------------------------------------------------ |
| config |  A configuration object, or a function that takes a config object and configures it. |

**Returns**

The chainable instance of this HttpClient.

**Chainable**

## configure

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [HttpClient](https://hamedfathi.gitbook.io/aurelia-2-doc-api/fetch-client/class/http-client/httpclient) |

**&#128966; Parameter(s)**

_**config**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | RequestInit &#124; [HttpClientConfiguration](https://hamedfathi.gitbook.io/aurelia-2-doc-api/fetch-client/class/http-client-configuration/httpclientconfiguration) &#124; ((config: HttpClientConfiguration) =&gt; HttpClientConfiguration) | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Starts the process of fetching a resource. Default configuration parameters
will be applied to the Request. The constructed Request will be passed to
registered request interceptors before being sent. The Response will be passed
to registered Response interceptors before it is returned.
See also https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API

**Parameter(s)**

| Name  | Description                                                                                                    |
| ----- | -------------------------------------------------------------------------------------------------------------- |
| input |  The resource that you wish to fetch. Either a Request object, or a string containing the URL of the resource. |
| init  |  An options object containing settings to be applied to the Request.                                           |

**Returns**

A Promise for the Response from the fetch request.

## fetch

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | Promise&lt;Response&gt; |

**&#128966; Parameter(s)**

_**input**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; Request | ✘  | ✘ | ✘ | - |

_**init**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | RequestInit &#124; undefined | ✔  | ✘ | ✘ | - |

## buildRequest

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | Request |

**&#128966; Parameter(s)**

_**input**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; Request | ✘  | ✘ | ✘ | - |

_**init**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | RequestInit &#124; undefined | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Calls fetch as a GET request.

**Parameter(s)**

| Name  | Description                                                                                                    |
| ----- | -------------------------------------------------------------------------------------------------------------- |
| input |  The resource that you wish to fetch. Either a Request object, or a string containing the URL of the resource. |
| init  |  An options object containing settings to be applied to the Request.                                           |

**Returns**

A Promise for the Response from the fetch request.

## get

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | Promise&lt;Response&gt; |

**&#128966; Parameter(s)**

_**input**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; Request | ✘  | ✘ | ✘ | - |

_**init**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | RequestInit &#124; undefined | ✔  | ✘ | ✘ | - |

### &#128366; Summary

Calls fetch with request method set to POST.

**Parameter(s)**

| Name  | Description                                                                                                    |
| ----- | -------------------------------------------------------------------------------------------------------------- |
| input |  The resource that you wish to fetch. Either a Request object, or a string containing the URL of the resource. |
| body  |  The body of the request.                                                                                      |
| init  |  An options object containing settings to be applied to the Request.                                           |

**Returns**

A Promise for the Response from the fetch request.

## post

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | Promise&lt;Response&gt; |

**&#128966; Parameter(s)**

_**input**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; Request | ✘  | ✘ | ✘ | - |

_**body**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; ArrayBuffer &#124; Blob &#124; ArrayBufferView &#124; FormData &#124; URLSearchParams &#124; ReadableStream&lt;Uint8Array&gt; &#124; undefined | ✔  | ✘ | ✘ | - |

_**init**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | RequestInit &#124; undefined | ✔  | ✘ | ✘ | - |

### &#128366; Summary

Calls fetch with request method set to PUT.

**Parameter(s)**

| Name  | Description                                                                                                    |
| ----- | -------------------------------------------------------------------------------------------------------------- |
| input |  The resource that you wish to fetch. Either a Request object, or a string containing the URL of the resource. |
| body  |  The body of the request.                                                                                      |
| init  |  An options object containing settings to be applied to the Request.                                           |

**Returns**

A Promise for the Response from the fetch request.

## put

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | Promise&lt;Response&gt; |

**&#128966; Parameter(s)**

_**input**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; Request | ✘  | ✘ | ✘ | - |

_**body**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; ArrayBuffer &#124; Blob &#124; ArrayBufferView &#124; FormData &#124; URLSearchParams &#124; ReadableStream&lt;Uint8Array&gt; &#124; undefined | ✔  | ✘ | ✘ | - |

_**init**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | RequestInit &#124; undefined | ✔  | ✘ | ✘ | - |

### &#128366; Summary

Calls fetch with request method set to PATCH.

**Parameter(s)**

| Name  | Description                                                                                                    |
| ----- | -------------------------------------------------------------------------------------------------------------- |
| input |  The resource that you wish to fetch. Either a Request object, or a string containing the URL of the resource. |
| body  |  The body of the request.                                                                                      |
| init  |  An options object containing settings to be applied to the Request.                                           |

**Returns**

A Promise for the Response from the fetch request.

## patch

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | Promise&lt;Response&gt; |

**&#128966; Parameter(s)**

_**input**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; Request | ✘  | ✘ | ✘ | - |

_**body**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; ArrayBuffer &#124; Blob &#124; ArrayBufferView &#124; FormData &#124; URLSearchParams &#124; ReadableStream&lt;Uint8Array&gt; &#124; undefined | ✔  | ✘ | ✘ | - |

_**init**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | RequestInit &#124; undefined | ✔  | ✘ | ✘ | - |

### &#128366; Summary

Calls fetch with request method set to DELETE.

**Parameter(s)**

| Name  | Description                                                                                                    |
| ----- | -------------------------------------------------------------------------------------------------------------- |
| input |  The resource that you wish to fetch. Either a Request object, or a string containing the URL of the resource. |
| body  |  The body of the request.                                                                                      |
| init  |  An options object containing settings to be applied to the Request.                                           |

**Returns**

A Promise for the Response from the fetch request.

## delete

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | Promise&lt;Response&gt; |

**&#128966; Parameter(s)**

_**input**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; Request | ✘  | ✘ | ✘ | - |

_**body**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; ArrayBuffer &#124; Blob &#124; ArrayBufferView &#124; FormData &#124; URLSearchParams &#124; ReadableStream&lt;Uint8Array&gt; &#124; undefined | ✔  | ✘ | ✘ | - |

_**init**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | RequestInit &#124; undefined | ✔  | ✘ | ✘ | - |

## trackRequestStart

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | void |

## trackRequestEnd

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | void |

## processRequest

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | Promise&lt;Request &#124; Response&gt; |

**&#128966; Parameter(s)**

_**request**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Request | ✘  | ✘ | ✘ | - |

_**interceptors**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [Interceptor](https://hamedfathi.gitbook.io/aurelia-2-doc-api/fetch-client/interface/interfaces/interceptor)[] | ✘  | ✘ | ✘ | - |

## processResponse

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | Promise&lt;Request &#124; Response&gt; |

**&#128966; Parameter(s)**

_**response**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Promise&lt;Response&gt; | ✘  | ✘ | ✘ | - |

_**interceptors**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [Interceptor](https://hamedfathi.gitbook.io/aurelia-2-doc-api/fetch-client/interface/interfaces/interceptor)[] | ✘  | ✘ | ✘ | - |

_**request**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Request | ✘  | ✘ | ✘ | - |

## applyInterceptors

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | Promise&lt;Request &#124; Response&gt; |

**&#128966; Parameter(s)**

_**input**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Request &#124; Promise&lt;Request &#124; Response&gt; | ✘  | ✘ | ✘ | - |

_**interceptors**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [Interceptor](https://hamedfathi.gitbook.io/aurelia-2-doc-api/fetch-client/interface/interfaces/interceptor)[] &#124; undefined | ✘  | ✘ | ✘ | - |

_**successName**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | "request" &#124; "requestError" &#124; "response" &#124; "responseError" | ✘  | ✘ | ✘ | - |

_**errorName**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | "request" &#124; "requestError" &#124; "response" &#124; "responseError" | ✘  | ✘ | ✘ | - |

_**interceptorArgs**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | unknown[] | ✔  | ✔ | ✘ | - |

## callFetch

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | Promise&lt;Response&gt; |

**&#128966; Parameter(s)**

_**input**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; Request | ✘  | ✘ | ✘ | - |

_**body**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; ArrayBuffer &#124; Blob &#124; ArrayBufferView &#124; FormData &#124; URLSearchParams &#124; ReadableStream&lt;Uint8Array&gt; &#124; undefined | ✘  | ✘ | ✘ | - |

_**init**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | RequestInit &#124; undefined | ✘  | ✘ | ✘ | - |

_**method**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |