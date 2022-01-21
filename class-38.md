# Code 401 - Advanced Software Development - Python

## Class 38 - React 2

Block intro

<!-- > An investment in knowledge pays the best interest. –  Benjamin Franklin -->


### React

React - Conditional Rendering ([Article](https://reactjs.org/docs/conditional-rendering.html))

React - Lists & Keys ([Article](https://reactjs.org/docs/lists-and-keys.html))

React - Forms ([Article](https://reactjs.org/docs/forms.html))

React - Lifting State ([Article](https://reactjs.org/docs/lifting-state-up.html))

React - Composition vs Inheritance ([Article](https://reactjs.org/docs/composition-vs-inheritance.html))

Thinking in React ([Article](https://reactjs.org/docs/thinking-in-react.html))

There are a lot of parallels between the class based React and the function based React. The major differences are the function arcitecture and some of the syntax when setting up a new component. It is quite intuitive and similar to class based.

```
function UserGreeting(props) {
  return <h1>Welcome back!</h1>;
}
 <!-- VS -->

 class UserGreeting extends React.Component {
     render(){
         return(
             <h1>Welcome back!</h1>
         )
     }
 }
```

As you can see there is a lot less code to execute roughly the same thing. It reads that the handling of state and passing of props along with other routine tasks are relatively the same. 

I look forward to working with the function based react in Next.js 


### Additional Resources

Hero Icons ([Video](https://www.youtube.com/watch?v=cVa1UiKPJN8))

### Bookmark/Skim

React - Comprehensive Guide ([Article](https://tylermcginnis.com/reactjs-tutorial-a-comprehensive-guide-to-building-apps-with-react/))

Heroicons ([Article](https://heroicons.com/))

### Things I want to know more about

* 

Go [Home](index.md)