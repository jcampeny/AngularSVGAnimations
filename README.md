# README #

## What is this? ##

AngularJS module that adds support for animate your svg files.


## How to install? ##


If you dont have Nodejs installed, you must do it at this point. Please visit: http://nodejs.org/ for instructions


Install dependencies
 
	npm install
	
	bower install


## How to run the AngularSvgAnimation? ##

Add the module to your Angular app (svgEkd). For example:

	angular.module('app',['svgEkd']);

	configure templateUrl of the svgContainer directive.


## How to use? ##

Add this directive:

	<svg-container name="svg_name_file" class="svg-test"></svg-container>

	The attribute name is the name of the svg file.
	
	Add 'position: absolute' to the directive.

	Add svg.file in the same folder.

to be continued...