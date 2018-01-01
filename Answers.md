#1. Describe the concept of a "Single Source of Truth" in Redux. Ex. What is the difference between Redux/Application _State_ vs. React/Component _State_?

  The state of the application is held in an object tree, called state. In react each component has its' own state and setSatet has to be called when we want to change its state.After setState being called, then it is being rendered to the screen. 

2. Describe what an _Action_ is/does.

  Action is a payload of information which sends information to the store. Action is just an object and the only information available for the store (notice the data flow). Each action must have a type property that will indicates the type of action being performed. 


3. Describe what a _Reducer_ is/does.

  Reducer will tell the state tree how the application state being changed. Reducer is function which takes to arguments: previous state and action and return the new state. 


4. What does HTTP stand for? What does CRUD stand for? Describe four HTTP methods that can be mapped to the CRUD acronym that we use to interface with APIs/Servers.

  HTTP stands for HyperText Transfer Protocol. 
  CRUD = Create, read, update and delete. 

  HTTP has many methods.

  Put/Post = create
  Get = read
  Put, Post, Patch = Update
  Delete = Delete