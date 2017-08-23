# Children.scss
A Scss mixin which will help you to manage the style of :nth-child elements.

## Example

```
@include child((
  type: in-between,
  min: 4,
  max: 10
  )...) {
    color: #fff;
  }
```
