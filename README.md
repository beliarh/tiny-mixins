Tiny Mixins (Sass):
===================

Clearfix
--------
```scss
@mixin clearfix() { /* ... */ }
```

**Usage:**  
```scss
.container {
    @include clearfix;
}
```

Reset
-----
```scss
@mixin reset() { /* ... */ }
```

**Usage:**  
```scss
@include reset;
```

Triangle
--------
```scss
@mixin triangle($direction, $width, $height, $color) { /* ... */ }
```

**Arguments:**
* **$direction**: to (top|right|bottom|left){1, 2}
* **$width**: width
* **$height**: height
* **$color**: color

**Usage:**  
```scss
.element {
    @include triangle(to right bottom, 30px, 25px, #000);
}
```
