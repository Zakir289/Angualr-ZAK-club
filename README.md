# AngularJS

**AngularJS** is the JavaScript MVC with awesome features to build rich client side MVC. It acts as a glue between HTML and JavaScript objects, i.e any update on your view will immediately effect without any DOM manipulation or event bindings.

#### Components:

- **The Model :**
The model is responsible for managing application data. It responds to the request from view and to the instructions from controller to update itself.

- **The View :**
Presenting data in particular format based on the controller’s decision to present the data.

- **The Controller :**
Based on the input, Controller performs interactions with data model objects. Controller receives input, validates it and then performs business operations that modifies the state of the model.

#### AngularJS directives:

- **ng-app :** Initializes the application when web page containing Angular JS Application is loaded.

- **ng-init :** stores the values to the variables used in the application.

- **ng-model :** defines model/variable to be used in the application.

- **ng-repeat :** repeat Html elements in the collections.

#### Features of AnuglarJS:

- **Data-binding :** It is the automatic synchronization of data between model and view components.
- **Scope :**These are objects that refer to the model. They act as a glue between controller and view.
- **Controller:**These are Javascript functions that are bound to a particular scope.
- **Services:** AngularJS come with several built-in services for example $http to make a XMLHttpRequests. These are singleton objects which are instantiated only once in app.

- **Filters:** These select a subset of items from an array and returns a new array.
- **Directives:** Directives are markers on DOM elements (such as elements, attributes, css, and more). These can be used to create custom HTML tags that serve as new, custom widgets. AngularJS has built-in directives (ngBind, ngModel...)
- **Templates:** These are the rendered view with information from the controller and model. These can be a single file (like index.html) or multiple views in one page using "partials".
- **Routing:** It is concept of switching views.
- **Deep Linking:** Deep linking allows you to encode the state of application in the URL so that it can be bookmarked. The application can then be restored from the URL to the same state.
- **Dependency Injection:** AngularJS has a built-in dependency injection subsystem that helps the developer by making the application easier to develop, understand, and test.

#### Few Disadvantages of AngularJS to discuss:
0. Security issue : It’s recommended to keep server side authentication as angular is like javascript only framework.
1. considering usecase like user disabling javascript on the page, then only the basic page will be shown. I don’t think that particular use case need to be considered.
