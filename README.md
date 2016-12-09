# \<json-box\>

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://beta.webcomponents.org/element/sbeleidy/json-box)
[![Join the chat](https://badges.gitter.im/gitterHQ/gitterHQ.github.io.svg)](https://gitter.im/sbeleidy/general)

A webcomponent that converts its input string to an object that is returned through a property.
Useful for displaying current object and allowing modifications.

## Install

```
bower install sbeleidy/json-box --save
```

## Usage

For displaying and editing an object:
<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="json-box.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->

```html
<json-box label="A JSON object" current="{{current}}" show-buttons max-rows="5"></json-box>

<!-- Demo -->
<br>
Current hello property: [[current.hello]]
<!-- End demo-->
```

For displaying an object and disabling editing:
<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="json-box.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->

```html
<json-box label="A JSON object" current="[[current]]" disabled></json-box>
```

## Contributing

### Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

### Viewing Your Application

```
$ polymer serve
```

### Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

### Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
