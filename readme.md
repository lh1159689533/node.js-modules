# 很棒的微npm包 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> 一个小的、集中的node.js模块列表.

*受启发于 [awesome](https://github.com/sindresorhus/awesome) .*


## Articles

* [One-line node modules](https://github.com/sindresorhus/ama/issues/10)
* [构建小型的单一用途模块](http://thenodeway.io/introduction/#build-small-single-purpose-modules)
* [模块的最佳实践](https://github.com/mattdesl/module-best-practices)
* [评估包 Part 1 - Turn to community](http://bytearcher.com/articles/evaluating-packages-1-check-community/) 
* [评估包 Part 2 - Review repository](http://bytearcher.com/articles/evaluating-packages-2-review-repository/)
* [Small modules: it’s not quite that simple](https://medium.com/@Rich_Harris/small-modules-it-s-not-quite-that-simple-3ca532d65de4)
* [高度模块化的包: A Crazy Cult or a Reasonable Practice?](http://thefullstack.xyz/hyper-modular-packages-a-crazy-cult-or-a-reasonable-practice/)
* [In Defense of Hyper Modular JavaScript](https://medium.freecodecamp.com/in-defense-of-hyper-modular-javascript-33934c79e113)
* [小npm包: 创建遵循小程序包思想的node.js模块](http://g14n.info/2015/12/tiny-npm-package/)
* [小模块的成本](https://nolanlawson.com/2016/08/15/the-cost-of-small-modules/)
* [为什么我认为“微包”是一件好事.](http://codetunnel.io/why-i-think-micro-packages-are-a-good-thing/)

## Modules

### Array

* [is-sorted](https://github.com/dcousens/is-sorted) - 用于检查数组是否排序.
* [array-first](https://github.com/jonschlinkert/array-first) - 获取数组中前n个元素.
* [array-last](https://github.com/jonschlinkert/array-last) - 获取数组中后n个元素.
* [arr-flatten](https://github.com/jonschlinkert/arr-flatten) - 展开一个嵌套数组.
* [dedupe](https://github.com/seriousManual/dedupe) - 从数组中删除重复项.
* [array-range](https://github.com/mattdesl/array-range) - 创建一个给定范围的数组.
* [arr-diff](https://github.com/jonschlinkert/arr-diff) - 通过严格的比较从第一个数组中排除附加数组中的所有值并返回.
* [filled-array](https://github.com/sindresorhus/filled-array) - 返回一个用指定值填充的指定长度的数组
* [map-array](https://github.com/parro-it/map-array) - 将对象的键和值以'key value'的格式映射到数组中.
* [in-array](https://github.com/jonschlinkert/in-array) - 若传递的值在数组中则返回true - 比indexOf更高效.
* [unordered-array-remove](https://github.com/mafintosh/unordered-array-remove) - 有效地从无序数组中删除元素，而不需要执行拼接.
* [array-swap](https://github.com/michaelzoidl/swap-array) - 交换数组中两项的位置(有错误一处).
* [mirrarray](https://github.com/johnwquarles/mirrarray) - 从有效键数组创建keymirror对象.
* [group-array](https://github.com/doowb/group-array) - 将对象数组分组到列表中.
* [array.chunk](https://github.com/zhiyelee/array.chunk) - 将array/TypedArray分割为指定大小的子数组.

### String

* [decamelize](https://github.com/sindresorhus/decamelize) - 将驼峰化字符串转换为带有自定义分隔符的小写字符串: unicornRainbow → unicorn_rainbow.
* [pad-left](https://github.com/jonschlinkert/pad-left) - 左填充带有0或指定字符的字符串.
* [to-camel-case](https://github.com/ianstormtaylor/to-camel-case) - 将字符串转换为驼峰式.
* [to-capital-case](https://github.com/ianstormtaylor/to-capital-case) - 将字符串转换为大写.
* [to-constant-case](https://github.com/ianstormtaylor/to-constant-case) - 将字符串转换为常量.
* [to-dot-case](https://github.com/ianstormtaylor/to-dot-case) - 将字符串用"."分割：camelCase → camel.case, space case → space.case, weird[case → weird.case.
* [to-no-case](https://github.com/ianstormtaylor/to-no-case) - 替换字符串中的'_ -'分隔符为空格并小写,若为驼峰式则驼峰字符小写且驼峰处空格分割.
* [to-pascal-case](https://github.com/ianstormtaylor/to-pascal-case) - 将空格'_ . ['等连接符连接的字符串转换为驼峰式且首字母大写.
* [to-sentence-case](https://github.com/ianstormtaylor/to-sentence-case) - 字符串句首字母大写：the catcher, in the rye. → The catcher, in the rye.
* [to-snake-case](https://github.com/ianstormtaylor/to-snake-case) - 将字符串用"_"分割：camelCase → camel_case, space case → space_case, weird[case → weird_case, dot.case → dot_case.
* [to-space-case](https://github.com/ianstormtaylor/to-space-case) - 移除字符串中的特殊字符：camelCase → camel case, snake_case → snake case, dot.case → dot case, -RAnDom -jUNk$__loL! → random junk lol.
* [to-title-case](https://github.com/ianstormtaylor/to-title-case) - Convert a string to a title case：the catcher in the rye → The Catcher in the Rye.
* [node-slug](https://github.com/dodo/node-slug) - slugifies even utf-8 chars.
* [rtrim](https://github.com/sergejmueller/rtrim) - Strip whitespace - or other characters - from the end of a string.
* [slice.js](https://github.com/hustcc/slice.js) - Javascript library to engance String.substring / Array.slice with python slice style.
* [strip-ansi](https://github.com/chalk/strip-ansi) - Strip ANSI escape codes.
* [striptags](https://github.com/ericnorris/striptags) - An implementation of PHP's strip_tags in Node.js.
* [parse-next-json-value](https://github.com/ErikOnBike/parse-next-json-value) - Parse next JSON value from string allowing extraneous characters after value.

### Date & Time

* [pretty-ms](https://github.com/sindresorhus/pretty-ms) - Convert milliseconds to a human readable string: 1337000000 → 15d 11h 23m 20s.
* [hirestime](https://github.com/seriousManual/hirestime) - A wrapper around the built-in high resolution timer which simplifies the calculation of timestamps.
* [periods](https://github.com/timruffles/periods) - Defined time-periods constants for Javascript, in milliseconds.
* [fecha](https://github.com/taylorhakes/fecha) - Javascript Date formatting and parsing.
* [akamai-time-reference](https://github.com/jucrouzet/akamai-time-reference) - Get reference time using Akamai's time reference service.
* [timeago.js](https://github.com/hustcc/timeago.js) - A tiny(~1.7kb) library used to format date with `*** time ago` statement.
* [count-days-in-month](https://github.com/shinnn/count-days-in-month) - Get the number of days in a given month.
* [time-stamp](https://github.com/jonschlinkert/time-stamp) - Get a formatted timestamp.
* [twas](https://github.com/vutran/twas) - Generate a relative time string (Example: "3 seconds ago")

### Object

* [map-obj](https://github.com/sindresorhus/map-obj) - Map object keys and values into a new object.
* [filter-obj](https://github.com/sindresorhus/filter-obj) - Filter object keys and values into a new object.
* [object-values](https://github.com/sindresorhus/object-values) - Get the values of an object.
* [object-pairs](https://github.com/eush77/object-pairs) - Turn an object into list of [key, value] pairs for mapping, iterating or other purposes.
* [zipmap](https://github.com/landau/zipmap) - Returns a map with the keys mapped to the corresponding vals. zipmap also accepts a single value of objects or pairs.
* [just-pluck](https://github.com/jarofghosts/just-pluck) - Pluck without the madness.
* [deep-equal](https://github.com/substack/node-deep-equal) - Node's assert.deepEqual() algorithm as a standalone module.
* [deep-assign](https://github.com/sindresorhus/deep-assign) - Recursive Object.assign().
* [set-value](https://github.com/jonschlinkert/set-value) - Create nested values and any intermediaries dot notation (`'a.b.c'`) paths.
* [get-value](https://github.com/jonschlinkert/get-value) - Use property paths (a.b.c) to get a nested value from an object.
* [has-value](https://github.com/jonschlinkert/has-value) - Returns true if a value exists, false if empty. Works with deeply nested values using dot notation (`'a.b.c'`) paths.
* [has-key-deep](https://github.com/ryanaghdam/has-key-deep) - Deep-search objects for keys. Keys can be searched by providing an array of keys, or using a dot-notiation.
* [flatkeys](https://github.com/ricardobeat/flatkeys) - Flatten object key hierarchies into a list of strings using a custom separator.
* [flatten-obj](https://github.com/watson/flatten-obj) - Converts an object literal with deeply nested nodes to a simple key/value object.
* [is-empty-object](https://github.com/gummesson/is-empty-object) - Check if an object is empty.
* [stringify-object](https://github.com/yeoman/stringify-object) - Stringify an object/array like JSON.stringify just without all the double-quotes.
* [sorted-object](https://github.com/domenic/sorted-object) - Returns a copy of an object with its keys sorted.
* [static-props](https://github.com/fibo/static-props) - Defines static object attributes using `Object.defineProperties`
* [missing-deep-keys](https://github.com/vladgolubev/missing-deep-keys) - Returns an array of keys from first object that are missing in second.
* [has-own-property](https://github.com/LinusU/has-own-property) - Check if an object has a local property. 
* [merge-objects](https://github.com/shevaroller/node-merge-objects) - Deep-merge two objects. Arrays that are values of the same object key get concatenated.
* [deep-object-diff](https://github.com/mattphillips/deep-object-diff) - Deep diff two JavaScript Objects while preserving the data structure. Including nested structures of Arrays and Objects.

### Function

* [compose-function](https://github.com/stoeffel/compose-function) - Compose a new function from smaller functions `f(g(x))`.
* [curry](https://github.com/dominictarr/curry) - A curry function without anything too clever.
* [once](https://github.com/isaacs/once) - Run a function exactly one time.
* [deep-bind](https://github.com/jonschlinkert/deep-bind) - Bind a context to all functions in an object, including deeply nested functions.
* [identity-function](https://github.com/substack/identity-function) - Always return the input argument. 
* [mem](https://github.com/sindresorhus/mem) - An optimization technique used to speed up consecutive function calls by caching the result of calls with identical input.
* [throttle-debounce](https://github.com/niksy/throttle-debounce) - Throttle/debounce your functions.
* [compose-tiny](https://github.com/hipstersmoothie/compose-tiny) - A very tiny and fast compose function.

### Math

* [is-number](https://github.com/jonschlinkert/is-number) - Returns `true` if the value is a number.

### Stream
* [through2](https://github.com/rvagg/through2) - Tiny wrapper around Node streams2 Transform to avoid explicit subclassing noise.
* [through2-filter](https://github.com/brycebaril/through2-filter) - A through2 to create an Array.prototype.filter analog for streams.
* [through2-map](https://github.com/brycebaril/through2-map) - A through2 to create an Array.prototype.map analog for streams.
* [stream-spigot](https://github.com/brycebaril/node-stream-spigot) - A readable stream generator, useful for testing or converting simple functions into Readable streams.
* [concat-stream](https://github.com/maxogden/concat-stream) - writable stream that concatenates strings or data and calls a callback with the result.
* [JSONStream](https://github.com/dominictarr/JSONStream) - streaming JSON.parse and stringify
* [through2-map-promise](https://github.com/RangerMauve/through2-map-promise) - A small promise-based wrapper for through2.
* [pump](https://github.com/mafintosh/pump) - pipe streams together and close all of them if one of them closes.
* [split](https://github.com/dominictarr/split) - Break up a stream and reassemble it so that each line is a chunk.
* [is-stream](https://github.com/sindresorhus/is-stream) - Check if something is a Node.js stream.
* [syncthrough](https://github.com/mcollina/syncthrough) - Transform your data as it pass by, synchronously.


### Promise

* [pify](https://github.com/sindresorhus/pify) - Promisify a callback-style function.
* [promise-all-props](https://github.com/Siilwyn/promise-all-props) - Like `Promise.all` but for object properties.
* [sleep-promise](https://github.com/brummelte/sleep-promise) - Resolves a promise after a specified delay.
* [is-promise](https://github.com/then/is-promise) - Test whether an object looks like a promises-a+ promise.

### File System

* [rimraf](https://github.com/isaacs/rimraf) - A deep deletion module for node (like rm -rf).
* [mkdirp](https://github.com/substack/node-mkdirp) - Recursively mkdir, like mkdir -p.
* [du](https://github.com/rvagg/node-du) - A simple JavaScript implementation of du -sb.
* [file-size](https://github.com/Nijikokun/file-size) - Lightweight filesize to human-readable / proportions w/o dependencies.
* [tmp](https://github.com/raszi/node-tmp) - Temporary file and directory creator for node.js.
* [fs-promise](https://github.com/kevinbeaty/fs-promise) - Node fs methods as Promise/A+ (optional fs-extra, graceful-fs).

### Browser

* [delegate](https://github.com/zenorocha/delegate) - Lightweight event delegation.
* [insert-css](https://github.com/substack/insert-css) - Insert a string of css into the head
* [dom-element-value](https://github.com/crysalead-js/dom-element-value) - DOM element value getter/setter.
* [image-promise](https://github.com/bfred-it/image-promise) - Load one or more `<img>`s in a Promise.
* [get-media-size](https://github.com/bfred-it/get-media-size) - Get the original size of any `img`/`video`/`svg`/`canvas` tags or canvas context.
* [document-ready](https://github.com/bendrucker/document-ready) - Document ready listener for modern browsers.
* [copee](https://github.com/styfle/copee) - Copy text from browser to clipboard...natively!

### Semver

* [semver](https://github.com/npm/node-semver) - The semantic version parser used by npm.
* [semver-max](https://github.com/eush77/semver-max) - Find maximum (or minimum) version according to semver.
* [semver-first-satisfied](https://github.com/parro-it/semver-first-satisfied) - Find minimum in an array of version that satisfies a semver range.



### CLI

* [abbrev](https://github.com/isaacs/abbrev-js) - Calculate the set of unique abbreviations for a given set of strings.
* [glob](https://github.com/isaacs/node-glob) - Glob functionality for node.js.
* [username](https://github.com/sindresorhus/username) - Get the username of the current user.
* [minimist](https://github.com/substack/minimist) - Parse argument options.
* [png-to-ico](https://github.com/steambap/png-to-ico) - Convert png to windows ico format.
* [help-version](https://github.com/eush77/help-version) - Easily handle --help and --version arguments in your CLI application

### Module management

* [pkg-conf](https://github.com/sindresorhus/pkg-conf) - Get namespaced config from the closest package.json.
* [normalize-pkg](https://github.com/jonschlinkert/normalize-pkg) - Normalize values in package.json to improve compatibility, programmatic readability and usefulness with third party libs.

### Generators

* [is-generator](https://github.com/blakeembrey/is-generator) - Check whether a given value is a generator function.

### Other

* [uuid](https://github.com/kelektiv/node-uuid) - Generate RFC-compliant UUIDs in JavaScript.
* [node-mime](https://github.com/broofa/node-mime) - Comprehensive MIME type mapping API based on mime-db module.
* [not-defined](https://github.com/fibo/not-defined) - Checks if foo is not defined, i.e. undefined, null, an empty string, array or object.
* [is-fqdn](https://github.com/parro-it/is-fqdn) - Check if a string represent a fully qualified domain name.

## Related lists

This section contains awesome lists that you may find useful if you use or write small NPM modules.

* [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs) - A curated list of delightful Node.js packages and resources.
* [awesome-npm](https://github.com/sindresorhus/awesome-npm) - Awesome npm resources and tips.

## Small modules rockstars to follow

These people are used to develop awesome NPM modules that follows the single responsibility philosophy.
Follow them to discover new great modules:

[![Sindre Sorhus](https://avatars.githubusercontent.com/u/170270?s=130)](https://github.com/sindresorhus) | [![James Halliday](https://avatars1.githubusercontent.com/u/12631?s=130)](https://github.com/substack) | [![Eugene Sharygin](https://avatars3.githubusercontent.com/u/4472489?s=130)](https://github.com/eush77) | [![Isaac Z. Schlueter](https://avatars3.githubusercontent.com/u/9287?s=130)](https://github.com/isaacs) | [![Jon Schlinkert](https://avatars1.githubusercontent.com/u/383994?s=130)](https://github.com/jonschlinkert) | [![Dominic Tarr](https://avatars3.githubusercontent.com/u/259374?s=130)](https://github.com/dominictarr)
---|---|---|---|---|---
[Sindre Sorhus](https://github.com/sindresorhus) | [James Halliday](https://github.com/substack) | [Eugene Sharygin](https://github.com/eush77) | [Isaac Z. Schlueter](https://github.com/isaacs) | [Jon Schlinkert](https://github.com/jonschlinkert) | [Dominic Tarr](https://github.com/dominictarr)

[![Rod Vagg](https://avatars0.githubusercontent.com/u/495647?s=130)](https://github.com/rvagg) | [![Max Ogden](https://avatars3.githubusercontent.com/u/39759?s=130)](https://github.com/maxogden) | [![Brian Woodward](https://avatars1.githubusercontent.com/u/995160?s=130)](https://github.com/doowb)
---|---|---
[Rod Vagg](https://github.com/rvagg) | [Max Ogden](https://github.com/maxogden) | [Brian Woodward](https://github.com/doowb)


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Andrea Parodi](https://github.com/parro-it) has waived all copyright and related or neighboring rights to this work.
