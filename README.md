# ArcticAdmin
[![Gem Version](https://img.shields.io/gem/v/arctic_admin.svg)](https://rubygems.org/gems/arctic_admin)
[![Gem Downloads](https://img.shields.io/gem/dt/arctic_admin.svg)](https://rubygems.org/gems/arctic_admin)


Simple theme for ActiveAdmin

Complete demo here : https://arctic-admin.herokuapp.com/

admin user : admin@example.com / password

## Installation

Add this to your Gemfile:

```ruby
gem 'arctic_admin'
```

and run `bundle install`.

## Screens

<table>
  <tr>
    <td>
      <a href="./doc/login.png"><img src="./doc/login.png"></a>
    </td>
    <td>
      <a href="./doc/dashboard.png"><img src="./doc/dashboard.png"></a>
    </td>
  </tr>
  <tr>
    <td>
      <a href="./doc/index.png"><img src="./doc/index.png"></a>
    </td>
    <td>
      <a href="./doc/show.png"><img src="./doc/show.png"></a>
    </td>
  </tr>
</table>

## Usage

### CSS

In your `active_admin.css`, include the css file:

```css
/*
 *= require arctic_admin
 */
```
Then restart your webserver if it was previously running.

### Sass Support

If you prefer [SCSS](http://sass-lang.com/documentation/file.SASS_REFERENCE.html), add this to your
`active_admin.css.scss` file:

```scss
@import "arctic_admin";
```

If you use the
[Sass indented syntax](http://sass-lang.com/docs/yardoc/file.INDENTED_SYNTAX.html),
add this to your `active_admin.css.sass` file:

```sass
@import arctic_admin
```

### JS

In your `active_admin.js`, include the js file:

```js
//= require active_admin/base
//= require arctic_admin
```

### Customization

For this, you need to use sass to custom the theme.

You can even change basic color of the theme by placing some other variables:

If you use the [SCSS](http://sass-lang.com/documentation/file.SASS_REFERENCE.html), add this to your
`active_admin.css.scss` file:

```scss
$primary-color: #2dbb43;

@import "arctic_admin";
```

If you use the
[Sass indented syntax](http://sass-lang.com/docs/yardoc/file.INDENTED_SYNTAX.html),
add this to your `active_admin.css.sass` file:

```sass
$primary-color: #2dbb43

@import arctic_admin
```

Then restart your webserver if it was previously running.

## Contributing

1. Fork it ( https://github.com/cle61/arctic_admin/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
