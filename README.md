# angular-deep-table

A Deep Table Level as tree, for AngularJS

# Install 

* Via bower 
	```sh
	bower i --save angular-deep-table
	```
# Getting started 

1. Include `src/deepTable.css` and `src/directive.js` in your HTML file. 
2. Then include the module as a dependency in your application:
	```js
	angular.module('myApp', ['deepTable'])
	```
3. Just add the following
	```html
	<deep-table tree-data="tree_data"></deep-table>
	```