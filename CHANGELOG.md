Changelog
=========

## [13.0.0](https://github.com/ckeditor/ckeditor5-mention/compare/v12.0.1...v13.0.0) (2019-08-26)

### Other changes

* The issue tracker for this package was moved to https://github.com/ckeditor/ckeditor5/issues. See [ckeditor/ckeditor5#1988](https://github.com/ckeditor/ckeditor5/issues/1988). ([2a33675](https://github.com/ckeditor/ckeditor5-mention/commit/2a33675))
* Use RegExp Unicode support feature detection form ckeditor5-utils. ([d47923e](https://github.com/ckeditor/ckeditor5-mention/commit/d47923e))

### BREAKING CHANGES

* The `mention/featuredetection` namespace is removed. Please use `env.features` from ckeditor5-utils instead.


## [12.0.1](https://github.com/ckeditor/ckeditor5-mention/compare/v12.0.0...v12.0.1) (2019-07-10)

Internal changes only (updated dependencies, documentation, etc.).


## [12.0.0](https://github.com/ckeditor/ckeditor5-mention/compare/v11.0.0...v12.0.0) (2019-07-04)

### Bug fixes

* It should be possible to type before a mention which is at the beginning of a block. Closes [#77](https://github.com/ckeditor/ckeditor5-mention/issues/77). ([946e762](https://github.com/ckeditor/ckeditor5-mention/commit/946e762))
* Mentions should work when different UTF character classes are used in the feed configuration. Closes [#38](https://github.com/ckeditor/ckeditor5-mention/issues/38). ([764f099](https://github.com/ckeditor/ckeditor5-mention/commit/764f099))
* Partial mentions should not be downcasted (e.g. not copied to clipboard). Closes [#24](https://github.com/ckeditor/ckeditor5-mention/issues/24). ([8956b1f](https://github.com/ckeditor/ckeditor5-mention/commit/8956b1f))

### Other changes

* Moved the `TextWatcher` util to `@ckeditor/ckeditor5-typing`. ([a644043](https://github.com/ckeditor/ckeditor5-mention/commit/a644043))

### BREAKING CHANGES

* The `TextWatcher` util was moved to `@ckeditor/ckeditor5-typing`.


## [11.0.0](https://github.com/ckeditor/ckeditor5-mention/compare/v10.0.0...v11.0.0) (2019-06-05)

### Bug fixes

* A mention can now be preceded by characters such as brackets, quotes, soft break, etc. Closes [#44](https://github.com/ckeditor/ckeditor5-mention/issues/44). ([86262d1](https://github.com/ckeditor/ckeditor5-mention/commit/86262d1))
* The mention plugin should not throw errors when another `ContextualBalloon` is already visible. Closes [#67](https://github.com/ckeditor/ckeditor5-mention/issues/67). ([de9ee71](https://github.com/ckeditor/ckeditor5-mention/commit/de9ee71))
* The mention panel should have precedence over all other panels. Closes [#74](https://github.com/ckeditor/ckeditor5-mention/issues/74). ([3e8a84c](https://github.com/ckeditor/ckeditor5-mention/commit/3e8a84c))
* The Mention UI will use `ContextualBalloon` plugin to display to prevent balloon collisions with other features. Closes [#27](https://github.com/ckeditor/ckeditor5-mention/issues/27). ([9ae7f30](https://github.com/ckeditor/ckeditor5-mention/commit/9ae7f30))

### Other changes

* Remove unknown stack option from `ContextualBalloon#add()` method call. ([b6a50cf](https://github.com/ckeditor/ckeditor5-mention/commit/b6a50cf))
* Use `Model#insertContent()` instead of `model.Writer#insertText()`. Closes [#69](https://github.com/ckeditor/ckeditor5-mention/issues/69). ([ee973bb](https://github.com/ckeditor/ckeditor5-mention/commit/ee973bb))

### BREAKING CHANGES

* The `MentionUI#panelView` property is removed. The mention feature now uses the `ContextualBalloon` plugin.


## [10.0.0](https://github.com/ckeditor/ckeditor5-mention/tree/v10.0.0) (2019-04-10)

The initial release.
