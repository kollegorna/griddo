# Griddo

Griddo is a collection of SCSS mixins that helps you build grids. 

It handles grids and only grids. No responsive/breakpointy stuff. You'll have to provide that by yourself. Hello separation of concerns.

We'll deal with better documentation and examples when we can.

Questions? Ask [@persand](https://twitter.com/persand) or [open an issue](https://github.com/kollegorna/griddo/issues).

### Thank you:

Griddo is mostly inspired by [Zurb Foundation](http://foundation.zurb.com) and also [csswizardy-grids](http://csswizardry.com/2013/02/introducing-csswizardry-grids/)</a>.

## Installation

Add this line to your application's Gemfile:

    gem 'griddo'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install griddo

## Usage

**HTML**

```html
<main>
  <article></article>
  <aside></aside>
</main>
```

**SCSS**

```scss
main {
  @include griddo-row;
}

article {
  @include griddo-column(8);
}

aside {
  @include griddo-column(4);
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
