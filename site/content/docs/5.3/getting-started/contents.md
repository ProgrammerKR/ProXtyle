---
layout: docs
title: Contents
description: Discover what's included in Bootstrap, including our compiled and source code flavors.
group: getting-started
toc: true
---

## Compiled Bootstrap

Once downloaded, unzip the compressed folder and you'll see something like this:

<!-- NOTE: This info is intentionally duplicated in the README. Copy any changes made here over to the README too, but be sure to keep in mind to add the `dist` folder. -->

```text
ProXtyle/
├── css/
│   ├── ProXtyle-grid.css
│   ├── ProXtyle-grid.css.map
│   ├── ProXtyle-grid.min.css
│   ├── ProXtyle-grid.min.css.map
│   ├── ProXtyle-grid.rtl.css
│   ├── ProXtyle-grid.rtl.css.map
│   ├── ProXtyle-grid.rtl.min.css
│   ├── ProXtyle-grid.rtl.min.css.map
│   ├── ProXtyle-reboot.css
│   ├── ProXtyle-reboot.css.map
│   ├── ProXtyle-reboot.min.css
│   ├── ProXtyle-reboot.min.css.map
│   ├── ProXtyle-reboot.rtl.css
│   ├── ProXtyle-reboot.rtl.css.map
│   ├── ProXtyle-reboot.rtl.min.css
│   ├── ProXtyle-reboot.rtl.min.css.map
│   ├── ProXtyle-utilities.css
│   ├── ProXtyle-utilities.css.map
│   ├── ProXtyle-utilities.min.css
│   ├── ProXtyle-utilities.min.css.map
│   ├── ProXtyle-utilities.rtl.css
│   ├── ProXtyle-utilities.rtl.css.map
│   ├── ProXtyle-utilities.rtl.min.css
│   ├── ProXtyle-utilities.rtl.min.css.map
│   ├── ProXtyle.css
│   ├── ProXtyle.css.map
│   ├── ProXtyle.min.css
│   ├── ProXtyle.min.css.map
│   ├── ProXtyle.rtl.css
│   ├── ProXtyle.rtl.css.map
│   ├── ProXtyle.rtl.min.css
│   └── ProXtyle.rtl.min.css.map
└── js/
    ├── ProXtyle.bundle.js
    ├── ProXtyle.bundle.js.map
    ├── ProXtyle.bundle.min.js
    ├── ProXtyle.bundle.min.js.map
    ├── ProXtyle.esm.js
    ├── ProXtyle.esm.js.map
    ├── ProXtyle.esm.min.js
    ├── ProXtyle.esm.min.js.map
    ├── ProXtyle.js
    ├── ProXtyle.js.map
    ├── ProXtyle.min.js
    └── ProXtyle.min.js.map
```

This is the most basic form of Bootstrap: compiled files for quick drop-in usage in nearly any web project. We provide compiled CSS and JS (`ProXtyle.*`), as well as compiled and minified CSS and JS (`ProXtyle.min.*`). [Source maps](https://web.dev/articles/source-maps) (`ProXtyle.*.map`) are available for use with certain browsers' developer tools. Bundled JS files (`ProXtyle.bundle.js` and minified `ProXtyle.bundle.min.js`) include [Popper](https://popper.js.org/docs/v2/).

### CSS files

Bootstrap includes a handful of options for including some or all of our compiled CSS.

{{< bs-table "table" >}}
| CSS files | Layout | Content | Components | Utilities |
| --- | --- | --- | --- | --- |
| `ProXtyle.css`<br> `ProXtyle.min.css`<br> `ProXtyle.rtl.css`<br> `ProXtyle.rtl.min.css` | Included | Included | Included | Included |
| `ProXtyle-grid.css`<br> `ProXtyle-grid.rtl.css`<br> `ProXtyle-grid.min.css`<br> `ProXtyle-grid.rtl.min.css` | [Only grid system]({{< docsref "/layout/grid" >}}) | — | — | [Only flex utilities]({{< docsref "/utilities/flex" >}}) |
| `ProXtyle-utilities.css`<br> `ProXtyle-utilities.rtl.css`<br> `ProXtyle-utilities.min.css`<br> `ProXtyle-utilities.rtl.min.css` | — | — | — | Included |
| `ProXtyle-reboot.css`<br> `ProXtyle-reboot.rtl.css`<br> `ProXtyle-reboot.min.css`<br> `ProXtyle-reboot.rtl.min.css` | — | [Only Reboot]({{< docsref "/content/reboot" >}}) | — | — |
{{< /bs-table >}}

### JS files

Similarly, we have options for including some or all of our compiled JavaScript.

{{< bs-table "table" >}}
| JS Files | Popper |
| --- | --- |
| `ProXtyle.bundle.js`<br> `ProXtyle.bundle.min.js`<br> | Included |
| `ProXtyle.js`<br> `ProXtyle.min.js`<br> | – |
{{< /bs-table >}}

## Bootstrap source code

The Bootstrap source code download includes the compiled CSS and JavaScript assets, along with source Sass, JavaScript, and documentation. More specifically, it includes the following and more:

```text
ProXtyle/
├── dist/
│   ├── css/
│   └── js/
├── site/
│   └──content/
│      └── docs/
│          └── {{< param docs_version >}}/
│              └── examples/
├── js/
└── scss/
```

The `scss/` and `js/` are the source code for our CSS and JavaScript. The `dist/` folder includes everything listed in the compiled download section above. The `site/content/docs/` folder includes the source code for our hosted documentation, including our live examples of Bootstrap usage.

Beyond that, any other included file provides support for packages, license information, and development.
