# &#128712; Attribute(s)

| Modifier(s)                            |
|----------------------------------------|
| export |

# &#128712; Variable(s)

# Registration

| Type                        | Initializer                       |
|-----------------------------|-----------------------------------|
| { instance&lt;T&gt;(key: Key, value: T): [IRegistration](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/iregistration)&lt;T&gt;; singleton&lt;T&#95;1 extends Constructable&lt;{}&gt;&gt;(key: Key, value: T&#95;1): IRegistration&lt;InstanceType&lt;T&#95;1&gt;&gt;; transient&lt;T&#95;2 extends Constructable&lt;{}&gt;&gt;(key: Key, value: T&#95;2): IRegistration&lt;InstanceType&lt;T&#95;2&gt;&gt;; callback&lt;T&#95;3&gt;(key: Key, callback: ResolveCallback&lt;T&#95;3&gt;): IRegistration&lt;Resolved&lt;T&#95;3&gt;&gt;; alias&lt;T&#95;4&gt;(originalKey: T&#95;4, aliasKey: Key): IRegistration&lt;Resolved&lt;T&#95;4&gt;&gt;; defer(key: Key, ...params: unknown[]): [IRegistry](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/iregistry); } | - |