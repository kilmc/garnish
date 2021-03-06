# Garnish

Garnish for your Sassy CSS cocktails. Made to be used on top of [Bourbon](http://bourbon.io).

## Usage

1. [Download as zip](https://github.com/paulozoom/garnish/archive/master.zip). (Bower coming soon)
2. Include Garnish in your code with `@include "src/garnish"`

## Included Mixins

### Helpers

**Grayscale Colours**  
A simple mixin to create gray colours at varying degrees of lightness

```SCSS
.margarita-salt {
  color: gray(40%);
}
```

**Hover Fix for Leopard**  
This will add :hover and :focus states to whatever content you add to the @include

```SCSS
.mint {
  color: #4183C4;
  @include hover {
    color: #333;
  }
}
```

## Development

### Rules

- Including Garnish should create no output. All code should be mixins and functions.
- Garnish code should make no style decisions or assumptions. Defaults are OK.
- Although using Bourbon is encouraged, Garnish should be library-agnostic.

### Contributing

Issues and pull requests are welcome.
