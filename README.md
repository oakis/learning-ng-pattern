# learning-ng-pattern
School assignment in Angular.js  
Made by Anders Ekman.

This is a simple app made for showing how we can use ng-pattern in Angular.

##The app is built with
* HTML
* CSS
* Angular.js

##To make this work we need to
* bind our input to a model (ng-model="string")
* define our regular expression (ng-pattern="regex")

##How the app works
The input elements have classes attatched to them by Angular.
When the regex is true, it will have the class ng-valid-pattern and when it is false it will have the class ng-invalid-pattern.
The input background will change color depending on what class is currently active on the element.

##Example uses
* We have a form with an input for e-mail and we want it to be a correct e-mail adress. (http://www.regular-expressions.info/email.html)
* Searching for a string in a text/database.
* Highlighting words in a text.
* Replacing words. (https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/replace)

More info on ng-pattern:
https://docs.angularjs.org/api/ng/directive/ngPattern

More info on ng-model:
https://docs.angularjs.org/api/ng/directive/ngModel
