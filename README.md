# vfile-reporter-pretty-too

**Pretty reporter for [`vfile`](https://github.com/vfile/vfile).** Visually the same as [`vfile-reporter-pretty`](https://github.com/vfile/vfile-reporter-pretty), but avoids a transformation to eslint messages which allows us to support info messages. In addition, it enables unicode output in Windows Terminal and ConEmu.

[![npm status](http://img.shields.io/npm/v/vfile-reporter-pretty-too.svg)](https://www.npmjs.org/package/vfile-reporter-pretty-too)
[![node](https://img.shields.io/node/v/vfile-reporter-pretty-too.svg)](https://www.npmjs.org/package/vfile-reporter-pretty-too)
[![Build Status](https://travis-ci.com/vweevers/vfile-reporter-pretty-too.svg?branch=main)](https://travis-ci.com/github/vweevers/vfile-reporter-pretty-too)
[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

![screenshot](screenshot.png)

## Highlights

- Sorts results by severity.
- Stylizes inline codeblocks in messages.
- In [terminals that support hyperlinks](https://gist.github.com/egmontkob/eb114294efbcd5adb1944c9f3cb5feda#supporting-apps), click a rule to open its docs. This works for [ESLint](https://eslint.org/), [remark](https://remark.js.org/) and [Attend](https://github.com/vweevers/attend) rules.
- In iTerm and ConEmu, click a filename to open it in your editor.

## Install

```
npm install vfile-reporter-pretty-too
```

## Usage

### [Attend](https://github.com/vweevers/attend)

Nothing to do. It's the default reporter.

### [Unified](https://unifiedjs.com/)

```
remark --report vfile-reporter-pretty-too .
```

### [Hallmark](https://github.com/vweevers/hallmark)

```
hallmark --report vfile-reporter-pretty-too
```

## License

[MIT](LICENSE). Forked from [`eslint-formatter-pretty`](https://github.com/sindresorhus/eslint-formatter-pretty).
