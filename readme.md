# vfile-reporter-pretty-too

**Pretty reporter for [`vfile`](https://github.com/vfile/vfile).** Visually the same as [`vfile-reporter-pretty`](https://github.com/vfile/vfile-reporter-pretty), but avoids a transformation to eslint messages which allows us to support info messages. In addition, it enables unicode output in Windows Terminal and ConEmu.

[![Build Status](https://travis-ci.com/vweevers/vfile-reporter-pretty-too.svg?branch=main)](https://travis-ci.com/github/vweevers/vfile-reporter-pretty-too)

![screenshot](screenshot.png)

## Highlights

- Pretty output.
- Sorts results by severity.
- Stylizes inline codeblocks in messages.
- Command-click a rule ID to open its docs.
- Command-click a header to reveal the first error in your editor. *(iTerm-only)*

## Install

```
npm install vfile-reporter-pretty-too
```

## Usage

### [Attend](https://github.com/vweevers/attend)

Nothing to do. It's the default reporter.

### [Unified](https://unifiedjs.com/)

```
remark . --report vfile-reporter-pretty-too
```

## Tips

In iTerm, <kbd>Command</kbd>-click the filename header to open the file in your editor.

In [terminals with support for hyperlinks](https://gist.github.com/egmontkob/eb114294efbcd5adb1944c9f3cb5feda#supporting-apps), <kbd>Command</kbd>-click the rule ID to open its docs.

## License

[MIT](LICENSE). Forked from [`eslint-formatter-pretty`](https://github.com/sindresorhus/eslint-formatter-pretty).
