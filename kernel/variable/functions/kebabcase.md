# &#128366; Summary

Efficiently convert a string to kebab-case.
Non-alphanumeric characters are treated as separators.
Primarily used by Aurelia to convert ViewModel property names to DOM attribute names.
Results are cached.

# &#128712; Attribute(s)

| Modifier(s)                            |
|----------------------------------------|
| export |

# &#128712; Variable(s)

# kebabCase

| Type                        | Initializer                       |
|-----------------------------|-----------------------------------|
| (input: string) =&gt; string | (function () {
const cache = Object.create(null) as Record<string, string | undefined>;
function callback(char: string, sep: boolean): string {
return sep ? `-${char.toLowerCase()}` : char.toLowerCase();
}
return function (input: string): string {
let output = cache[input];
if (output === void 0) {
output = cache[input] = baseCase(input, callback);
}
return output;
};
})() |