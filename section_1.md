## Why learn Angular JS over other frameworks like Ember, Backbone, Knockout, etc?

#### Angular requires fewer lines of code than the others to do the same thing. It doesn't use setters and getters. Larger community for Angular, and more modules. It is fast due to being small -- it doesn't require jquery or underscore like other libraries. 

## People have some very strong opinions about Angular. What are 3 common complaints people have about Angular?

#### Directives are considered complex, especially transclusion. 
#### scope hierarchy uses Prototypical inheritance which sucks for people coming from OO languages like Java.
#### Angular expressions used within the view layer can become overly complex and impossible to test in isolation. Also, mistakes are sometimes silently ignored and hard to find.
## Is Angular an MVC framework?
#### yes
## Why did I say jQuery is "sort of" a dependency of Angular? Does it depend on it or not?!
#### angular uses jQuery lite, which is basically a super minimalized version of jQuery that is just enough for Angular to run.
## Read the docs for ng-app. What is it and what does it do?
#### it sets the root element of the page in order to connect Angular. Angular applications cannot be setup inside each other.
#### ngApp is the most common way to bootstrap an application
## What does ng-model do?
#### it has 2 way data binding and can be put inside of form elements
#### it will try to bind a property onto the current scope, if it doesn't exist, it will be created and added to the scope
## What is "dirty checking"?
#### it is the digest of angular, which scans the scopes for changes. 
#### it updates the val without using getters and setters from the model
## What are those {{ }} expressions? Are they Handlebars?
#### they are used to demark expressions, and are evaluated against the scope object. They are not handlebars.
## Explain what 2-way data binding is.
#### 2 way data binding in the ability to have data transfer btwn the view and the model and vice versa.
