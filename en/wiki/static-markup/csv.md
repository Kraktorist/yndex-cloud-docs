# Formatting CSV data

To display CSV data as a table, use the following markup:

```
%%(csv delimiter=; head=1)
Heading 1; Heading 2; Heading 3
cell 11;cell 12;cell 13
cell 21; cell 22; cell 23
%%
```

{% cut "See the result" %}

![](../../_assets/wiki/csv-table.png)

{% endcut %}

Markup parameters:

* `delimiter`: a field separator used in CSV tables.

* `head`: if set to 1, the first row of the table becomes a header.

{% note info %}

You can't use [text formatting elements](formatting.md) in CSV tables.

{% endnote %}

#### See also

* [Insert diagrams and flowcharts](diagram.md)

* [Insert formulas](formulas.md)
