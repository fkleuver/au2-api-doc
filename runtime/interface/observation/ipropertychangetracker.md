# &#128366; Summary

Describes a type that specifically tracks changes in an object property, or simply something that can have a getter and/or setter

# IPropertyChangeTracker

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | - |

# &#128712; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| TObj | -          |

| Type  | Constraint |
| ----- | ---------- |
| TProp | -          |

| Type   | Constraint |
| ------ | ---------- |
| TValue | -          |

# &#128712; Property(ies)

## obj

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | TObj |

## propertyKey

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | TProp &#124; undefined |

## currentValue

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | TValue &#124; undefined |