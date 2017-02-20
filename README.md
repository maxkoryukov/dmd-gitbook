# dmd-gitbook

[![Tips](http://img.shields.io/gittip/maxkoryukov.png)](https://www.gittip.com/maxkoryukov/)

[![Build Status](https://travis-ci.org/maxkoryukov/dmd-gitbook.svg?branch=master)](https://travis-ci.org/maxkoryukov/dmd-gitbook)
<!--
[![Build status](https://ci.appveyor.com/api/projects/status/xxxxx?svg=true)](https://ci.appveyor.com/project/maxkoryukov/dmd-gitbook)
-->

[![npm version](https://img.shields.io/npm/v/dmd-gitbook.svg)](https://www.npmjs.com/package/dmd-gitbook)
[![npm downloads](https://img.shields.io/npm/dm/dmd-gitbook.svg)](https://www.npmjs.com/package/dmd-gitbook)

[![codebeat badge](https://codebeat.co/badges/fca005f3-4e1e-4f9a-978e-bf51aa941259)](https://codebeat.co/projects/github-com-maxkoryukov-dmd-gitbook)
[![bitHound Overall Score](https://www.bithound.io/github/maxkoryukov/dmd-gitbook/badges/score.svg)](https://www.bithound.io/github/maxkoryukov/dmd-gitbook)
[![bitHound Dependencies](https://www.bithound.io/github/maxkoryukov/dmd-gitbook/badges/dependencies.svg)](https://www.bithound.io/github/maxkoryukov/dmd-gitbook/master/dependencies/npm)
[![codecov](https://codecov.io/gh/maxkoryukov/dmd-gitbook/branch/master/graph/badge.svg)](https://codecov.io/gh/maxkoryukov/dmd-gitbook)
<!--
[![NSP Status](https://nodesecurity.io/orgs/maxkoryukov/projects/xxxxxx/badge)](https://nodesecurity.io/orgs/maxkoryukov/projects/xxxxxx)
 -->

Plugin for jsdoc2md to produce markdown suitable for gitbook.

To use a plug-in in your project, first install it as a devDependency:

```
$ npm install dmd-gitbook --save-dev
```

Then pass the plug-in name to `jsdoc2md` or `dmd`:

```
$ jsdoc2md --plugin dmd-gitbook lib/*.js
```

## License

Please, read the [`LICENSE`](LICENSE) file in the root of the repository (or downloaded package).
