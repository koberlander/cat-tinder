Virtual DOM
 - Related to DOM -- React will update the DOM for you automatically
- DOM is an abstraction - a node-structured tree like object that represents the HTML (can be interacted with by programming languages)
 - Virtual DOM is JS object  that represents DOM (can be reacted with by React developers like me)


Component
 - piece of the web app you are building... a ProgramsContainer or a Comment
  - Class component
    - render/return
    - more complex than functional
    - can contain state
    - can take advantage of the lifecycle
  - Functional component
    - could be function declaration
    - could be a function expression (arrow function or using the 'function' keyword)(which prob means a const)
    - can add state with hooks
  - 'Container' vs 'Presentational' components
    - Container does something - hold state, hold other components, use lifecycles, maybe routes
    - Presentational take props and show them
  - JSX
    - React's syntax for rendering XML/component/JS code quickly
