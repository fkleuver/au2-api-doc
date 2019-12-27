# &#128712; Attribute(s)

| Modifier(s)                            |
|----------------------------------------|
| export |

# &#128712; Literal(s)

## RouterConfiguration

| Type                        | Array                           |
|-----------------------------|---------------------------------|
| { register(container: IContainer): IContainer; createContainer(): IContainer; customize(config?: [[IRouter](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/router/irouter)Options](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/router/irouteroptions) &#124; ((router: IRouter) =&gt; void) &#124; undefined): { register(container: IContainer): IContainer; createContainer(): IContainer; }; } | ✘ |

## 🟆 Member(s)

### &#128712; Attribute(s)

| Object                        |
|-------------------------------|
| ✔ |

### &#128712; Assignment(s)

### routerConfiguration

| Type                      | Shorthand                         | Spread                        |
|---------------------------|:---------------------------------:|:-----------------------------:|
| { register(container: IContainer): IContainer; createContainer(): IContainer; customize(config?: [[IRouter](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/router/irouter)Options](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/router/irouteroptions) &#124; ((router: IRouter) =&gt; void) &#124; undefined): { register(container: IContainer): IContainer; createContainer(): IContainer; }; } | ✘  | ✔ |

### Value

-

### &#128712; Method(s)

### &#128366; Summary

Make it possible to specify options to Router activation.
Parameter is either a config object that's passed to Router's activate
or a config function that's called instead of Router's activate.

## customize

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | { register(container: IContainer): IContainer; createContainer(): IContainer; } |

**&#128966; Parameter(s)**

_**config**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [[IRouter](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/router/irouter)Options](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/router/irouteroptions) &#124; ((router: IRouter) =&gt; void) &#124; undefined | ✔  | ✘ | ✘ | - |