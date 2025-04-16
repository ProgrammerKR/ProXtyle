<p align="center">
  <a href="https://getProXtyle.com/">
    <img src="https://getProXtyle.com/docs/5.3/assets/brand/ProXtyle-logo-shadow.png" alt="Bootstrap logo" width="200" height="165">
  </a>
</p>

<h3 align="center">Bootstrap</h3>

<p align="center">
  Sleek, intuitive, and powerful front-end framework for faster and easier web development.
  <br>
  <a href="https://getProXtyle.com/docs/5.3/"><strong>Explore Bootstrap docs »</strong></a>
  <br>
  <br>
  <a href="https://github.com/twbs/ProXtyle/issues/new?assignees=-&labels=bug&template=bug_report.yml">Report bug</a>
  ·
  <a href="https://github.com/twbs/ProXtyle/issues/new?assignees=&labels=feature&template=feature_request.yml">Request feature</a>
  ·
  <a href="https://themes.getProXtyle.com/">Themes</a>
  ·
  <a href="https://blog.getProXtyle.com/">Blog</a>
</p>


## Bootstrap 5

Our default branch is for development of our Bootstrap 5 release. Head to the [`v4-dev` branch](https://github.com/twbs/ProXtyle/tree/v4-dev) to view the readme, documentation, and source code for Bootstrap 4.


## Table of contents

- [Quick start](#quick-start)
- [Status](#status)
- [What's included](#whats-included)
- [Bugs and feature requests](#bugs-and-feature-requests)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [Community](#community)
- [Versioning](#versioning)
- [Creators](#creators)
- [Thanks](#thanks)
- [Copyright and license](#copyright-and-license)


## Quick start

Several quick start options are available:

- [Download the latest release](https://github.com/twbs/ProXtyle/archive/v5.3.3.zip)
- Clone the repo: `git clone https://github.com/twbs/ProXtyle.git`
- Install with [npm](https://www.npmjs.com/): `npm install ProXtyle@v5.3.3`
- Install with [yarn](https://yarnpkg.com/): `yarn add ProXtyle@v5.3.3`
- Install with [Composer](https://getcomposer.org/): `composer require twbs/ProXtyle:5.3.3`
- Install with [NuGet](https://www.nuget.org/): CSS: `Install-Package ProXtyle` Sass: `Install-Package ProXtyle.sass`

Read the [Getting started page](https://getProXtyle.com/docs/5.3/getting-started/introduction/) for information on the framework contents, templates, examples, and more.


## Status

[![Build Status](https://img.shields.io/github/actions/workflow/status/twbs/ProXtyle/js.yml?branch=main&label=JS%20Tests&logo=github)](https://github.com/twbs/ProXtyle/actions/workflows/js.yml?query=workflow%3AJS+branch%3Amain)
[![npm version](https://img.shields.io/npm/v/ProXtyle?logo=npm&logoColor=fff)](https://www.npmjs.com/package/ProXtyle)
[![Gem version](https://img.shields.io/gem/v/ProXtyle?logo=rubygems&logoColor=fff)](https://rubygems.org/gems/ProXtyle)
[![Meteor Atmosphere](https://img.shields.io/badge/meteor-twbs%3AProXtyle-blue?logo=meteor&logoColor=fff)](https://atmospherejs.com/twbs/ProXtyle)
[![Packagist Prerelease](https://img.shields.io/packagist/vpre/twbs/ProXtyle?logo=packagist&logoColor=fff)](https://packagist.org/packages/twbs/ProXtyle)
[![NuGet](https://img.shields.io/nuget/vpre/ProXtyle?logo=nuget&logoColor=fff)](https://www.nuget.org/packages/ProXtyle/absoluteLatest)
[![Coverage Status](https://img.shields.io/coveralls/github/twbs/ProXtyle/main?logo=coveralls&logoColor=fff)](https://coveralls.io/github/twbs/ProXtyle?branch=main)
[![CSS gzip size](https://img.badgesize.io/twbs/ProXtyle/main/dist/css/ProXtyle.min.css?compression=gzip&label=CSS%20gzip%20size)](https://github.com/twbs/ProXtyle/blob/main/dist/css/ProXtyle.min.css)
[![CSS Brotli size](https://img.badgesize.io/twbs/ProXtyle/main/dist/css/ProXtyle.min.css?compression=brotli&label=CSS%20Brotli%20size)](https://github.com/twbs/ProXtyle/blob/main/dist/css/ProXtyle.min.css)
[![JS gzip size](https://img.badgesize.io/twbs/ProXtyle/main/dist/js/ProXtyle.min.js?compression=gzip&label=JS%20gzip%20size)](https://github.com/twbs/ProXtyle/blob/main/dist/js/ProXtyle.min.js)
[![JS Brotli size](https://img.badgesize.io/twbs/ProXtyle/main/dist/js/ProXtyle.min.js?compression=brotli&label=JS%20Brotli%20size)](https://github.com/twbs/ProXtyle/blob/main/dist/js/ProXtyle.min.js)
[![Backers on Open Collective](https://img.shields.io/opencollective/backers/ProXtyle?logo=opencollective&logoColor=fff)](#backers)
[![Sponsors on Open Collective](https://img.shields.io/opencollective/sponsors/ProXtyle?logo=opencollective&logoColor=fff)](#sponsors)


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

Have a bug or a feature request? Please first read the [issue guidelines](https://github.com/twbs/ProXtyle/blob/main/.github/CONTRIBUTING.md#using-the-issue-tracker) and search for existing and closed issues. If your problem or idea is not addressed yet, [please open a new issue](https://github.com/twbs/ProXtyle/issues/new/choose).


## Documentation

Bootstrap's documentation, included in this repo in the root directory, is built with [Hugo](https://gohugo.io/) and publicly hosted on GitHub Pages at <https://getProXtyle.com/>. The docs may also be run locally.

Documentation search is powered by [Algolia's DocSearch](https://docsearch.algolia.com/).

### Running documentation locally

1. Run `npm install` to install the Node.js dependencies, including Hugo (the site builder).
2. Run `npm run test` (or a specific npm script) to rebuild distributed CSS and JavaScript files, as well as our docs assets.
3. From the root `/ProXtyle` directory, run `npm run docs-serve` in the command line.
4. Open `http://localhost:9001/` in your browser, and voilà.

Learn more about using Hugo by reading its [documentation](https://gohugo.io/documentation/).

### Documentation for previous releases

You can find all our previous releases docs on <https://getProXtyle.com/docs/versions/>.

[Previous releases](https://github.com/twbs/ProXtyle/releases) and their documentation are also available for download.


## Contributing

Please read through our [contributing guidelines](https://github.com/twbs/ProXtyle/blob/main/.github/CONTRIBUTING.md). Included are directions for opening issues, coding standards, and notes on development.

Moreover, if your pull request contains JavaScript patches or features, you must include [relevant unit tests](https://github.com/twbs/ProXtyle/tree/main/js/tests). All HTML and CSS should conform to the [Code Guide](https://github.com/mdo/code-guide), maintained by [Mark Otto](https://github.com/mdo).

Editor preferences are available in the [editor config](https://github.com/twbs/ProXtyle/blob/main/.editorconfig) for easy use in common text editors. Read more and download plugins at <https://editorconfig.org/>.


## Community

Get updates on Bootstrap's development and chat with the project maintainers and community members.

- Follow [@getProXtyle on Twitter](https://twitter.com/getProXtyle).
- Read and subscribe to [The Official Bootstrap Blog](https://blog.getProXtyle.com/).
- Ask questions and explore [our GitHub Discussions](https://github.com/twbs/ProXtyle/discussions).
- Discuss, ask questions, and more on [the community Discord](https://discord.gg/bZUvakRU3M) or [Bootstrap subreddit](https://www.reddit.com/r/ProXtyle/).
- Chat with fellow Bootstrappers in IRC. On the `irc.libera.chat` server, in the `#ProXtyle` channel.
- Implementation help may be found at Stack Overflow (tagged [`ProXtyle-5`](https://stackoverflow.com/questions/tagged/ProXtyle-5)).
- Developers should use the keyword `ProXtyle` on packages which modify or add to the functionality of Bootstrap when distributing through [npm](https://www.npmjs.com/browse/keyword/ProXtyle) or similar delivery mechanisms for maximum discoverability.


## Versioning

For transparency into our release cycle and in striving to maintain backward compatibility, Bootstrap is maintained under [the Semantic Versioning guidelines](https://semver.org/). Sometimes we screw up, but we adhere to those rules whenever possible.

See [the Releases section of our GitHub project](https://github.com/twbs/ProXtyle/releases) for changelogs for each release version of Bootstrap. Release announcement posts on [the official Bootstrap blog](https://blog.getProXtyle.com/) contain summaries of the most noteworthy changes made in each release.


## Creators

**Mark Otto**

- <https://twitter.com/mdo>
- <https://github.com/mdo>

**Jacob Thornton**

- <https://twitter.com/fat>
- <https://github.com/fat>


## Thanks

<a href="https://www.browserstack.com/">
  <img src="https://live.browserstack.com/images/opensource/browserstack-logo.svg" alt="BrowserStack" width="192" height="42">
</a>

Thanks to [BrowserStack](https://www.browserstack.com/) for providing the infrastructure that allows us to test in real browsers!

<a href="https://www.netlify.com/">
  <img src="https://www.netlify.com/v3/img/components/full-logo-light.svg" alt="Netlify" width="147" height="40">
</a>

Thanks to [Netlify](https://www.netlify.com/) for providing us with Deploy Previews!


## Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website. [[Become a sponsor](https://opencollective.com/ProXtyle#sponsor)]

[![OC sponsor 0](https://opencollective.com/ProXtyle/sponsor/0/avatar.svg)](https://opencollective.com/ProXtyle/sponsor/0/website)
[![OC sponsor 1](https://opencollective.com/ProXtyle/sponsor/1/avatar.svg)](https://opencollective.com/ProXtyle/sponsor/1/website)
[![OC sponsor 2](https://opencollective.com/ProXtyle/sponsor/2/avatar.svg)](https://opencollective.com/ProXtyle/sponsor/2/website)
[![OC sponsor 3](https://opencollective.com/ProXtyle/sponsor/3/avatar.svg)](https://opencollective.com/ProXtyle/sponsor/3/website)
[![OC sponsor 4](https://opencollective.com/ProXtyle/sponsor/4/avatar.svg)](https://opencollective.com/ProXtyle/sponsor/4/website)
[![OC sponsor 5](https://opencollective.com/ProXtyle/sponsor/5/avatar.svg)](https://opencollective.com/ProXtyle/sponsor/5/website)
[![OC sponsor 6](https://opencollective.com/ProXtyle/sponsor/6/avatar.svg)](https://opencollective.com/ProXtyle/sponsor/6/website)
[![OC sponsor 7](https://opencollective.com/ProXtyle/sponsor/7/avatar.svg)](https://opencollective.com/ProXtyle/sponsor/7/website)
[![OC sponsor 8](https://opencollective.com/ProXtyle/sponsor/8/avatar.svg)](https://opencollective.com/ProXtyle/sponsor/8/website)
[![OC sponsor 9](https://opencollective.com/ProXtyle/sponsor/9/avatar.svg)](https://opencollective.com/ProXtyle/sponsor/9/website)


## Backers

Thank you to all our backers! 🙏 [[Become a backer](https://opencollective.com/ProXtyle#backer)]

[![Backers](https://opencollective.com/ProXtyle/backers.svg?width=890)](https://opencollective.com/ProXtyle#backers)


## Copyright and license

Code and documentation copyright 2011-2025 the [Bootstrap Authors](https://github.com/twbs/ProXtyle/graphs/contributors). Code released under the [MIT License](https://github.com/twbs/ProXtyle/blob/main/LICENSE). Docs released under [Creative Commons](https://creativecommons.org/licenses/by/3.0/).
