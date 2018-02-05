# Sitemap
**GitHub Organization: <https://github.com/elementnet>**

**Scratch Forum Topic: <https://scratch.mit.edu/discuss/topic/286069>**

## [Server](https://elementnet.herokuapp.com)
[![Gitter](https://img.shields.io/badge/gitter-join_chat-1dce73.svg?logo=gitter-white)](https://gitter.im/elementnet/main)

[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://elementnet.js.org/LICENSE.txt)
[![GitHub release](https://img.shields.io/github/release/elementnet/e.svg)](https://github.com/elementnet/elementnet-www/releases)

[![Code Maintainability](https://img.shields.io/codeclimate/maintainability/elementnet/e.svg)](https://codeclimate.com/github/elementnet/elementnet-www/issues?status%5B%5D=open&status%5B%5D=confirmed)
[![Build Status](https://travis-ci.org/elementnet/elementnet-www.svg?branch=develop)](https://travis-ci.org/elementnet/elementnet-www)

[![Waffle.io - Columns and their card count](https://badge.waffle.io/elementnet/elementnet-www.png?columns=Next,In+Progress,Review)](https://waffle.io/elementnet/elementnet-www?utm_source=badge)

**Nightly builds: <https://elementnet-dev.herokuapp.com>**

## [Editor](https://elementnet.js.org/elementnet-editor)
[![Gitter](https://img.shields.io/badge/gitter-join_chat-1dce73.svg?logo=gitter-white)](https://gitter.im/elementnet/elementnet-editor)
[![Build Status](https://travis-ci.org/elementnet/elementnet-editor.svg?branch=master)](https://travis-ci.org/elementnet/elementnet-editor)

[![Waffle.io - Columns and their card count](https://badge.waffle.io/elementnet/elementnet-editor.svg?columns=Next,In+Progress,Review)](https://waffle.io/elementnet/elementnet-editor)

### Running Locally

**Note: uglify-js, uglifycss, and browserify need to be installed globally.** (`npm i -g <packagename>`)

```sh
git clone --recursive git@github.com:elementnet/elementnet-editor
cd elementnet-editor
npm install && npm start
```

Then, navigate to <http://localhost:8080/>.

If it's already cloned, just run `npm run rebuild && npm start`.
