# `numberformat`
The `numberformat` filter is used to format a decimal number. Behind the scenes it uses `java.text.DecimalFormat`.
```
{{ 3.141592653 | numberformat("#.##") }}
```
The above example will output the following:
```
3.14
```

## Argumnets
- format