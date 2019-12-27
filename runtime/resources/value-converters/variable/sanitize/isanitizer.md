# &#128712; Attribute(s)

| Modifier(s)                            |
|----------------------------------------|
| export |

# &#128712; Variable(s)

# ISanitizer

| Type                        | Initializer                       |
|-----------------------------|-----------------------------------|
| InterfaceSymbol&lt;[ISanitizer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/resources/value-converters/interface/sanitize/isanitizer)&gt; | DI.createInterface<ISanitizer>('ISanitizer').withDefault(x => x.singleton(class {
public sanitize(input: string): string {
return input.replace(SCRIPT_REGEX, '');
}
})) |