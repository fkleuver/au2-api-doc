# &#128712; Attribute(s)

| Modifier(s)                            |
|----------------------------------------|
| export |

# &#128712; Variable(s)

# getPrototypeChain

| Type                        | Initializer                       |
|-----------------------------|-----------------------------------|
| &lt;T extends Constructable&lt;{}&gt;&gt;(Type: T) =&gt; readonly [T, ...Constructable&lt;{}&gt;[]] | (function () {
const functionPrototype = Function.prototype;
// eslint-disable-next-line @typescript-eslint/unbound-method
const getPrototypeOf = Object.getPrototypeOf;
const cache = new WeakMap<Constructable, [Constructable, ...Constructable[]]>();
let proto = functionPrototype as Constructable;
let i = 0;
let chain: [Constructable, ...Constructable[]] | undefined = void 0;
return function <T extends Constructable> (Type: T): readonly [T, ...Constructable[]] {
chain = cache.get(Type);
if (chain === void 0) {
cache.set(Type, chain = [proto = Type]);
i = 0;
while ((proto = getPrototypeOf(proto)) !== functionPrototype) {
chain[++i] = proto;
}
}
return chain as [T, ...Constructable[]];
};
})() |