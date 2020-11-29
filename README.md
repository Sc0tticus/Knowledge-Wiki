# Knowledge-Wiki

#React
The App function is a React Component.

App Component ->returns-> JSX

Produces JSX and handles user events -> Set of instructions to tell React what content we want to show on the screen.

JSX = set of instructions telling React what we want to show on the screen.

JSX Elements -> Tell React to create a normal HTML element (div, span, h1, table, hr, input) or tell React to show another component (Field, Translate, Languages).

-> Call the App function, get back JSX, and turn it into HTML -> index.js

App Component 
  <div>
    <Field />  -> Call the App function get back JSX  turn it into HTML -> index.js -> ReactDOM.render(<App/>, document.getElementById("root"));
    <Languages />
    <hr />
    <Translate />
  </div>
  
  index.html
  
  <html>
  <head></head>
  <body>
    <div id="root">
          <----- Then take that HTML and put it into the DOM inside this div  < --- > document.getElementById('root')
    </div>
  </body>
  </html>
  
  What's the difference between React and ReactDOM ? Two different libraries:
  
  React: knows how to work with components, Called a 'reconciler'
  ReactDOM: knows how to take instructions on what we want to show and turn it into HTML, Called a 'renderer'
  
  What was all the 'useState' stuff ?
  
  useState = Function for working with React's 'state'system. State is used to keep track of data that changes over time. Used to make Ract update the HTML on the screen.
  
  Syntax for generating a React project: npx create-react-app myapp
  
  npm install -g create-react-app: npm: runs 'npm', install: installs a package, -g: installs the package globally, create-react-app: name of the package being installed.
  
  Versions of JS: ES5 (Supported across all browsers), ES2015 (Almost completely supported), ES2016, ES2017, ES2018 (Poor support).
  
  Babel: Command line tool, can take any version of JS and spit out a newer version.
  
  create-react-app -> Brand new React project -> Webpack, Babel, Dev Server.
  
  A React component is either a function or class --> that produces HTML to show the user (done using JSX) --> and handles feedback from the user (Using Event Handlers). Before JSX gets sent down to a users browser it gets converted in normal JS code.
  
  JSX: Special dialect of JS (its not HTML!). Browsers don't understant JSX code! We write JSX then run tools to turn it into normal JS. Very similar in form and function to HTML with a couple differences.
  
  JSX vs HTML: Adding custom styling to an element uses different syntax, Adding a class to an element uses different syntax (use className instead of class inside a JSX element), JSX can reference JS variables.
  
  HTML: <div style="background-color: red;"><div>
  JSX: <div style={{backgroundColor:'red'}}></div>
  
  Component Nesting: A component can be shown inside of another.
  Component Reusability: We want to make components that can be easily be reused through our application.
  Component Configuration: We should be able to configure a component when it is created.
  
  
  

