# Knowledge-Wiki

#React
The App function is a React Component.

App Component ->returns-> JSX

Produces JSX and handles user events -> Set of instructions to tell React what content we want to show on the screen.

JSX = set of instructions telling React what we want to show on the screen.

JSX Elements -> Tell React to create a normal HTML element (div, span, h1, table, hr, input) or tell React to show another component (Field, Translate, Languages).

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
  
  
  
  
  

-> Call the App function, get back JSX, and turn it into HTML -> index.js
