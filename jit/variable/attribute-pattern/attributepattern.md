# &#128712; Attribute(s)

| Modifier(s)                            |
|----------------------------------------|
| export |

# &#128712; Variable(s)

# AttributePattern

| Type                        | Initializer                       |
|-----------------------------|-----------------------------------|
| [AttributePattern](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit/interface/attribute-pattern/attributepattern) | Object.freeze({
name: Protocol.resource.keyFor('attribute-pattern'),
definitionAnnotationKey: 'attribute-pattern-definitions',
define<TProto, TClass>(
patternDefs: AttributePatternDefinition[],
Type: DecoratableAttributePattern<TProto, TClass>,
) {
validatePrototype(Type.prototype as IAttributePattern, patternDefs);
const definition = new AttributePatternResourceDefinition(Type);
const { name, definitionAnnotationKey } = AttributePattern;
Metadata.define(name, definition, Type);
Protocol.resource.appendTo(Type, name);
Protocol.annotation.set(Type, definitionAnnotationKey, patternDefs);
Protocol.annotation.appendTo(Type, definitionAnnotationKey);
return Type as DecoratedAttributePattern<TProto, TClass>;
},
getPatternDefinitions<TProto, TClass>(Type: DecoratedAttributePattern<TProto, TClass>) {
return Protocol.annotation.get(Type, AttributePattern.definitionAnnotationKey) as AttributePatternDefinition[];
}
}) |