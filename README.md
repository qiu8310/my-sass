# my-sass


## quantity

* `@mixin equal-to-one()`
* `@mixin more-than-one()`
* `@mixin equal-to($total)`
* `@mixin nth-equal-to($total, $n)`
* `@mixin more-or-equal-than($n)`
* `@mixin more-than($n)`
* `@mixin less-or-equal-than($n)`
* `@mixin less-than($n)`
* `@mixin grid($cols)`


__Examples__


```scss

.list li {
  @include equal-to(10) {  // If there are ten `li` items in the `.list`
    //...
  }
}

```

[Live Examples](http://codepen.io/qiu8310/pen/bdWbvm)

_Inspired by [quantity-queries-for-css](http://alistapart.com/article/quantity-queries-for-css) and [heydon](http://codepen.io/heydon/pen/bcdrl)_
