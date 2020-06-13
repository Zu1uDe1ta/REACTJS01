# REACTJS 

WHAT IS REACT? 
- React is a JavaScript library for building fast and interactive user interfaces for the web as well as mobile applications 
- It is an open-source, reusable component-based front-end library
- In a model view controller architecture. React is the 'View' which is responsible for how the app looks and feels
- Instagram components: 
	- Search Component
	- Profile Description Component
	- Stories Component
	- Post List Component 
- React divides the UI into multiple components, which makes the code easier to debug, and each component has its own property and function. 

The Model View Controller (MVC) design pattern specifies that an application consist of a data model, presentation information, and control information. The pattern requires that each of these be separated into different objects. MVC is more of an architectural pattern, but not for complete application.



WHY REACT?
- Easy creation of dynamic web applications 
- Performance enhancements
- Reusable components 
- Unidirectional data flow
- Small learning curve
- Can be used for mobile apps 
(extension: ReactNative developing mobile apps that are cross compatible)
- dedicated tools for easy debugging

Cross-platform mobile development is the creation of software applications that are compatible with multiple mobile operating systems. Originally, the complexity of developing mobile apps was compounded by the difficulty of building out a backend that worked across multiple platforms.

FEATURES OF REACT
- JSX - JavaScript Syntax Extension
	- JSX is a syntax extension to JavaScript. It is used with React to describe what the User Interface should look like
	- By using JSX, you can write HTML structures in the same file that contains JavaScript code
	- JSX helps in making the code easier to understand and debug as it avoids usage of JS DOM structures which are rather complex 
	- JSX = JS + HTML
		- ex: ``` const simple = <h1>Hello World!</h1>;```
			Javascript ```const simple =```
			HTML ```<h1>Hello World!</h1>```
			JavaScript ```;``` (note that usage of ";" is not mandatory but is consdiered as a good practice)

HTML: Hypertext Markup Language, a standardized system for tagging text files to achieve font, color, graphic, and hyperlink effects on World Wide Web pages.

XML: a metalanguage which allows users to define their own customized markup languages, especially in order to display documents on the Internet.

- Virtual DOM (Document Object Model)
	- DOM treats an XML or HTML document as a treee structure in which each node is an object representing a part of the document 
	- React creates a virtual DOM that is the exact copy of the real DOM
	- React keeps a ligthweight representation of the Real DOM in the memory, and that is known as the Virtual DOM
	- Manipulating Real DOM is much slower than manipulating the Virtual DOM, because nothing gets drawn onscreen
	- When the state of an object changes, Virtual DOM changes only that object in the real DOM instead of updating all the objects

- Performance 

- One Way Data 
	- React's one-way data binding keeps everythin modular and fast
	- A unidirectional data flow means that when designing a React app you often nest child components within parent components

- Extensions
	- React goes beyond simple UI and has many extensions for complete application architecture support 
	- It provides server-side rendering; rather than in the browser
	- Supports mobile app development 
		- React Native 
			- lets you build mobile apps using only JavaScript
			- a React Native is a REAL mobile app and NOT just a web app running on mobile
	- Extended with Flux and Redux, among others
		- Flux
			- is the application architeture that /facebook uses for building web applications
			- implements unidirectional flow which makes it easeier to deduce what's going on
			- Action>>Dispatcher>>Store>>View

- Debugging 
	- React applications are extremely easy to test due to a large developer community
	- Facebook even provides a small browser extension that makes React debuggin faster and easier

- Components, State, & Props
	- Components
		- are the building blocks of any React application and a sinlbe app usually consists of multiple components
	- is essentially a piece of the User Interfae. It is like a function that returns HTML elements
	- it splits the User Interface into independent, reusable pieces that can be processed separately
		- ex.: a components is implement as a JavaScript class having some state and a render method
			- State is the data that we want the component to render
			- Render method is repsonsible for how the User Interface looks and feels to the user
	- State
		- State of a component is an object that holds some data
		- This data influences the output of a component
	- Props
		- is short for properties, that allow us to pass arguments or data to components 
		- are passed to components in the way similar to that of HTML-tag attributes

REACT PRE-REQUISITES 
- You should be familiar with programming concepts like functions, objects, arrays, and to a lesser extent classes
- You should ahve a basi knowledge of JavaScript
- You should have a some familiarity with HTML

INDDUSTRY TRENDS
- React developers earn more money when compared to other web development technologies
- React is gaining popularity and is being adopted by a lot of big companies and startups alike
	- Facebook, Instagram, Netflix, The New York Times, Dropbox
