| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | - |

## &#128712; Decorators(s)

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| inject | ✔  |

| Argument(s)                                           |
|-------------------------------------------------------|
| IRouter  |
| INode  |

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| customElement | ✔  |

| Argument(s)                                           |
|-------------------------------------------------------|
| {
name: 'au-nav', template:
`<template>
<nav if.bind="name" class="\${name} \${navClasses.nav}">
<au-nav routes.bind="navRoutes" classes.bind="navClasses" containerless></au-nav>
</nav>
<ul if.bind="routes" class="nav-level-\${level} \${classes.ul}">
<li repeat.for="route of routes" if.bind="route.visible" class="\${route.active ? classes.liActive : ''} \${route.hasChildren} \${classes.li}">
<a if.bind="route.link && route.link.length" goto="\${route.link}" class="\${route.active ? classes.aActive : ''} \${classes.a}" innerhtml.bind="route.title"></a>
<a if.bind="route.execute" click.trigger="route.executeAction($event)" href="" class="\${route.active ? classes.aActive : ''} \${classes.a}" innerhtml.bind="route.title"></a>
<span if.bind="(!route.link || !route.link.length) && !route.execute && !route.children" class="\${route.active ? classes.aActive : ''} \${classes.span} nav-separator" innerhtml.bind="route.title"></span>
<a if.bind="(!route.link || !route.link.length) && !route.execute && route.children" click.delegate="route.toggleActive()" href="" class="\${route.active ? classes.aActive : ''} \${classes.a}" innerhtml.bind="route.title"></a>
<au-nav if.bind="route.children" routes.bind="route.children" level.bind="level + 1" classes.bind="classes" containerless></au-nav>
</li>
</ul>
</template>` }  |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**router**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IRouter](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/router/irouter) | ✘  | ✘ | ✔ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128966; Decorators(s)**

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| bindable | ✘  |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**name**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128966; Decorators(s)**

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| bindable | ✘  |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**routes**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128966; Decorators(s)**

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| bindable | ✘  |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**level**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128966; Decorators(s)**

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| bindable | ✘  |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**classes**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

# &#128712; Get Accessor(s)

## navRoutes

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

## navClasses

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

# &#128712; Method(s)

## active

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | string |

**&#128966; Parameter(s)**

_**route**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [NavRoute](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/nav-route/navroute) | ✘  | ✘ | ✘ | - |