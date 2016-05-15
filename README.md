# Simple Responsive Grid System with SaSS
Simple reponsive grid system with [SaSS](http://sass-lang.com/) similar to [Bootstrap](http://getbootstrap.com/css/#grid).

View result at [simple responsive grid system](http://huyb1991.github.io/sass-simple-responsive-grid-system).

## Customize
Custom number of column at `$grid-number-column`.
Custom column spacing at `$grid-column-spacing`.
Custom media query with `$screen-sm-max` and `$screen-md-max`.

Default is 12 columns and space is 1% padding (padding-left 0.5% and padding-right: 0.5%) with 3 kind of devices are: **small** (<768px), **medium** (≥768px and <1024px) and **large** (≥1024px).
```
$grid-number-column:  12;
$grid-column-spacing: 1%;
$screen-sm-max:       768px;
$screen-md-max:       1024px;
```