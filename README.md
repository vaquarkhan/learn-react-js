# Learn React-js

![Alt Text](https://miro.medium.com/max/3600/1*HSisLuifMO6KbLfPOKtLow.jpeg)

-----------------------------------------------


![Alt Text](https://res.cloudinary.com/practicaldev/image/fetch/s--VtRaY29J--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://thepracticaldev.s3.amazonaws.com/i/fewc8ez6r2e2agah717y.png )

![Alt Text](https://i.redd.it/vezwyo0qq4lz.png )

### Redux:

Redux is a popular JavaScript library for managing the state of your application. It is very common and if you are working with React, chances are — you’ve already heard about it.

### State

state is: it’s like a global object which holds information that you use for various purposes later in the app (e.g. making decisions on which components to render and when, rendering the stored data etc).

### Note :

In Redux You don't actually change the state, you create updated copies of the state. This is probably one of the most important things to understand about Redux's state changing pattern, make sure you commit it to memory.


### Stores:

A store holds the whole state tree of your application. The only way to change the state inside it is to dispatch an action on it.

Store Methods#

- getState() :    getState for accessing the current state of the application
- dispatch(action) : dispatch for changing state via an action
- subscribe(listener) : subscribe for responding to state changes
- replaceReducer(nextReducer)


- https://redux.js.org/api/store



### Reducers:

A reducer is just a function that takes two arguments and returns your app's current state. The two arguments it takes are:

                const reducer = (state, action) => {
                         return state
                  }

### Note :

   reducer function as an argument within createStore(), it will be called a couple of times
  - Once on initialization (this sets our store's initial state) And every time an action is dispatched


### Actions:

Redux actions are JavaScript objects that contain two properties: type and payload. These actions are "dispatched," or used as arguments by the Redux store's dispatch API method


### Create react redux project :

                       npx create-react-app my-app --template redux
                       
 - https://redux.js.org/introduction/getting-started     
 
 
 ###  connect() :
  
  The connect() function connects a React component to a Redux store.It does not modify the component class passed to it; instead, it returns a new, connected component class that wraps the component you passed in.


                    function connect(mapStateToProps?, mapDispatchToProps?, mergeProps?, options?)
                    
                    
 The connect function takes another function as an argument: mapStateToProps. mapStateToProps determines what state from our store we want to pull into our component. In this case, we're specifying to only pull our state's posts property


In addition to our mapStateToProps function, we're also going to add a mapDispatchToProps function which will give us access to our Redux store's dispatch method:


 
----------------------------

- https://www.youtube.com/watch?v=Ke90Tje7VS0


# Redux

- https://youtu.be/1QI-UE3-0PU
- https://egghead.io/courses/getting-started-with-redux
- https://medium.com/fullstack-academy/thunks-in-redux-the-basics-85e538a3fe60
- https://www.youtube.com/watch?v=hMIGj1690QA&list=PLD8nQCAhR3tSSFktby1h8htS6QWTTneEr
- https://chriscourses.com/blog/redux
- https://github.com/james-priest/udacity-nanodegree-react
- https://redux.js.org/tutorials/essentials/part-5-async-logic
- https://www.youtube.com/watch?v=BwuLxPH8IDs

# Type scripts
- https://www.youtube.com/watch?v=BwuLxPH8IDs


### Books :
- https://github.com/vetsinen/react-books
- https://github.com/Tesla1988/ebooks---javascript

