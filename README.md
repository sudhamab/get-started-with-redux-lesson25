# get-started-with-redux-lesson25

### What is in this repo? 
This is based on the lessons from https://egghead.io/series/getting-started-with-redux, lesson 23,
so one can look at how the running code looks like. It will get more complicated with subsequent 
lessons


### IMPORTANT CAVEAT 
To quote Dan, 
"Context is a powerful feature but it contradicts the React philosophy of explicit data flow. 
The context allows global variables ( e.g store ) across the component tree but global variables
are usually a bad idea but unless you are using it for dependency injection where as in this 
case, you want to make a single variable accessible across the components, you shouldn't use 
contexts. 

Finally, the context api is not stable in React. It was changed before and is likely to be 
changed again so try not to rely on it too much"

### Motivation 

I was finding it a bit hard to remember every single detail of each decision Dan was taking 
as he walks through the tutorials, which by the way are brilliant. 

So after much trial and error, I realized I have to master these tutorials by 
writing the code the way it is being explained. 

I wanted to put document step by step how the code evolved to get more comfortable with thinking in Redux.

So I decided to just follow the videos and create working versions of the entire code from Dan's lessons,
but backtracked from the 17th lesson onwards. 


## Quickstart

```
npm install
npm start 
```

### Whats the goal of this lesson? 

In this lesson, Dan uses a Provider so that we don't have to pass down the store as a prop
at each level of the component tree in order for child components to have access to the store.

### Different versions of the index.js files 

In this repo, you will find a reference to the index.js file from the previous lesson so you can 
easily diff it to see how the code is changing, in case you want to come back to it.


### Comments in the code.

Have also added some comments of my own observations about the coding style as well as based on the 
lecture videos. 
