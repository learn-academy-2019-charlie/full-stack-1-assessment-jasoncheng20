# Full Stack 1 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. What is Enzyme and what are some of the methods that it provides?

Enzyme is a testing suite for React apps, more specifically testing components. One method that is especially useful is mount, which simulates a full render, which allows for testing of all parts of a component's lifecycle.

#### 2. What is the difference between dynamic and a static routes?

Static routes are the basic routes, and it defines a pathway to a certain view via a change in url. These routes are initialized and declared along with the app initialization process.
A dynamic route can include variables, and they pass those variables to the component view that the pathway leads to: they dynamic routes are able to take in variables because they are set up as the app renders.

#### 3. What is a JSON API?

JSON API: an API is a way for applications to send information to each other. JSON is a notation to send or request information. So, JSON API is using this specific JavaScript Object Notation to build APIs - it is a standard way of allowing apps to communicate - to send info, respond, request, etc.

#### 4. What is a migration and why would you use one?

A migration is a version of a database schema. They are used to edit schema: one can use a migration to create a table, edit a table by adding columns, changing column names, deleting columns.

#### 5. Explain how to set up a route in React.

We learned how to set up routes in React with react-router. Steps to set up a route include importing BrowserRouter, Route from react-router. Then, in the return in the render, set a route up with <Route path="/desiredpathinurl/" component = {ComponentToGoTo} />

#### 6. When would you use a generate resource over a generate controller?

Generate resource would create many items - including a set of routes, a model, and a view that are pre-set. I would use generate resource to start with, and adjust the different routes, etc. as I go, if I know that I'm trying to develop a full-stack app with all of those parts (routes, views, etc.)
To me, generate resource is analogous using a pre-made cake mix, whereas generating a controller is like initializing the process of making the cake more from scratch.

#### 7. Explain the difference between a controller spec and a request spec.

Controller specs allows you to simulate a single HTTP request and test for the expected outcomes. Request specs are more useful in a general sense - they allow you to test the entire stack with multiple requests. According to the article I read, controller specs test each individual action (how each step is performed), while request specs test the result (what the application does).

#### 8. Describe the React component lifecycle. What are some of the lifecycle methods?

The three lifecycle stages in React are mounting, updating and unmounting.
The mounting methods: constructor(), render(), and componentDidMount()
The updating methods: render() and componentDidUpdate()
The unmounting methods: componentWillUnmount()

#### 9. At this point in the program, what technologies/languages do you find yourself gravitating to?
I gravitate towards Javascript and React. I still feel more familiar and more practiced with these technologies because we've had more in-class practice with them. I would like to become more familiar with Ruby and Rails, as well as with testing.