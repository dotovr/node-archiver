## Changelog

**0.21.0** — <small>_December 21, 2015_</small> — [Diff](https://github.com/archiverjs/node-archiver/compare/0.20.0...0.21.0)

- core: add support for `entry.prefix`. update some internals to use it.
- core(glob): when setting `options.cwd` get an absolute path to the file and use the relative path for `entry.name`. #173
- core(bulk): soft-deprecation of `bulk` feature. will remain for time being with no new features or support.
- docs: initial jsdoc for core. http://archiverjs.com/docs
- tests: restructure a bit.

**0.20.0** — <small>_November 30, 2015_</small> — [Diff](https://github.com/archiverjs/node-archiver/compare/0.19.0...0.20.0)

- simpler path normalization as path.join was a bit restrictive. #162
- move utils to separate module to DRY.

[Release Archive](https://github.com/archiverjs/node-archiver/releases)