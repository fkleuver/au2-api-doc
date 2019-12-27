# &#128366; Summary

stringModuleWrap is to deal with pure css text module import in shadowDOM mode.
For webpack:
import d0 from '!!raw-loader!./foo.css';
For dumber/requirejs:
import d0 from 'text!./foo.css';
We cannot use
import d0 from './foo.css';
because most bundler by default will inject that css into HTML head.

# preprocessHtmlTemplate

| Modifier(s)                            | Return Type                    | Generator                        | Overload                         | Implementation                        |
|----------------------------------------|--------------------------------|:--------------------------------:|:--------------------------------:|:-------------------------------------:|
| export | ModifyCodeResult | ✘ | ✘  | ✔ |

## &#128966; Parameter(s)

_**unit**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IFileUnit](https://hamedfathi.gitbook.io/aurelia-2-doc-api/plugin-conventions/interface/options/ifileunit) | ✘  | ✘ | ✘ | - |

_**options**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IPreprocessOptions](https://hamedfathi.gitbook.io/aurelia-2-doc-api/plugin-conventions/interface/options/ipreprocessoptions) | ✘  | ✘ | ✘ | - |