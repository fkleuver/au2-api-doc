## &#128366; Summary

Simple html sanitization converter to preserve whitelisted elements and attributes on a bound property containing html.

| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | - |

## &#128712; Decorators(s)

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| valueConverter | ✔  |

| Argument(s)                                           |
|-------------------------------------------------------|
| 'sanitize'  |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Decorator(s)**

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| ISanitizer | ✘  |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**sanitizer**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [ISanitizer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/resources/value-converters/interface/sanitize/isanitizer) | ✘  | ✘ | ✔ |

# &#128712; Method(s)

### &#128366; Summary

Process the provided markup that flows to the view.

**Parameter(s)**

| Name            | Description                            |
| --------------- | -------------------------------------- |
| untrustedMarkup |  The untrusted markup to be sanitized. |

## toView

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | string &#124; null |

**&#128966; Parameter(s)**

_**untrustedMarkup**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |