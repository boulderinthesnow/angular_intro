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
## BONUS: Research the $digest loop
#### digest loop has 2 components the watch list and the evalAsync list
#### when we use a ng tag (bind an elements) we add a watch into the watch list
#### when something changes with that property Angular changes that prop all places connected to Angular.
## EXERCISE: With one single expression, prove that the context angular expressions run is not the window object. What is it instead?
#### alert won't run b/c not operating on the window object
## What are Angular expressions? How do they compare to EJS/ERB tags?
#### angular expressions are code snippets that exist inside double curly brace bindings. They can't handle loops, arrays and objects like ERB and EJS

##What happens when you write invalid code in an expression? What type of error do you get?
#### you get regular html of the angular expressions.

##What are Angular filters? Name 4 built-in filters, including one that we haven't used yet.
#### they modify data that is shown on the view without modifying the data in the model. uppercase, lowercase, number, currency, orderBy are examples of filters.
##We'll soon see how to create custom filters. What is a use case for a custom filter?
#### custom filters can be useful when you need to filter the data in a specific way outside of the built in options.


