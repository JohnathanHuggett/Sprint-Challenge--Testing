<!-- Answers to the Short Answer Essay Questions go here -->

1.  In Mocha, what are the differences between `before`, `after`, `beforeEach`, and `afterEach`? When do they run? What are they used for?

    *   before runs any calls are made
    *   after runs after everything is completed
    *   before each will run before each call is made to the test db
    *   after each will run after each call to the db is made

2.  What is the point of Test Driven Development? What do you personally think about this approach?

    *   test driven approach requires that you write test before you write code. It helps by requiring less debugging
    *   I like the approach when there will be multiple people maintaining the application because it helps to document the app

3.  What is a `spy` in `sinon`? How do we use it to effectively test a `callback`?
    *   spy is a function tha records arguments within a function
    *   we can pass the spy into the callback and simulate the functionally within a test and spy can report data on the function
