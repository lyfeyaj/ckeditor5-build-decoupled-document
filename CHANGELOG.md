Changelog
=========

## [11.0.1](https://github.com/ckeditor/ckeditor5-build-decoupled-document/compare/v11.0.0...v11.0.1) (2018-07-18)

Internal changes only (updated dependencies, documentation, etc.).


## [11.0.0](https://github.com/ckeditor/ckeditor5-build-decoupled-document/compare/v10.1.0...v11.0.0) (2018-07-18)

### Release notes

This is a major releases that introduces many smaller features, dozens of bug fixes and a couple of infrastructure changes (an upgrade to `webpack@4`, simplified structure of the build repository). Additionally, the `DecoupledEditor#element` property was renamed to `DecoupledEditor#sourceElement`.

If you maintain a [custom build of CKEditor 5](https://docs.ckeditor.com/ckeditor5/latest/builds/guides/development/custom-builds.html) or [integrate CKEditor 5 from source](https://docs.ckeditor.com/ckeditor5/latest/builds/guides/integration/advanced-setup.html#scenario-2-building-from-source), we recommend reading the [migration guide](https://github.com/ckeditor/ckeditor5/issues/1136).

Blog post is coming soon...

### Dependencies

Major releases (contain breaking changes):

* [@ckeditor/ckeditor5-core](https://www.npmjs.com/package/@ckeditor/ckeditor5-core): v10.1.0 => [v11.0.0](https://github.com/ckeditor/ckeditor5-core/releases/tag/v11.0.0)
* [@ckeditor/ckeditor5-editor-decoupled](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-decoupled): v10.0.2 => [v11.0.0](https://github.com/ckeditor/ckeditor5-editor-decoupled/releases/tag/v11.0.0)
* [@ckeditor/ckeditor5-theme-lark](https://www.npmjs.com/package/@ckeditor/ckeditor5-theme-lark): v10.1.0 => [v11.0.0](https://github.com/ckeditor/ckeditor5-theme-lark/releases/tag/v11.0.0)
* [@ckeditor/ckeditor5-typing](https://www.npmjs.com/package/@ckeditor/ckeditor5-typing): v10.0.1 => [v11.0.0](https://github.com/ckeditor/ckeditor5-typing/releases/tag/v11.0.0)
* [@ckeditor/ckeditor5-ui](https://www.npmjs.com/package/@ckeditor/ckeditor5-ui): v10.1.0 => [v11.0.0](https://github.com/ckeditor/ckeditor5-ui/releases/tag/v11.0.0)

Minor releases:

* [@ckeditor/ckeditor5-engine](https://www.npmjs.com/package/@ckeditor/ckeditor5-engine): v10.1.0 => [v10.2.0](https://github.com/ckeditor/ckeditor5-engine/releases/tag/v10.2.0)
* [@ckeditor/ckeditor5-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-image): v10.1.0 => [v10.2.0](https://github.com/ckeditor/ckeditor5-image/releases/tag/v10.2.0)
* [@ckeditor/ckeditor5-table](https://www.npmjs.com/package/@ckeditor/ckeditor5-table): v10.0.0 => [v10.1.0](https://github.com/ckeditor/ckeditor5-table/releases/tag/v10.1.0)
* [@ckeditor/ckeditor5-utils](https://www.npmjs.com/package/@ckeditor/ckeditor5-utils): v10.1.0 => [v10.2.0](https://github.com/ckeditor/ckeditor5-utils/releases/tag/v10.2.0)
* [@ckeditor/ckeditor5-widget](https://www.npmjs.com/package/@ckeditor/ckeditor5-widget): v10.1.0 => [v10.2.0](https://github.com/ckeditor/ckeditor5-widget/releases/tag/v10.2.0)

Patch releases (bug fixes, internal changes):

* [@ckeditor/ckeditor5-adapter-ckfinder](https://www.npmjs.com/package/@ckeditor/ckeditor5-adapter-ckfinder): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-adapter-ckfinder/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-alignment](https://www.npmjs.com/package/@ckeditor/ckeditor5-alignment): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-alignment/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-autoformat](https://www.npmjs.com/package/@ckeditor/ckeditor5-autoformat): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-autoformat/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-basic-styles](https://www.npmjs.com/package/@ckeditor/ckeditor5-basic-styles): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-basic-styles/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-block-quote](https://www.npmjs.com/package/@ckeditor/ckeditor5-block-quote): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-block-quote/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-clipboard](https://www.npmjs.com/package/@ckeditor/ckeditor5-clipboard): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-clipboard/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-cloud-services](https://www.npmjs.com/package/@ckeditor/ckeditor5-cloud-services): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-cloud-services/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-easy-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-easy-image): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-easy-image/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-enter](https://www.npmjs.com/package/@ckeditor/ckeditor5-enter): v10.1.0 => [v10.1.1](https://github.com/ckeditor/ckeditor5-enter/releases/tag/v10.1.1)
* [@ckeditor/ckeditor5-essentials](https://www.npmjs.com/package/@ckeditor/ckeditor5-essentials): v10.1.0 => [v10.1.1](https://github.com/ckeditor/ckeditor5-essentials/releases/tag/v10.1.1)
* [@ckeditor/ckeditor5-font](https://www.npmjs.com/package/@ckeditor/ckeditor5-font): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-font/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-heading](https://www.npmjs.com/package/@ckeditor/ckeditor5-heading): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-heading/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-highlight](https://www.npmjs.com/package/@ckeditor/ckeditor5-highlight): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-highlight/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-link](https://www.npmjs.com/package/@ckeditor/ckeditor5-link): v10.0.2 => [v10.0.3](https://github.com/ckeditor/ckeditor5-link/releases/tag/v10.0.3)
* [@ckeditor/ckeditor5-list](https://www.npmjs.com/package/@ckeditor/ckeditor5-list): v11.0.0 => [v11.0.1](https://github.com/ckeditor/ckeditor5-list/releases/tag/v11.0.1)
* [@ckeditor/ckeditor5-paragraph](https://www.npmjs.com/package/@ckeditor/ckeditor5-paragraph): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-paragraph/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-undo](https://www.npmjs.com/package/@ckeditor/ckeditor5-undo): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-undo/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-upload](https://www.npmjs.com/package/@ckeditor/ckeditor5-upload): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-upload/releases/tag/v10.0.2)

### Other changes

* Changed the structure of the build repository. Closes [ckeditor/ckeditor5#1038](https://github.com/ckeditor/ckeditor5/issues/1038). ([cd72eca](https://github.com/ckeditor/ckeditor5-build-decoupled-document/commit/cd72eca))
* Updated `webpack` to version 4 (applies to custom builds only). ([dfdde57](https://github.com/ckeditor/ckeditor5-build-decoupled-document/commit/dfdde57))

### BREAKING CHANGES

If you maintain a custom build, we recommend reading the [migration guide](https://github.com/ckeditor/ckeditor5/issues/1136). Closes [ckeditor/ckeditor5#1038](https://github.com/ckeditor/ckeditor5/issues/1038).

* CKEditor 5 environment was updated to use `webpack@4`. `webpack@4` introduced major changes in its configuration and plugin system. CKEditor 5 tools and build configuration were updated to work with `webpack@4` and will not work with `webpack@3`.
* The structure of the build repository was changed. The `build-config.js` file was removed and the build configuration is now kept only in the `src/ckeditor.js` file.


## [10.1.0](https://github.com/ckeditor/ckeditor5-build-decoupled-document/compare/v10.0.1...v10.1.0) (2018-06-21)

This is a minor release that introduces many bug fixes and new features. Most notable ones are the table plugin and support for inserting soft breaks with <kbd>Shift</kbd>+<kbd>Enter</kbd>.

You can read more in the [blog post](https://ckeditor.com/blog/CKEditor-5-v10.1.0-released/).

### Dependencies

New packages:

* [@ckeditor/ckeditor5-table](https://www.npmjs.com/package/@ckeditor/ckeditor5-table): [v10.0.0](https://github.com/ckeditor/ckeditor5-table/releases/tag/v10.0.0)

Major releases (contain breaking changes):

* [@ckeditor/ckeditor5-list](https://www.npmjs.com/package/@ckeditor/ckeditor5-list): v10.0.0 => [v11.0.0](https://github.com/ckeditor/ckeditor5-list/releases/tag/v11.0.0)

Minor releases:

* [@ckeditor/ckeditor5-core](https://www.npmjs.com/package/@ckeditor/ckeditor5-core): v10.0.0 => [v10.1.0](https://github.com/ckeditor/ckeditor5-core/releases/tag/v10.1.0)
* [@ckeditor/ckeditor5-engine](https://www.npmjs.com/package/@ckeditor/ckeditor5-engine): v10.0.0 => [v10.1.0](https://github.com/ckeditor/ckeditor5-engine/releases/tag/v10.1.0)
* [@ckeditor/ckeditor5-enter](https://www.npmjs.com/package/@ckeditor/ckeditor5-enter): v10.0.0 => [v10.1.0](https://github.com/ckeditor/ckeditor5-enter/releases/tag/v10.1.0)
* [@ckeditor/ckeditor5-essentials](https://www.npmjs.com/package/@ckeditor/ckeditor5-essentials): v10.0.0 => [v10.1.0](https://github.com/ckeditor/ckeditor5-essentials/releases/tag/v10.1.0)
* [@ckeditor/ckeditor5-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-image): v10.0.0 => [v10.1.0](https://github.com/ckeditor/ckeditor5-image/releases/tag/v10.1.0)
* [@ckeditor/ckeditor5-theme-lark](https://www.npmjs.com/package/@ckeditor/ckeditor5-theme-lark): v10.0.0 => [v10.1.0](https://github.com/ckeditor/ckeditor5-theme-lark/releases/tag/v10.1.0)
* [@ckeditor/ckeditor5-ui](https://www.npmjs.com/package/@ckeditor/ckeditor5-ui): v10.0.0 => [v10.1.0](https://github.com/ckeditor/ckeditor5-ui/releases/tag/v10.1.0)
* [@ckeditor/ckeditor5-upload](https://www.npmjs.com/package/@ckeditor/ckeditor5-upload): v10.0.0 => [v10.1.0](https://github.com/ckeditor/ckeditor5-upload/releases/tag/v10.1.0)
* [@ckeditor/ckeditor5-utils](https://www.npmjs.com/package/@ckeditor/ckeditor5-utils): v10.0.0 => [v10.1.0](https://github.com/ckeditor/ckeditor5-utils/releases/tag/v10.1.0)
* [@ckeditor/ckeditor5-widget](https://www.npmjs.com/package/@ckeditor/ckeditor5-widget): v10.0.0 => [v10.1.0](https://github.com/ckeditor/ckeditor5-widget/releases/tag/v10.1.0)

Patch releases (bug fixes, internal changes):

* [@ckeditor/ckeditor5-adapter-ckfinder](https://www.npmjs.com/package/@ckeditor/ckeditor5-adapter-ckfinder): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-adapter-ckfinder/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-alignment](https://www.npmjs.com/package/@ckeditor/ckeditor5-alignment): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-alignment/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-autoformat](https://www.npmjs.com/package/@ckeditor/ckeditor5-autoformat): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-autoformat/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-basic-styles](https://www.npmjs.com/package/@ckeditor/ckeditor5-basic-styles): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-basic-styles/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-block-quote](https://www.npmjs.com/package/@ckeditor/ckeditor5-block-quote): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-block-quote/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-clipboard](https://www.npmjs.com/package/@ckeditor/ckeditor5-clipboard): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-clipboard/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-cloud-services](https://www.npmjs.com/package/@ckeditor/ckeditor5-cloud-services): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-cloud-services/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-easy-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-easy-image): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-easy-image/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-editor-decoupled](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-decoupled): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-editor-decoupled/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-font](https://www.npmjs.com/package/@ckeditor/ckeditor5-font): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-font/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-heading](https://www.npmjs.com/package/@ckeditor/ckeditor5-heading): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-heading/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-highlight](https://www.npmjs.com/package/@ckeditor/ckeditor5-highlight): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-highlight/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-link](https://www.npmjs.com/package/@ckeditor/ckeditor5-link): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-link/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-paragraph](https://www.npmjs.com/package/@ckeditor/ckeditor5-paragraph): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-paragraph/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-typing](https://www.npmjs.com/package/@ckeditor/ckeditor5-typing): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-typing/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-undo](https://www.npmjs.com/package/@ckeditor/ckeditor5-undo): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-undo/releases/tag/v10.0.1)

### Features

Besides new features introduced by the dependencies, this version also introduces the following features:

* Added the table feature to the build. Closes [#12](https://github.com/ckeditor/ckeditor5-build-decoupled-document/issues/12). ([58bfd46](https://github.com/ckeditor/ckeditor5-build-decoupled-document/commit/58bfd46))


## [10.0.1](https://github.com/ckeditor/ckeditor5-build-decoupled-document/compare/v10.0.0...v10.0.1) (2018-05-22)

### Dependencies

Patch releases (bug fixes, internal changes):

* [@ckeditor/ckeditor5-editor-decoupled](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-decoupled): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-editor-decoupled/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-link](https://www.npmjs.com/package/@ckeditor/ckeditor5-link): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-link/releases/tag/v10.0.1)


## [10.0.0](https://github.com/ckeditor/ckeditor5-build-decoupled-document/compare/v1.0.0-beta.4...v10.0.0) (2018-04-25)

### Dependencies

Major releases (contain breaking changes):

* [@ckeditor/ckeditor5-adapter-ckfinder](https://www.npmjs.com/package/@ckeditor/ckeditor5-adapter-ckfinder): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-adapter-ckfinder/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-alignment](https://www.npmjs.com/package/@ckeditor/ckeditor5-alignment): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-alignment/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-autoformat](https://www.npmjs.com/package/@ckeditor/ckeditor5-autoformat): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-autoformat/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-basic-styles](https://www.npmjs.com/package/@ckeditor/ckeditor5-basic-styles): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-basic-styles/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-block-quote](https://www.npmjs.com/package/@ckeditor/ckeditor5-block-quote): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-block-quote/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-clipboard](https://www.npmjs.com/package/@ckeditor/ckeditor5-clipboard): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-clipboard/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-cloud-services](https://www.npmjs.com/package/@ckeditor/ckeditor5-cloud-services): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-cloud-services/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-core](https://www.npmjs.com/package/@ckeditor/ckeditor5-core): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-core/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-easy-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-easy-image): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-easy-image/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-editor-decoupled](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-decoupled): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-editor-decoupled/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-engine](https://www.npmjs.com/package/@ckeditor/ckeditor5-engine): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-engine/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-enter](https://www.npmjs.com/package/@ckeditor/ckeditor5-enter): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-enter/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-essentials](https://www.npmjs.com/package/@ckeditor/ckeditor5-essentials): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-essentials/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-font](https://www.npmjs.com/package/@ckeditor/ckeditor5-font): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-font/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-heading](https://www.npmjs.com/package/@ckeditor/ckeditor5-heading): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-heading/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-highlight](https://www.npmjs.com/package/@ckeditor/ckeditor5-highlight): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-highlight/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-image): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-image/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-link](https://www.npmjs.com/package/@ckeditor/ckeditor5-link): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-link/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-list](https://www.npmjs.com/package/@ckeditor/ckeditor5-list): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-list/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-paragraph](https://www.npmjs.com/package/@ckeditor/ckeditor5-paragraph): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-paragraph/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-theme-lark](https://www.npmjs.com/package/@ckeditor/ckeditor5-theme-lark): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-theme-lark/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-typing](https://www.npmjs.com/package/@ckeditor/ckeditor5-typing): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-typing/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-ui](https://www.npmjs.com/package/@ckeditor/ckeditor5-ui): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-ui/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-undo](https://www.npmjs.com/package/@ckeditor/ckeditor5-undo): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-undo/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-upload](https://www.npmjs.com/package/@ckeditor/ckeditor5-upload): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-upload/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-utils](https://www.npmjs.com/package/@ckeditor/ckeditor5-utils): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-utils/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-widget](https://www.npmjs.com/package/@ckeditor/ckeditor5-widget): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-widget/releases/tag/v10.0.0)

### Other changes

* Changed the license to GPL2+ only. See [ckeditor/ckeditor5#991](https://github.com/ckeditor/ckeditor5/issues/991). ([f5147e8](https://github.com/ckeditor/ckeditor5-build-decoupled-document/commit/f5147e8))

### BREAKING CHANGES

* The license under which CKEditor 5 is released has been changed from a triple GPL, LGPL and MPL license to a GPL2+ only. See [ckeditor/ckeditor5#991](https://github.com/ckeditor/ckeditor5/issues/991) for more information.


## [1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-build-decoupled-document/compare/v1.0.0-beta.3...v1.0.0-beta.4) (2018-04-19)

### Dependencies

Major releases (contain breaking changes):

* [@ckeditor/ckeditor5-adapter-ckfinder](https://www.npmjs.com/package/@ckeditor/ckeditor5-adapter-ckfinder): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-adapter-ckfinder/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-alignment](https://www.npmjs.com/package/@ckeditor/ckeditor5-alignment): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-alignment/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-autoformat](https://www.npmjs.com/package/@ckeditor/ckeditor5-autoformat): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-autoformat/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-basic-styles](https://www.npmjs.com/package/@ckeditor/ckeditor5-basic-styles): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-basic-styles/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-block-quote](https://www.npmjs.com/package/@ckeditor/ckeditor5-block-quote): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-block-quote/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-clipboard](https://www.npmjs.com/package/@ckeditor/ckeditor5-clipboard): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-clipboard/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-cloud-services](https://www.npmjs.com/package/@ckeditor/ckeditor5-cloud-services): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-cloud-services/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-core](https://www.npmjs.com/package/@ckeditor/ckeditor5-core): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-core/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-easy-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-easy-image): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-easy-image/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-editor-decoupled](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-decoupled): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-editor-decoupled/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-engine](https://www.npmjs.com/package/@ckeditor/ckeditor5-engine): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-engine/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-enter](https://www.npmjs.com/package/@ckeditor/ckeditor5-enter): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-enter/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-essentials](https://www.npmjs.com/package/@ckeditor/ckeditor5-essentials): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-essentials/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-font](https://www.npmjs.com/package/@ckeditor/ckeditor5-font): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-font/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-heading](https://www.npmjs.com/package/@ckeditor/ckeditor5-heading): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-heading/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-highlight](https://www.npmjs.com/package/@ckeditor/ckeditor5-highlight): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-highlight/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-image): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-image/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-link](https://www.npmjs.com/package/@ckeditor/ckeditor5-link): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-link/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-list](https://www.npmjs.com/package/@ckeditor/ckeditor5-list): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-list/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-paragraph](https://www.npmjs.com/package/@ckeditor/ckeditor5-paragraph): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-paragraph/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-theme-lark](https://www.npmjs.com/package/@ckeditor/ckeditor5-theme-lark): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-theme-lark/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-typing](https://www.npmjs.com/package/@ckeditor/ckeditor5-typing): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-typing/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-ui](https://www.npmjs.com/package/@ckeditor/ckeditor5-ui): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-ui/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-undo](https://www.npmjs.com/package/@ckeditor/ckeditor5-undo): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-undo/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-upload](https://www.npmjs.com/package/@ckeditor/ckeditor5-upload): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-upload/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-utils](https://www.npmjs.com/package/@ckeditor/ckeditor5-utils): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-utils/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-widget](https://www.npmjs.com/package/@ckeditor/ckeditor5-widget): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-widget/releases/tag/v1.0.0-beta.4)

### Other changes

* Image styles's default configuration has been changed to: left-aligned, right-aligned image and full-size image (instead of the typical: side-image and full-size image). This change makes content previously created with this build incompatible with the new setup.

   You can [configure image styles](https://docs.ckeditor.com/ckeditor5/latest/features/image.html#image-styles) in order to bring back the old setting (`[ 'full', 'side' ]`).

   Closes [#10](https://github.com/ckeditor/ckeditor5-build-decoupled-document/issues/10). ([75855d9](https://github.com/ckeditor/ckeditor5-build-decoupled-document/commit/75855d9))

### BREAKING CHANGES

* The default image styles configuration has been changed (see the section above for more information).


## [1.0.0-beta.3](https://github.com/ckeditor/ckeditor5-build-decoupled-document/compare/v1.0.0-beta.2...v1.0.0-beta.3) (2018-04-10)

### NOTE

This release followed `v1.0.0-beta.2` immediately to fix the issue mentioned below. Therefore, when upgrading from `v1.0.0-beta.1` make sure to also check [`v1.0.0-beta.2` release notes](https://github.com/ckeditor/ckeditor5-build-decoupled-document/releases/tag/v1.0.0-beta.2).

### Bug fixes

* Translations should work when CKEditor was loaded using RequireJS. See [ckeditor/ckeditor5#914](https://github.com/ckeditor/ckeditor5/issues/914). ([df3620e](https://github.com/ckeditor/ckeditor5-build-decoupled-document/commit/df3620e))


## [1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-build-decoupled-document/compare/v1.0.0-beta.1...v1.0.0-beta.2) (2018-04-10)

**Note:** Make sure to see the BREAKING CHANGES section below.

### Dependencies

Major releases (contain breaking changes):

* [@ckeditor/ckeditor5-adapter-ckfinder](https://www.npmjs.com/package/@ckeditor/ckeditor5-adapter-ckfinder): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-adapter-ckfinder/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-alignment](https://www.npmjs.com/package/@ckeditor/ckeditor5-alignment): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-alignment/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-autoformat](https://www.npmjs.com/package/@ckeditor/ckeditor5-autoformat): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-autoformat/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-basic-styles](https://www.npmjs.com/package/@ckeditor/ckeditor5-basic-styles): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-basic-styles/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-block-quote](https://www.npmjs.com/package/@ckeditor/ckeditor5-block-quote): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-block-quote/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-clipboard](https://www.npmjs.com/package/@ckeditor/ckeditor5-clipboard): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-clipboard/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-cloud-services](https://www.npmjs.com/package/@ckeditor/ckeditor5-cloud-services): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-cloud-services/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-core](https://www.npmjs.com/package/@ckeditor/ckeditor5-core): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-core/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-easy-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-easy-image): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-easy-image/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-editor-decoupled](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-decoupled): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-editor-decoupled/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-engine](https://www.npmjs.com/package/@ckeditor/ckeditor5-engine): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-engine/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-enter](https://www.npmjs.com/package/@ckeditor/ckeditor5-enter): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-enter/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-essentials](https://www.npmjs.com/package/@ckeditor/ckeditor5-essentials): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-essentials/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-font](https://www.npmjs.com/package/@ckeditor/ckeditor5-font): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-font/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-heading](https://www.npmjs.com/package/@ckeditor/ckeditor5-heading): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-heading/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-highlight](https://www.npmjs.com/package/@ckeditor/ckeditor5-highlight): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-highlight/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-image): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-image/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-link](https://www.npmjs.com/package/@ckeditor/ckeditor5-link): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-link/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-list](https://www.npmjs.com/package/@ckeditor/ckeditor5-list): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-list/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-paragraph](https://www.npmjs.com/package/@ckeditor/ckeditor5-paragraph): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-paragraph/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-theme-lark](https://www.npmjs.com/package/@ckeditor/ckeditor5-theme-lark): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-theme-lark/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-typing](https://www.npmjs.com/package/@ckeditor/ckeditor5-typing): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-typing/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-ui](https://www.npmjs.com/package/@ckeditor/ckeditor5-ui): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-ui/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-undo](https://www.npmjs.com/package/@ckeditor/ckeditor5-undo): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-undo/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-upload](https://www.npmjs.com/package/@ckeditor/ckeditor5-upload): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-upload/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-utils](https://www.npmjs.com/package/@ckeditor/ckeditor5-utils): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-utils/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-widget](https://www.npmjs.com/package/@ckeditor/ckeditor5-widget): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-widget/releases/tag/v1.0.0-beta.2)

### Other changes

* Renamed the export name from `DecoupledDocumentEditor` to `DecoupledEditor`. Closes [#6](https://github.com/ckeditor/ckeditor5-build-decoupled-document/issues/6). ([bc9da6a](https://github.com/ckeditor/ckeditor5-build-decoupled-document/commit/bc9da6a))
* Updated the build to the latest `DecoupledEditor` class API (see [ckeditor/ckeditor5-editor-decoupled#10](https://github.com/ckeditor/ckeditor5-editor-decoupled/issues/10)). ([7b4aef1](https://github.com/ckeditor/ckeditor5-build-decoupled-document/commit/7b4aef1))

### BREAKING CHANGES

* The global variable exported by the build is now called `DecoupledEditor` instead of `DecoupledDocumentEditor`. See [#6](https://github.com/ckeditor/ckeditor5-build-decoupled-document/issues/6).
* The config options `config.toolbarContainer` and `config.editableContainer` have been removed. Please refer to the `DecoupledEditor` class API documentation to learn about possible methods of bootstrapping the UI.


## [1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-build-decoupled-document/compare/v0.0.1...v1.0.0-beta.1) (2018-03-15)

### Features

* Implemented the document editor build on top of the decoupled editor. Closes [#1](https://github.com/ckeditor/ckeditor5-build-decoupled-document/issues/1). ([5bf2a07](https://github.com/ckeditor/ckeditor5-build-decoupled-document/commit/5bf2a07))
