## Open Source > NHN CloudUI Grid > 개요

## ![NHN Cloud ui grid](https://cloud.githubusercontent.com/assets/12269489/13489851/a5ca2490-e16c-11e5-8d80-3bf6fe3b940d.png)
<br>
The NHN Cloud UI Grid is a powerful widget which allows you to visualize and edit data via its table representation.

## Features
* Various input types *(checkbox, radio, select, password, etc)*
* Full keyboard navigation *(move, select, copy, paste, delete, etc)*
* Virtual scrolling *(Handling large dataset without performance loses)*
* Copy & Paste using clipboard with 3rd party application *(Like MS-Excel or Google-spreadsheet)*
* Column resize & reorder & show & hide
* Multi column headers
* Custom cell formatter & converter
* Inline Editing
* Validation
* Selection
* Pagination
* Picking date
* Sorting
* Merging cell
* Frozen(Pinned) columns
* Relation between each columns
* Binding to remote data

<br>
The video below shows the major features of NHN Cloud UI Grid briefly.<br>
(Click the image to play!)

[![intro-movie-shot](http://static.toastoven.net/prod_toastuigrid/intro-movie-sshot.png)](https://www.youtube.com/watch?v=pyPlOFhexQk)

Check more detailed explanation on https://github.com/nhn/tui.grid/wiki.

## Documentation
* **API** : [https://nhn.github.io/tui.grid/api](https://nhn.github.io/tui.grid/api)
* **Tutorial** : [https://github.com/nhn/tui.grid/wiki/Getting-Started](https://github.com/nhn/tui.grid/wiki/Getting-Started)
* **Example** : [https://nhn.github.io/tui.grid/api/tutorial-example01-basic.html](https://nhn.github.io/tui.grid/api/tutorial-example01-basic.html)

You can also see the older versions of API page on the [releases page](https://github.com/nhn/tui.grid/releases).

## Dependencies
* [jquery](https://jquery.com/) >=1.11.0
* [underscore](http://underscorejs.org/) >=1.8.3
* [backbone](http://backbonejs.org/) >=1.3.3
* [tui-code-snippet](https://github.com/nhn/tui.code-snippet) >=1.2.5
* component (optional)
  - [tui-pagination](https://github.com/nhn/tui.pagination) >=3.0.0
  - [tui-date-picker](https://github.com/nhn/tui.date-picker) >=3.0.0

You can also use **lodash** instead of underscore and use **higher version of jquery** (like v2.x.x) depending on your project.

## Browser Support
* IE8~11
* Edge
* Chrome
* Firefox
* Safari

## Usage
### Use **npm**

Install the latest version using **npm** command:

```
$ npm install tui-grid --save
```

or want to install the each version:

```
$ npm install tui-grid@<version> --save
```

To access as module format in your code:

```javascript
var Grid = require('tui-grid');
var instance = new Grid(...);
```

### Use **bower**
Install the latest version using **bower** command:

```
$ bower install tui-grid
```

or want to install the each version:

```
$ bower install tui-grid#<tag>
```

To access as namespace format in your code:

```javascript
var instance = new tui.Grid(...);
```

### Download
* [Download all sources for each version.](https://github.com/nhn/tui.grid/releases)

## License
This software is licensed under the [MIT License](https://github.com/nhn/tui.grid/blob/master/LICENSE).
