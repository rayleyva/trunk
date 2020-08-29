changelog
=========

## Unreleased
### changed
- `trunk serve` now takes the `--open` option to control whether or not a browser tab will be opened. Thanks @MartinKavik for the report.
- The `trunk serve` listener info has been slightly updated. It continues to function as in previous releases. Thanks @MartinKavik for the report.

## 0.1.3
### fixed
- Closed [#15](https://github.com/thedodd/trunk/issues/15): ensure cargo package name is processed as cargo itself processes package names (`s/-/_/`).
- Closed [#16](https://github.com/thedodd/trunk/issues/16): default to `index.html` as the default target for all CLI commands which expect a target. This matches the expectation of Seed & Yew.

Thanks @MartinKavik for reporting these items.

## 0.1.2
### changed
- Swap our `grass` for `sass-rs`.
- Compress SASS/SCSS output when building in `--release` mode.

## 0.1.1
### fixed
- Fix an issue with the watch system which was breaking builds on Windows.

## 0.1.0
- Initialize release. See the [release notes on Github](https://github.com/thedodd/trunk/releases/tag/v0.1.0) for more info.