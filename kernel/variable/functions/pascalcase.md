# &#128366; Summary

Efficiently convert a string to PascalCase.
Non-alphanumeric characters are treated as separators.
Primarily used by Aurelia to convert element names to class names for synthetic types.
Results are cached.

# &#128712; Attribute(s)

| Modifier(s)                            |
|----------------------------------------|
| export |

# &#128712; Variable(s)

# pascalCase

| Type                        | Initializer                       |
|-----------------------------|-----------------------------------|
| (input: string) =&gt; string | (function () {
const cache = Object.create(null) as Record<string, string | undefined>;
return function (input: string): string {
let output = cache[input];
if (output === void 0) {
output = camelCase(input);
if (output.length > 0) {
output = output[0].toUpperCase() + output.slice(1);
}
cache[input] = output;
}
return output;
};
})() |