<p align="center">
  <a href="https://getproxtyle.com/">
    <img src="site/assets/ProXtyle-logo.png" alt="ProXtyle Logo" width="520" height="300">
  </a>
</p>

<h3 align="center">ProXtyle</h3>

<p align="center">
  A sleek, lightweight, and professional CSS framework for building modern, responsive websites with ease.
  <br>
  <a href="https://getproxtyle.com/docs/1.0/"><strong>Explore ProXtyle Docs »</strong></a>
  <br><br>
  <a href="https://github.com/ProgrammerKR/ProXtyle/issues/new?labels=bug">Report Bug</a>
  ·
  <a href="https://github.com/ProgrammerKR/ProXtyle/issues/new?labels=feature">Request Feature</a>
  ·
  <a href="https://themes.getproxtyle.com/">Themes</a>
  ·
  <a href="https://blog.getproxtyle.com/">Blog</a>
</p>

## ProXtyle

The default branch is used for active development of ProXtyle. Visit the [`proxtyle` branch](https://github.com/ProgrammerKR/ProXtyle/tree/proxtyle) to view the full source code, documentation, and related files.

## Table of contents

- [Quick start](#quick-start)
- [Status](#status)
- [What's included](#whats-included)
- [Bugs and feature requests](#bugs-and-feature-requests)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [Community](#community)
- [Versioning](#versioning)
- [Thanks](#thanks)
- [Copyright and license](#copyright-and-license)


## Quick start

Several quick start options are available:

- [Download the latest release](https://github.com/ProgrammerKR/ProXtyle/archive/v1.0.0.zip)
- Clone the repo: `git clone https://github.com/ProgrammerKR/ProXtyle.git`
- Install with [npm](https://www.npmjs.com/): `npm install ProXtyle@v1.0.2`
- Install with [yarn](https://yarnpkg.com/): `yarn add ProXtyle@v1.0.2`
- 
Read the [Getting started page](https://getproxtyle.com/docs/1.0.2/getting-started/introduction/) for information on the framework contents, templates, examples, and more.


## Status

[![Build Status](https://img.shields.io/github/actions/workflow/status/ProgrammerKR/ProXtyle/js.yml?branch=main&label=JS%20Tests&logo=github)](https://github.com/ProgrammerKR/ProXtyle/actions/workflows/js.yml?query=workflow%3AJS+branch%3Amain)  
[![npm version](https://img.shields.io/npm/v/ProXtyle?logo=npm&logoColor=fff)](https://www.npmjs.com/package/ProXtyle)  
[![Coverage Status](https://img.shields.io/coveralls/github/ProgrammerKR/ProXtyle/main?logo=coveralls&logoColor=fff)](https://coveralls.io/github/ProgrammerKR/ProXtyle?branch=main)  
[![CSS gzip size](https://img.badgesize.io/ProgrammerKR/ProXtyle/main/dist/css/ProXtyle.min.css?compression=gzip&label=CSS%20gzip%20size)](https://github.com/ProgrammerKR/ProXtyle/blob/main/dist/css/ProXtyle.min.css)  
[![JS gzip size](https://img.badgesize.io/ProgrammerKR/ProXtyle/main/dist/js/ProXtyle.min.js?compression=gzip&label=JS%20gzip%20size)](https://github.com/ProgrammerKR/ProXtyle/blob/main/dist/js/ProXtyle.min.js)

## What's included

Within the download you'll find the following directories and files, logically grouping common assets and providing both compiled and minified variations.

<details>
  <summary>Download contents</summary>

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
</details>

We provide compiled CSS and JS (`ProXtyle.*`), as well as compiled and minified CSS and JS (`ProXtyle.min.*`). [Source maps](https://web.dev/articles/source-maps) (`ProXtyle.*.map`) are available for use with certain browsers' developer tools. Bundled JS files (`ProXtyle.bundle.js` and minified `ProXtyle.bundle.min.js`) include [Popper](https://popper.js.org/docs/v2/).


## Bugs and feature requests

Have a bug or a feature request? Please first read the [issue guidelines](https://github.com/ProgrammerKR/ProXtyle/blob/main/.github/CONTRIBUTING.md#using-the-issue-tracker) and search for existing and closed issues. If your problem or idea is not addressed yet, [please open a new issue](https://github.com/ProgrammerKR/ProXtyle/issues/new/choose).

## Documentation

ProXtyle's official documentation will be available soon at [https://getproxtyle.com](https://getproxtyle.com).

The documentation site is currently under development and will include comprehensive guides, components, and usage examples.

**Note:** Until the full documentation is live, you can use all standard Bootstrap classes with ProXtyle, as it is currently compatible and built upon Bootstrap's core structure.

Refer to [Bootstrap Docs](https://getbootstrap.com/docs/) for class references.

Stay tuned!

### Documentation for previous releases

You can find all our previous releases docs on <https://getproxtyle.com/docs/versions/>.

[Previous releases](https://github.com/ProgrammerKR/ProXtyle/releases) and their documentation are also available for download.


## Contributing

Please read through our [contributing guidelines](https://github.com/ProgrammerKR/ProXtyle/blob/main/.github/CONTRIBUTING.md). Included are directions for opening issues, coding standards, and notes on development.

Moreover, if your pull request contains JavaScript patches or features, you must include [relevant unit tests](https://github.com/ProgrammerKR/ProXtyle/tree/main/js/tests). All HTML and CSS should conform to the [Code Guide](https://github.com/mdo/code-guide), maintained by [Mark Otto](https://github.com/mdo).

Editor preferences are available in the [editor config](https://github.com/ProgrammerKR/ProXtyle/blob/main/.editorconfig) for easy use in common text editors. Read more and download plugins at <https://editorconfig.org/>.


## Community

Get updates on Bootstrap's development and chat with the project maintainers and community members.

- Follow [@ProgrammerKR on Twitter](https://twitter.com/@Prog_KaniahkRaj).
- Ask questions and explore [our GitHub Discussions](https://github.com/ProgrammerKR/ProXtyle/discussions).
- Discuss, ask questions, and more on [the community Discord](https://discord.gg/bZUvakRU3M)
- Implementation help may be found at Stack Overflow (tagged [`ProXtyle`](https://stackoverflow.com/questions/tagged/ProXtyle)).
- Developers should use the keyword `ProXtyle` on packages which modify or add to the functionality of Bootstrap when distributing through [npm](https://www.npmjs.com/browse/keyword/ProXtyle) or similar delivery mechanisms for maximum discoverability.


## Versioning

For transparency into our release cycle and in striving to maintain backward compatibility, Bootstrap is maintained under [the Semantic Versioning guidelines](https://semver.org/). Sometimes we screw up, but we adhere to those rules whenever possible.

See [the Releases section of our GitHub project](https://github.com/ProgrammerKR/ProXtyle/releases) for changelogs for each release version of Bootstrap. Release announcement posts on [the official ProXtyle blog](https://blog.getProXtyle.com/) contain summaries of the most noteworthy changes made in each release.

## Thanks

<a href="https://www.netlify.com/">
  <img src="https://www.netlify.com/v3/img/components/full-logo-light.svg" alt="Netlify" width="147" height="40">
</a>

Thanks to [Netlify](https://www.netlify.com/) for providing us with Deploy Previews!

## Copyright and license

Code and documentation copyright 2025 the [ProXtyle Authors](https://github.com/ProgrammerKR/ProXtyle/graphs/contributors). Code released under the [MIT License](https://github.com/ProgrammerKR/ProXtyle/blob/main/LICENSE). Docs released under [Creative Commons](https://creativecommons.org/licenses/by/3.0/).
