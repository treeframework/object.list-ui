# list-ui

The `list-ui` object creates blocky, keyline-delimited list items.

## Dependencies

The `list-ui` object depends on two other modules:

* [settings.defaults](https://github.com/treeframework/settings.defaults)
* [tools.functions](https://github.com/treeframework/tools.functions)

If you install the `list-ui` object using Bower or npm, you will get these 
dependencies at the same time. If not using Bower or npm, please be sure to 
install and `@import` these dependencies in the relevant way.

## Installation

You can install `list-ui` module via Bower, npm, or copy and paste.

### Install using Bower:

```sh
$ bower install tree-list-ui --save
```

Once installed, `@import` into your project in its Object layer:

```scss
@import "bower_components/tree-list-ui/object.list-ui";
```

### Install using npm:

```sh
$ npm install tree-list-ui --save
```

### Install via file download

The least recommended option for installation is to simply download
`_object.list-ui.scss` into your project and `@import` it into your project in
its Object layer.

## Usage

Basic usage of the `list-ui` object uses the required classes:

```html
<ul class="o-list-ui">
    <li class="o-list-ui__item">...</li>
    <li class="o-list-ui__item">...</li>
    <li class="o-list-ui__item">...</li>
</ul>
```

The only valid children of the `.o-list-ui` node is `.o-list-ui__item`.

## Options

Other, optional classes can supplement the required base classes:

* `.o-list-ui--[tiny|small|large|huge]`: alter the spacing between list-ui 
items.

For example:

```html
<ul class="o-list-ui  o-list-ui--large">
    <li class="o-list-ui__item">...</li>
    <li class="o-list-ui__item">...</li>
    <li class="o-list-ui__item">...</li>
</ul>
```

## Credits

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.
