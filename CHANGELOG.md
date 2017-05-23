Change History
==============

v0.1.0 (May 23, 2017)
---

### Breaking Changes

* No longer support "Slim" and "Haml"（prepared other packages [Slim](https://github.com/negibouze/html-webpack-slim-plugin), [Haml](https://github.com/negibouze/html-webpack-haml-plugin)）.

### Enhancements

* Supports manifest attribute.

### Bug Fixes

* Error inject when not have head tag [#3](https://github.com/negibouze/html-webpack-pug-plugin/issues/3)
* Breaks if there's word "body" anywhere in the content (not tag) [#7](https://github.com/negibouze/html-webpack-pug-plugin/issues/7)
