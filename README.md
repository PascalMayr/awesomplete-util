# AwesompleteUtil 

Javascript library by [nico-amsterdam](https://github.com/nico-amsterdam) as npm module that utilizes Lea Verou's autocomplete / autosuggest / typeahead / inputsearch [Awesomplete widget](https://leaverou.github.io/awesomplete/index.html). It adds the following features:

- Dynamic remote data loading; based on what is typed-in it performs an ajax lookup.
- Allow HTML markup in the shown items. Show value with description. Optionally search in the description text.
- Show when there is an exact match.
- Show when a list is loading from a remote source.
- Show when there isn't a match.
- When there is an exact match show related data (supplied in the remote data) in other parts of the page.
- Select the highlighted item when tab key is used.

Install
-------
```sh
$ yarn add awesomplete-util # Or alternatively: `npm i awesomplete-util`
```

Usage
-----
````js
import AwesompleteUtil from 'awesomplete-util'
````

## Examples and documentation

[live examples](https://nico-amsterdam.github.io/awesomplete-util/index.html) with code.

The CSS class 'awe-loading' is put on the input control when there is an ongoing XHR request.

## Generate minified version with sourcemap

Copy index.js and make your desired changes.
Install the Node package manager and the uglify-js node module.
Adjust the paths in mini.sh and run this shell script to generated the minified version of AwesompleteUtil and the sourcemap.

## License

[MIT](LICENSE)

