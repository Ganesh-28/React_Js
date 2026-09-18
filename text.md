Welcome to react class

day-1

















17-09-2026

\----------



Reconciliation process in React JS:

\-----------------------------------



\- The reconciliation process in the React JS is the mechanism by which react determines what changes need to be made to the real DOM in response to updates in the virtual DOM.



\- It involves comparing the current virtual DOM representation of a component with its previous representation to identify the differences and efficiently update the Real DOM.





Here's a step-by-step overview of the reconciliation process in React:

\----------------------------------------------------------------------

Component render:

\-----------------

\- When a component's state or props change, React re-renders the component and its children to generate a new virtual DOM representation.



Diffing Algorithm:

\------------------

\- React performs a "diffing" or comparison process between the new virtual DOM tree and the previous virtual DOM tree for the component.

\- It recursively traverses the component tree and compares each node (element) in the tree with it's counterpart in the previous tree.



Identifying Changes:

\--------------------

react identifies three types of changes:

\- added nodes

\- removed nodes

\- updated nodes



Applying changes:

\-----------------

\- react efficiently applies the identified changes to the Real DOM, updating only the affected parts without re-rendering the entire DOM tree.

\- This process involves adding, removing, or updating DOM elements and attributes as necessary to reflect the changes in the UI.





By performing this reconciliation process, react ensures that the UI remains in sync with the application state while minimizing unnecessary updates to the real DOM, leading to better performance and a smoother user experience.











Difference between Real DOM and Virtual DOM:

\----------------------------------------------

|real DOM|virtual DOM|
|-|-|
|represents the actual structure of a web page|A lightweight, in-memory representation|
|created by the browser when a page loads|created and maintained by react for each component|
|insufficient for frequent updates|efficient for frequent updates|
|updating is slow and resource intensive|updating is fast and less resource intensive|

|directly manipulates the browser's display|indirectly manipulates the browser's display through reconciliation|
|-|-|
|requires re-rendering the entire tree for updates|requires minimal updates for changes|
|updating can lead to performance issues|optimizing rendering and improves performance|







6 components of react JS:

\-------------------------



1. JSX

\--------

JSX (Java Script XML) is a syntax extension for JavaScript used in React. It allows you to write HTML - like code in Java Script components.



2\. Components

\-------------

React JS is all about components. React JS application is made up of multiple components and each component has it's own logic and controls.

these components can be reusable.



3\. One Way Data Binding:

\------------------------

react JS designed in such a manner that follows unidirectional data flow or one way data binding.

The benefits of one way data binding give you better control throughout the application.



4\. Virtual DOM:

\---------------

A virtual DOM is a copy of original DOM. Whenever any modification happen in the web application the entire UI is re-rendered in virtual DOM representation.



Then it checks the difference between DOM representation and new DOM only it updates if it needed.



5\. Simplicity:

\--------------

React JS uses Jsx file which makes the application simple and to code as well as understand.



we know that react JS is a component based approach which makes the code reusable as yours need



6\. performance:

\---------------

React JS is known to be a great performer

This feature makes it much better than other frameworks out there today. The reason behind this is that it manages a virtual DOM.





18-9-2026

\---------



Why react is used to create UI when we can create UI using HTML and JS?

\-----------------------------------------------------------------------

HTML:

\----

UI -> HTML -> Pre defined element



Using HTML creating UI is very easy

To create UI html is providing some HTML elements and tags.



Drawbacks:

\----------

we can't reuse the UI.

time consuming to create UI.



Java Script:

\------------

UI -> JS -> pre defined function -> DOM element -> DOM -> Screen



JS we can create UI dynamically.

we can reuse UI.



Drawbacks:

\----------

Creating UI is very Complex process.

Time consuming





React JS:

\---------

UI -> React -> predefined function -> React element -> DOM -> Screen







|HTML|JS|React|
|-|-|-|
|Creating the UI is easy|We can reuse the UI|Creating UI is very easy like HTML|
|We cannot reuse the UI|Creating the UI is complex process|We can reuse the UI like JS|















Creating a React Project:

\----------------------------

create one folder and open it in VS Code





commands:

\---------



* npm create vite@latest
* Ok to proceed? (y) y
* ◇  Project name:
* │  firstproject
* ◇  Select a framework:
* │  React
* ◇  Select a variant:
* │  JavaScript + React Compiler
* ◇  Which linter to use?
* │  ESLint
* │
* ◇  Install with npm and start now?      ## for automatic server running, choose 'no' for manual server start
* │  Yes







Ctrl+c for stopping the server.

