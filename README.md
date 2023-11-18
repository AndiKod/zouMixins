# zouMixins

Collection of actual SCSS mixins projects, all in one place to be used in other projects.

## Install

From NPM

```shell
npm i zoumixins --save-dev
```

Addapt the path to the needed depth in regard to the root folder when importing a collection in a SCSS file.

### Libraries

_...obviously just a beginning, to start the collection._

## [CSSOwl](https://cssowl.owl-stars.com/documentation.html#absolute)

_In the SCSS_

```scss
@use "../../node_modules/zoumixins/cssowl/before" as owl;

.star {
  @include owl.cssowl-before-float("*", 4px 10px 0 0);
}
```

_In the HTML_

```html
<h2 class="star">Some title marked with a star</h2>
```

### Mixin Groups

- [Absolute](https://cssowl.owl-stars.com/documentation.html#absolute)
- [After](https://cssowl.owl-stars.com/documentation.html#after)
- [Before](https://cssowl.owl-stars.com/documentation.html#before)
- [Coords](https://cssowl.owl-stars.com/documentation.html#coords)
- [Relative](https://cssowl.owl-stars.com/documentation.html#relative)
- [Sprite](https://cssowl.owl-stars.com/documentation.html#sprite)
- [Text](https://cssowl.owl-stars.com/documentation.html#text)

#### Changelog

1.0.0
Hello
