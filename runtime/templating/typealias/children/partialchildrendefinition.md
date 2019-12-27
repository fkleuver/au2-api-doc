# PartialChildrenDefinition

| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | PartialChildrenDefinition&lt;TNode&gt; |

# &#128712; Type Parameter(s)

| Type  | Constraint                                                                           |
| ----- | ------------------------------------------------------------------------------------ |
| TNode | [INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode) |

# &#128712; Initializer

{
callback?: string;
property?: string;
options?: MutationObserverInit;
query?: (projector: IElementProjector<TNode>) => ArrayLike<TNode>;
filter?: (node: TNode, controller?: ICustomElementController<TNode>, viewModel?: ICustomElementViewModel<TNode>) => boolean;
map?: (node: TNode, controller?: ICustomElementController<TNode>, viewModel?: ICustomElementViewModel<TNode>) => any;
}