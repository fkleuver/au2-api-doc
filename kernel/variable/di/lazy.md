# &#128712; Attribute(s)

| Modifier(s)                            |
|----------------------------------------|
| export |

# &#128712; Variable(s)

# lazy

| Type                        | Initializer                       |
|-----------------------------|-----------------------------------|
| (key: any) =&gt; any | createResolver((key: any, handler: IContainer, requestor: IContainer) =>  {
let instance: unknown = null; // cache locally so that lazy always returns the same instance once resolved
return () => {
if (instance == null) {
instance = requestor.get(key);
}
return instance;
};
}) |