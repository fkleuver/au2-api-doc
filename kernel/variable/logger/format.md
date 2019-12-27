# &#128366; Summary

http:en.wikipedia.org/wiki/ANSI_escape_code#graphics

# &#128712; Attribute(s)

| Modifier(s)                            |
|----------------------------------------|
| export |

# &#128712; Variable(s)

# format

| Type                        | Initializer                       |
|-----------------------------|-----------------------------------|
| { readonly red: &lt;T extends string&gt;(str: T) =&gt; T; readonly green: &lt;T extends string&gt;(str: T) =&gt; T; readonly yellow: &lt;T extends string&gt;(str: T) =&gt; T; readonly blue: &lt;T extends string&gt;(str: T) =&gt; T; readonly magenta: &lt;T extends string&gt;(str: T) =&gt; T; readonly cyan: &lt;T extends string&gt;(str: T) =&gt; T; readonly white: &lt;T extends string&gt;(str: T) =&gt; T; readonly grey: &lt;T extends string&gt;(str: T) =&gt; T; } | toLookup({
red<T extends string>(str: T): T {
return `\u001b[31m${str}\u001b[39m` as T;
},
green<T extends string>(str: T): T {
return `\u001b[32m${str}\u001b[39m` as T;
},
yellow<T extends string>(str: T): T {
return `\u001b[33m${str}\u001b[39m` as T;
},
blue<T extends string>(str: T): T {
return `\u001b[34m${str}\u001b[39m` as T;
},
magenta<T extends string>(str: T): T {
return `\u001b[35m${str}\u001b[39m` as T;
},
cyan<T extends string>(str: T): T {
return `\u001b[36m${str}\u001b[39m` as T;
},
white<T extends string>(str: T): T {
return `\u001b[37m${str}\u001b[39m` as T;
},
grey<T extends string>(str: T): T {
return `\u001b[90m${str}\u001b[39m` as T;
},
} as const) |