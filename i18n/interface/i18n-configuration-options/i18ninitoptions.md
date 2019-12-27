# I18nInitOptions

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | any |

# &#128712; Property(ies)

### &#128366; Summary

Collection of i18next plugins to use.

## plugins

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | any[] &#124; undefined |

## skipTranslationOnMissingKey

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | boolean &#124; undefined |

### &#128366; Summary

Leeway for computing the time difference for relative time formatting.
If abs(t1 - now) < 1 time_unit, where t1 is the date being formatted, and time_unit is a unit of time such as minute, hour etc.,
then the relative time formatting may sometime produce unexpected results, such as 'in 60 seconds' instead of 'in 1 minute'.
A non-zero rtEpsilon ensures nicer results instead. Default is 0.01. A smaller value for epsilon ensures stricter comparison.

## rtEpsilon

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | number &#124; undefined |