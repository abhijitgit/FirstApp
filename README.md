# FirstApp
First angular app. We will understand basics of Angular and how a simple app is developed using Angular.

Angular is a development platform, built on TypeScript. As a platform, Angular includes:
    - A component-based framework for building scalable web applications
    - A collection of well-integrated libraries that cover a wide variety of features, including routing, forms management, client-server communication, and more
    - A suite of developer tools to help you develop, build, test, and update your code
## Essentials
### Components

Components are building blocks of an application. A component includes a TypeScript class with a @Component() decorator, an HTML template, and styles. The @Component() decorator specifies the following Angular-specific information:

    - A CSS selector that defines how the component is used in a template. HTML elements in your template that match this selector become instances of the component.
    - An HTML template that instructs Angular how to render the component
    - An optional set of CSS styles that define the appearance of the template's HTML elements


Angular's component model offers strong encapsulation and an intuitive application structure. Components also make your application painless to unit test and can improve the general readability of your code.

### Template
Every component has an HTML template that declares how that component renders. You define this template either inline or by file path.

Angular adds syntax elements that extend HTML so you can insert dynamic values from your component. Angular automatically updates the rendered DOM when your component's state changes. One application of this feature is inserting dynamic text.

#### Syntax
- Curly braces instruct Angular to interpolate the contents within them.
- Angular uses property binding to set values for properties and attributes of HTML elements and pass values to presentation presentation logic. 
    - Square brackets indicates that you're binding the property or attribute to a value in the component class.
- You can declare event listners to respond to user actions. You declare an event listener by specifying the event name in parentheses.
#### Directives
- You can add features to your templates by using directives.
- Directives are used to perform a variety of tasks, such as dynamically modifying the DOM structure. And create your own custom directives to create great user experiences.
- *ngIf & *ngFor are most common directives used for conditional branching and loops.

Angular's declarative templates let you cleanly separate your application's logic from its presentation. Templates are based on standard HTML, for ease in building, maintaining, and updating.

### Dependency Injections
Dependency injection lets you declare the dependencies of your TypeScript classes without taking care of their instantiation. Instead, Angular handles the instantiation for you. This design pattern lets you write more testable and flexible code.

Proceed to [First Application](./First_App.md) To learn further.