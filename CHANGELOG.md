<a name="0.5.0"></a>
# [0.5.0](https://github.com/algolia/instantsearch.js/compare/v0.4.1...v0.5.0) (2015-10-22)


### Bug Fixes

* **example:** Example searchbox ([cdad6c7](https://github.com/algolia/instantsearch.js/commit/cdad6c7)), closes [#157](https://github.com/algolia/instantsearch.js/issues/157)
* **hierarchicalFacets:** use a real attribute name for the hierarchicalFacet name ([0d2a455](https://github.com/algolia/instantsearch.js/commit/0d2a455))
* **hits:** Fix warning about unique key in iterator ([0c9468c](https://github.com/algolia/instantsearch.js/commit/0c9468c))
* **onClick:** do not replace the browser's behavior on special clicks ([8562d49](https://github.com/algolia/instantsearch.js/commit/8562d49)), closes [#278](https://github.com/algolia/instantsearch.js/issues/278)
* **package.json:** typo in repository ([33cf196](https://github.com/algolia/instantsearch.js/commit/33cf196))
* **pagination:** do not generate the URL for disabled pages. ([e5d78ab](https://github.com/algolia/instantsearch.js/commit/e5d78ab)), closes [#282](https://github.com/algolia/instantsearch.js/issues/282)
* **poweredBy:** Extract its hiding capabilities ([f5fa9ee](https://github.com/algolia/instantsearch.js/commit/f5fa9ee)), closes [#189](https://github.com/algolia/instantsearch.js/issues/189)
* **rangeSlider:** refinements cleanuo ([16c132c](https://github.com/algolia/instantsearch.js/commit/16c132c)), closes [#147](https://github.com/algolia/instantsearch.js/issues/147)
* **rangeSlider:** restore wrongly removed state nesting ([3ed3d39](https://github.com/algolia/instantsearch.js/commit/3ed3d39))
* **React:** require React in order for JSX to work in widgets ([64d6011](https://github.com/algolia/instantsearch.js/commit/64d6011))
* **react-nouislider:** upgrade react-nouislider to avoid mutating props ([1b7cd1d](https://github.com/algolia/instantsearch.js/commit/1b7cd1d))
* **refinementList:** Remove `singleRefine` attribute ([db73e38](https://github.com/algolia/instantsearch.js/commit/db73e38)), closes [#220](https://github.com/algolia/instantsearch.js/issues/220)
* **refinementList:** singleRefine is not dependant from operator ([d29dff6](https://github.com/algolia/instantsearch.js/commit/d29dff6))
* **RefinementList:** click on child should not click on parent ([d476da2](https://github.com/algolia/instantsearch.js/commit/d476da2)), closes [#191](https://github.com/algolia/instantsearch.js/issues/191)
* **Slider:** cssClasses.body handled by headerFooter HOC ([d8d20b2](https://github.com/algolia/instantsearch.js/commit/d8d20b2))
* **stats:** Move CSS classes definition to widget from component ([99073cd](https://github.com/algolia/instantsearch.js/commit/99073cd))
* **transformData:** add an explicit error message ([94c53d3](https://github.com/algolia/instantsearch.js/commit/94c53d3)), closes [#212](https://github.com/algolia/instantsearch.js/issues/212)
* **transformData:** this test is not needed, already covered by Template ([36e5b9c](https://github.com/algolia/instantsearch.js/commit/36e5b9c))
* **validate-commit:** Update the regexp ([96b93ba](https://github.com/algolia/instantsearch.js/commit/96b93ba))

### Features

* **bem:** Add BEM to the index-selector widget ([564da51](https://github.com/algolia/instantsearch.js/commit/564da51))
* **bem:** Add BEM-styling to the Stats widget ([92cebeb](https://github.com/algolia/instantsearch.js/commit/92cebeb))
* **build:** Add minified CSS theme version to build ([77f0640](https://github.com/algolia/instantsearch.js/commit/77f0640))
* **core/lifecycle-event:** emits `render` when render ([7f03ae9](https://github.com/algolia/instantsearch.js/commit/7f03ae9))
* **es7:** Enable `es7.objectRestSpread` ([fc2fbc4](https://github.com/algolia/instantsearch.js/commit/fc2fbc4))
* **headerFooter:** Add BEM classes to header and footer ([9e9d438](https://github.com/algolia/instantsearch.js/commit/9e9d438)), closes [#259](https://github.com/algolia/instantsearch.js/issues/259)
* **hierarchical-menu:** Add BEM classes ([58ec191](https://github.com/algolia/instantsearch.js/commit/58ec191))
* **hierarchical-menu:** Add CSS classes dependent on the depth ([1256ea8](https://github.com/algolia/instantsearch.js/commit/1256ea8))
* **hits:** Add BEM styling to the `hits` widget ([6681960](https://github.com/algolia/instantsearch.js/commit/6681960))
* **menu:** Add BEM classes ([467f49e](https://github.com/algolia/instantsearch.js/commit/467f49e))
* **pagination:** add `scrollTo` option ([e6cd621](https://github.com/algolia/instantsearch.js/commit/e6cd621)), closes [#73](https://github.com/algolia/instantsearch.js/issues/73)
* **priceRanges:** new Amazon-style price ranges widget ([e5fe344](https://github.com/algolia/instantsearch.js/commit/e5fe344))
* **priceRanges:** polish priceRanges widget ([0994e6f](https://github.com/algolia/instantsearch.js/commit/0994e6f))
* **refinement-list:** Add BEM naming ([b09b830](https://github.com/algolia/instantsearch.js/commit/b09b830))
* **refinementlist:** Move default templates to its own file ([cb6fa16](https://github.com/algolia/instantsearch.js/commit/cb6fa16))
* **refinementList:** Limits improvement ([ebcc8a9](https://github.com/algolia/instantsearch.js/commit/ebcc8a9))
* **searchbox:** Make the searchBox BEMish ([db8bd60](https://github.com/algolia/instantsearch.js/commit/db8bd60))
* **theme:** Add `searchBox` widget to default theme ([def831f](https://github.com/algolia/instantsearch.js/commit/def831f))
* **theme:** Add debug.css file ([ff8f2dc](https://github.com/algolia/instantsearch.js/commit/ff8f2dc)), closes [#249](https://github.com/algolia/instantsearch.js/issues/249)
* **theme:** Move `indexSelector` styling to default.css ([1841ef1](https://github.com/algolia/instantsearch.js/commit/1841ef1))
* **theme:** Move all default css rules to `default.css` ([57c8c65](https://github.com/algolia/instantsearch.js/commit/57c8c65))
* **toggle:** Adding BEM class naming ([8730c97](https://github.com/algolia/instantsearch.js/commit/8730c97))
* **urlSync:** url generation for widget links. Fix #29 ([23dd505](https://github.com/algolia/instantsearch.js/commit/23dd505)), closes [#29](https://github.com/algolia/instantsearch.js/issues/29)


### BREAKING CHANGES

* build: You should now include the `default.css` file in your
page to get the default styling.

- Added `clean-css` as minifier
- Updated build script
- Updated documentation about loading it from jsdeliver
- `npm shrinkwrap` madness
* hits: The hit template and transform data key is renamed
from `hit` to `item` to stay consistent with the other widgets
* menu: The default template now has the count element inside
the link, not outside.
* stats: `cssClasses.root` now applies to the main root
element (above header and footer) and no longer to the template
wrapper. To style the template wrapper, use `cssClasses.body`
* theme: Classes are now named `ais-index-selector` and
`ais-index-selector--item` to stay consistent with other widgets.

Updated tests as well. Widget is responsible for adding default
classes + user-defined ones. Then component simply add them to the
markup.
* theme: "Powered by" styles are now
`ais-search-box--powered-by` and `ais-search-box--powered-by-link`.
* urlSync: urlSync is not a widget anymore. It's now an option of
instantsearch(appID, apiKey, opts);. See the README.md for more info.
* searchbox: The `searchBox` widget now expect
a `cssClasses.{input, poweredBy}`
* bem: We now use a `span.ais-stats--time` instead of
a `small` tag in the stats widget.
* bem: We now use `cssClasses.select` and
`cssClasses.option` instead of `cssClass` for the index-selector
widget.



<a name="0.4.1"></a>
## [0.4.1](https://github.com/algolia/instantsearch.js/compare/v0.4.0...v0.4.1) (2015-10-05)


### Bug Fixes

* allow passing only one key of transformData as an object ([e0ce89f](https://github.com/algolia/instantsearch.js/commit/e0ce89f))
* **search-box:** Fix #137 autofocus must be configurable ([51f01be](https://github.com/algolia/instantsearch.js/commit/51f01be)), closes [#137](https://github.com/algolia/instantsearch.js/issues/137)
* **searchBox:** do not update input's value if focused ([0e85f0d](https://github.com/algolia/instantsearch.js/commit/0e85f0d)), closes [#163](https://github.com/algolia/instantsearch.js/issues/163)
* **templatesConfig:** helpers are now following Mustache spec ([8f3502f](https://github.com/algolia/instantsearch.js/commit/8f3502f))
* **url-sync:** handle both hash and query parameter fix #165 ([8d84de6](https://github.com/algolia/instantsearch.js/commit/8d84de6)), closes [#165](https://github.com/algolia/instantsearch.js/issues/165)



<a name="0.4.0"></a>
# [0.4.0](https://github.com/algolia/instantsearch.js/compare/v0.3.0...v0.4.0) (2015-09-30)


### Bug Fixes

* **pagination:** handle cases where maxPages is low ([d3c9959](https://github.com/algolia/instantsearch.js/commit/d3c9959)), closes [#100](https://github.com/algolia/instantsearch.js/issues/100)
* **searchBox:** allow searchBox to reuse an `<input>` ([e820cc3](https://github.com/algolia/instantsearch.js/commit/e820cc3))
* **searchBox:** Use `hasAttribute` instead of `getAttribute` ([a122af9](https://github.com/algolia/instantsearch.js/commit/a122af9))
* **slider:** allow handles to reach the real start and end of the slider ([03ed3f5](https://github.com/algolia/instantsearch.js/commit/03ed3f5))
* **slider:** fix tap event throwing ([d906d3e](https://github.com/algolia/instantsearch.js/commit/d906d3e)), closes [#120](https://github.com/algolia/instantsearch.js/issues/120)
* **Template:** add default value for template ([4291014](https://github.com/algolia/instantsearch.js/commit/4291014))
* **url-sync:** make input not to lose focus ([63488d3](https://github.com/algolia/instantsearch.js/commit/63488d3))

### Features

* **rangeSlider:** add headerFooter decorator ([19090c3](https://github.com/algolia/instantsearch.js/commit/19090c3))
* **searchBox:** add headerFooter decorator to the Component ([5974a88](https://github.com/algolia/instantsearch.js/commit/5974a88))
* **templatesConfig:** helpers and options transferred to Template ([456d781](https://github.com/algolia/instantsearch.js/commit/456d781)), closes [#99](https://github.com/algolia/instantsearch.js/issues/99)
* **toggle:** add headerFooter decorator ([8a70c7d](https://github.com/algolia/instantsearch.js/commit/8a70c7d))
* **url-sync:** Add `is_v` version to url ([9f597a0](https://github.com/algolia/instantsearch.js/commit/9f597a0)), closes [#70](https://github.com/algolia/instantsearch.js/issues/70)
* hierarchicalWidget ([1facd9d](https://github.com/algolia/instantsearch.js/commit/1facd9d))


### BREAKING CHANGES

* S:
- toggle: removed template
* - removed: inputClass



<a name="0.3.0"></a>
# [0.3.0](https://github.com/algolia/instantsearch.js/compare/v0.2.2...v0.3.0) (2015-09-24)


### Bug Fixes

* Allow not specifying `cssClass` on index selector ([4e9324f](https://github.com/algolia/instantsearch.js/commit/4e9324f))
* More explicit error message when DOM selector is invalid ([d36a2ad](https://github.com/algolia/instantsearch.js/commit/d36a2ad)), closes [#105](https://github.com/algolia/instantsearch.js/issues/105)
* Pass nbHits, hitsPerPage, nbPages and page to Stats widget ([deefd23](https://github.com/algolia/instantsearch.js/commit/deefd23)), closes [#106](https://github.com/algolia/instantsearch.js/issues/106)
* **hideIfEmpty:** should be hideWhenNoResults ([21877a0](https://github.com/algolia/instantsearch.js/commit/21877a0))
* **Hits:** handle the display when there is no result ([544ff5c](https://github.com/algolia/instantsearch.js/commit/544ff5c))
* **menu:** send an empty array values when no values ([12cd7dc](https://github.com/algolia/instantsearch.js/commit/12cd7dc)), closes [#107](https://github.com/algolia/instantsearch.js/issues/107)
* **pagination:** missing showFirstLast attribute when instanciating ([28fa0ae](https://github.com/algolia/instantsearch.js/commit/28fa0ae))
* **SearchBox:** Missing poweredBy in the not focused SearchBox ([ef695ff](https://github.com/algolia/instantsearch.js/commit/ef695ff))
* **slider:** hide slider if when no hits/matches ([31e4a80](https://github.com/algolia/instantsearch.js/commit/31e4a80)), closes [#107](https://github.com/algolia/instantsearch.js/issues/107)

### Features

* **menu,refinementList:** add header/item/footer templating solution ([58275dc](https://github.com/algolia/instantsearch.js/commit/58275dc)), closes [#101](https://github.com/algolia/instantsearch.js/issues/101)
* **searchBox:** add poweredBy option, disabled by default ([c9da165](https://github.com/algolia/instantsearch.js/commit/c9da165))
* **stats:** add query variable to the template ([75f457d](https://github.com/algolia/instantsearch.js/commit/75f457d))
* **transformData:** add to every widget using the Template component ([d080a03](https://github.com/algolia/instantsearch.js/commit/d080a03)), closes [#116](https://github.com/algolia/instantsearch.js/issues/116)
* **transformData:** refinementList + menu implementation ([0a0e36e](https://github.com/algolia/instantsearch.js/commit/0a0e36e))
* **urlSync:** add urlSync widget ([50fc4ce](https://github.com/algolia/instantsearch.js/commit/50fc4ce))
* **widgets:** auto hide some widgets ([187b4bd](https://github.com/algolia/instantsearch.js/commit/187b4bd))


### BREAKING CHANGES

* Removed from menu and refinementList:
- rootClass => cssClasses.root
- itemCLass => cssClasses.item
- template => templates.item

Added to menu and refinementList:
- cssClasses{root,list,item}
- templates{header,item,footer}
- widget (container) is automatically hidden by default
- hideWhenNoResults=true

This was done to allow more templating solutions like discussed in #101.



<a name="0.2.2"></a>
## [0.2.2](https://github.com/algolia/instantsearch.js/compare/v0.1.0...v0.2.2) (2015-09-17)




<a name="0.2.1"></a>
## [0.2.1](https://github.com/algolia/instantsearch.js/compare/v0.1.0...v0.2.1) (2015-09-17)




<a name="0.1.0"></a>
# 0.1.0 (2015-09-17)

First release

<a name="0.0.0"></a>
## [0.0.0](https://github.com/algolia/instantsearch.js/compare/v0.0.0...v0.0.0) (2015-09-17)

First commit