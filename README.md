# paged-angular-sample
This is a demo for pagination of a grid content. 

Requeriments 

- AngularJS
- UI Bootstrap
- NPM

index.html

Add to index.html the following scripts data-require
- <link data-require="bootstrap-css@2.3.2" data-semver="2.3.2" rel="stylesheet" href="//netdna.bootstrapcdn.com/twitter-bootstrap/2.3.2/css/bootstrap-combined.min.css" />

- <script data-require="angular.js@1.1.5" data-semver="1.1.5" src="http://code.angularjs.org/1.1.5/angular.min.js"></script>

- <script data-require="angular-ui-bootstrap@0.3.0" data-semver="0.3.0" src="http://angular-ui.github.io/bootstrap/ui-bootstrap-tpls-0.3.0.min.js"></script>

Define:
<html>: ng-app = variable
<body>: ng-controller = controller
Create a container for show your information add create the pagination. 

Scripts.js
Initialize the variable containing the contents and ui.bootstrap propeties 
Define the controlles and the features you want for the pager. 
Create a function whit json of contentn or info to show. 
Create the next functions:
numPages: Defines the amount of content tha will be displeyed on the selected page
whatch: Defines and show the content

