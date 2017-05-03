# \<bootstrap-grid\>

Use Bootstrap responsive 12 column grid styles in a Polymer component.

Inside this element you can use Bootstrap `col-*` classes as if you are in a `container-fluid`.

`--bootstrap-grid-gutter` sets gutters size, default 15px.

Currently the media breakpoints are hard coded, as `@media` queries can't apply CSS variables.

## Example

4 columns on large, 3 on medium, 2 on small and 1 on phone screens:

```html
<bootstrap-grid>
    <bootstrap-row>
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-3">A</div>
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-3">B</div>
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-3">C</div>
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-3">D</div>
    </bootstrap-row>
</bootstrap-grid>
```

## Versions

v1.0.1 is compatible with Polymer 1.

V2.0.0 is for Polymer 2 and above.