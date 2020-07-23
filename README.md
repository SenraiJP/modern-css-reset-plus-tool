# A modern CSS reset plus tool

![The Uncompressed size of this reset](https://img.badgesize.io/https://unpkg.com/modern-css-reset-plus-tool?label=Uncompressed%20Size)
![The GZIP size of this reset](https://img.badgesize.io/https://unpkg.com/modern-css-reset-plus-tool?compression=gzip&label=GZIP%20Size)
![The Brotli size of this reset](https://img.badgesize.io/https://unpkg.com/modern-css-reset-plus-tool?compression=brotli&label=Brotli%20Size)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

A tiny little reset that you can use as the basis of your CSS projects. You can read a [breakdown of it here](https://hankchizljaw.com/wrote/a-modern-css-reset/).

### Changes

#### Resetting
* Extend elements removing default margin
* Delete a line under links
* Reset list marker position

#### Tools
* Warn when image source is not defined by show red element
* Add icons after links when using "icon_link" or "icon_link_blank" --FONTAWSOME IS REQUESTED--

## Installation

NPM:

```console
npm install --save-dev modern-css-reset-plus-tool
```

Yarn:

```console
yarn add --save-dev modern-css-reset-plus-tool
```

Unpkg CDN: 

```html
<link rel="stylesheet" href="https://unpkg.com/modern-css-reset-plus-tool/dist/reset.min.css" />
```

jsDelivr CDN: 

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/modern-css-reset-plus-tool/dist/reset.min.css" />
```

### Manual installation

First, let's clone this repository:

```console
git clone https://github.com/lmGroupJp/modern-css-reset-plus-tool.git
```

Then, go to `modern-css-reset-plus-tool` directory:

```console
cd modern-css-reset-plus-tool
```

And now, you can minify and move the main reset to the `dist` by running:

```console
npm run build
```

That's it! 🎉

## License

MIT
