# Bagel Boilerplate

Bagel requires node v0.10 and Sass >=v3.3

---

### Getting started

```npm install && grunt```

This will download [bagel-core](https://github.com/goodtwin/bagel-core), which in turn downloads
[bagel-functions](https://github.com/goodtwin/bagel-functions),
[bagel-layout](https://github.com/goodtwin/bagel-layout), and
[bagel-abstractions](https://github.com/goodtwin/bagel-abstractions).

By their powers combined, you get a base Sass authoring framework (resusable mixins, layout utility helpers, and structural abstractions),
a set of base components (from buttons to inputs to dropdowns), a base prototype theme for those components to allow rapid UI prototyping,
and a methodology for creating your own themes/chrome.

### Configuration
Values in config.yml allow you choose exactly what you want from each layer as well as set sizing variables to be used throughout.

### Guide
By default, bagel-boilerplate will use the styleguide documentation from bagel-core.
Overrides to any styleguide document can be made by creating your own file in guide/.
See [bagel-core guides](https://github.com/goodtwin/bagel-core/tree/master/guide) for examples.

### Mockups
Mockups can be created directly in bagel via mockups/. As with guides/, we use [Assemble](http://assemble.io) under the hood.
