# ember-cli-transformicons

[![npm badge][npm-badge-png]][npm-url]

[![github release versions][github-release-svg]][github-release-url]
[![npm downloads per month][npm-dm-badge-svg]][npm-url]
[![build status][travis-badge]][travis-url]

This README outlines the details of collaborating on this Ember addon.

## Installation
Install the addon with Ember CLI directly

```shell
ember install:addon ember-cli-transformicons
```

*OR* You may install via `npm`:

```shell
npm install ember-cli-transformicons --save
```
## Usage
Usage is very simple. Add the transformicon you want from within your `template`.

`type` is an optional parameter. If you do not provide a specific type for an icon category, then the default type will simply be provided for you.

### Menu
```handlebars
{{t-menu type="butterfly"}}
{{t-menu type="minus"}}
{{t-menu type="x-cross"}}
{{t-menu type="arrow-up"}}
{{t-menu type="arrow-360-left"}}
{{t-menu type="arrow-left"}}
```

### Grid
```handlebars
{{t-grid type="rearrange"}}
{{t-grid type="collapse"}}
```

### Add/Remove
```handlebars
{{t-plus type="minus"}}
{{t-plus type="check"}}
{{t-plus type="minus-fold"}}
{{t-plus type="circle"}}
```

### Mail
```handlebars
{{t-mail}}
```

### Video
```handlebars
{{t-video}}
```

### Loader
```handlebars
{{t-loader}}
```

## Contributing
**Please contribute!** This section outlines the details of collaborating on this Ember addon. You can help code, design, update documentation, fix typos, raise issues and much more. 

Any help is welcome and absolutely appreciated!

## Backlog

- [ ] Modularize components/Refactor
- [ ] Add proper action/event handling for the hosting application
- [ ] Add/Update transformicons

## Installation

* `git clone` this repository
* `npm install`
* `bower install`

## Running

* `ember server`
* Visit your app at http://localhost:4200.

## Running Tests

* `ember test`
* `ember test --server`

## Building

* `ember build`

For more information on using ember-cli, visit [http://www.ember-cli.com/](http://www.ember-cli.com/).



[npm-url]: https://www.npmjs.com/package/ember-cli-transformicons
[github-release-url]: https://github.com/alexdiliberto/ember-cli-transformicons/releases
[npm-dm-badge-svg]: https://img.shields.io/npm/dm/ember-cli-transformicons.svg
[npm-badge-png]: https://nodei.co/npm/ember-cli-transformicons.png?downloads=true&stars=true
[github-release-svg]: https://img.shields.io/github/release/alexdiliberto/ember-cli-transformicons.svg
[travis-badge]: https://travis-ci.org/alexdiliberto/ember-cli-transformicons.svg?branch=master
[travis-url]: https://travis-ci.org/alexdiliberto/ember-cli-transformicons
