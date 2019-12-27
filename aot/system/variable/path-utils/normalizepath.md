# &#128712; Attribute(s)

| Modifier(s)                            |
|----------------------------------------|
| export |

# &#128712; Variable(s)

# normalizePath

| Type                        | Initializer                       |
|-----------------------------|-----------------------------------|
| (path: string) =&gt; string | (function () {
const cache: Record<string, string | undefined> = Object.create(null);
const regex = /\\/g;
return function (path: string) {
let normalized = cache[path];
if (normalized === void 0) {
normalized = cache[path] = path.replace(regex, '/');
}
return normalized;
};
})() |