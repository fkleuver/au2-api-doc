# &#128712; Attribute(s)

| Modifier(s)                            |
|----------------------------------------|
| export |

# &#128712; Variable(s)

# ISVGAnalyzer

| Type                        | Initializer                       |
|-----------------------------|-----------------------------------|
| InterfaceSymbol&lt;[ISVGAnalyzer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime-html/observation/interface/svg-analyzer/isvganalyzer)&gt; | DI.createInterface<ISVGAnalyzer>('ISVGAnalyzer').withDefault(x => x.singleton(class {
public isStandardSvgAttribute(node: INode, attributeName: string): boolean {
return false;
}
})) |