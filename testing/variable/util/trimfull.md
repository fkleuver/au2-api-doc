# &#128712; Attribute(s)

| Modifier(s)                            |
|----------------------------------------|
| export |

# &#128712; Variable(s)

# trimFull

| Type                        | Initializer                       |
|-----------------------------|-----------------------------------|
| (input: string) =&gt; string | (function () {
const cache: Record<string, string | undefined> = {};
return function (input: string) {
let result = cache[input];
if (result === void 0) {
result = '';
const length = input.length;
let ch = 0;
for (let i = 0; i < length; ++i) {
ch = input.charCodeAt(i);
if (ch > 0x20) {
result += String.fromCharCode(ch);
}
}
cache[input] = result;
}
return result;
};
}()) |