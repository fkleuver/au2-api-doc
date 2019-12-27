# &#128712; Attribute(s)

| Modifier(s)                            |
|----------------------------------------|
| export |

# &#128712; Variable(s)

# optional

| Type                        | Initializer                       |
|-----------------------------|-----------------------------------|
| (key: any) =&gt; any | createResolver((key: any, handler: IContainer, requestor: IContainer) =>  {
if (requestor.has(key, true)) {
return requestor.get(key);
} else {
return null;
}
}) |