# Typst-Font-Awesome

![code size](https://img.shields.io/github/languages/code-size/ivaquero/typst-font-awesome.svg)
![repo size](https://img.shields.io/github/repo-size/ivaquero/typst-font-awesome.svg)

Offline [FontAwesome](https://fontawesome.com/) Binding for [Typst](https://typst.app/docs/).

## Usage

1. Download the fontawesome latest desktop version from [FontAwesome Official Site](https://github.com/FortAwesome/Font-Awesome/releases), unzip it and move the `svgs` folder into your workspace folder, and rename `svgs` as `fontawesome`.
2. Download the `font-awesome.typ` file, and place it into your workspace folder as well.
3. Import it into your Typst file, and use it with `fa()` function like the following example

```typst
#import "font-awesome": *

#fa("brand-amazon-pay")
```

You can also customize the icon like this

```typst
#import "font-awesome": *

#fa(
  "brand-amazon-pay",
  baseline: 0.25em,
  height: 1.0em,
  width: 1.5em)
```

Checkup [manual](https://github.com/ivaquero/typst-font-awesome/blob/main/manual.pdf) for more details.

![demo](demo.png)

## Changelog

### v0.2.0 (2025-03-03)

- update fontawesome to v6.7.2

### v0.1.0 (2023-08-28)

- update fontawesome to v6.5.1

### v0.0.4 (2023-08-28)

- change naming pattern

### v0.0.3 (2023-08-16)

- update fontawesome to v6.4.2
- change naming pattern

### v0.0.2 (2023-07-28)

- update structures
- enable customization

### v0.0.1 (2023-07-27)

- initial release
- add fontawesome v6.4.0
