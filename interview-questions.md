# ASSESSMENT 2: Interview Practice Questions

Answer the following questions.

First, without external resources. Challenge yourself to answer from memory as if you were in a job interview.

Then, research the question to expand on your answer. Even if you feel you have answered the question completely, there is always something more to learn. Write your researched answer in your OWN WORDS.

1. Why would you use the method super()?

  Your answer: placed withing the constructor, super() allows a programmer to call on the parent constructor's to access the parent's properties and methods

  Researched answer: super() refers to the parent class. It is used to call the constructor of the parent class and acc it's properties and methods. It allows programmers to avoid duplication of constructor parts that are common between two classes. 



2. What is a virtual DOM?

  Your answer: The virtual Dom is a lightweight representation of a DOM object. It allows faster manipulation and editing of the DOM when rendering JSX elements. 

  Researched answer: DOM manipulation in React is slow; therefore, we require the virtual DOM to make fast and efficient changes to the DOM. A virtual DOM has the same properties as the real DOM object, but lacks the power to change things directly. It essentially acts as the editing blueprint.



3. When creating a basic (stateless) class component in React, what are the necessary elements needed to display "Hello World" in the browser?

  Your answer: The necessary elements are a function in which we render elements using JSX and a return to output those elements.

  Researched answer: In App.js, we need the function of the app, render for the app, and a return for the the app. JSX dividers are necessary to tell the code that we are leaving JSX and going into writing JS. "Hello World" is displayed in the header tags.



4. What is JSX?

  Your answer: JSX is the sibling of JS that allows us to render eui elements and interactive elements in react applications

  Researched answer: JSX allows rendering logic to be coupled with UI logic. It is the syntax extension to javascript that produces React "elements" within the same file allowing technologies to co-exist.



5. What is state in React?

  Your answer: State is what allows us to indicate a change to a property in the react application.

  Researched answer: State is a rendered value where you store property values that belongs to the component. When the state object changes, the component re-renders.



6. STRETCH: What is hoisting in JavaScript?

  Your answer: Hoisting is when JS will put function declerations into memory allowing variables to be initialized and used before they are declared.

  Researched answer: It is JavaScript's default behavior of moving all declerations to the top of the current script or the current function. Variables, such as const and let, are hoisted to the top, but nor initialized.



## Looking Ahead: Terms for Next Week

Research and define the following terms to the best of your ability.

- React lifecycle methods - lifecycle in which you can monitor and manipulate during its three main phases. Mounting, updating, and unmounting. Mounting refers to putting elements in the DOM.Updating is the next phase in which the component is updated. a component is changed whenever there is a change in the components state or props. Unmounting is the last phase in which a component is removed from the DOM aka unmounted. 

- React props - function like arguments in javascript and attributes in HTML. The component receives the argument as a props object. Furthermore, they act as a way to pass data from one compenent to another. They are passed to the constructor ans also to the React.Component via the super() method. 

- event.preventDefault() - Tells the user agent that if the event does not get explicitly handled, its default action should not be taken as it normally would be. It is non-cancellable

- DOM events - HTML DOM allows javascript to react to HTML events. A JavaScript can be executed when an event occurs, like when a user clicks on an HTML element. To execute code when a user clicks on an element, add JavaScript code to an HTML event attribute.

- MVC - software design pattern commonly used for developing UI. Consists of the model, view, and controller. Model is the dynamic data structure, view is the representation of inforation, and controller accepts input converting it to commands for the model or view.
User uses controller manipulating the model, updating the view, and the user sees the output.
