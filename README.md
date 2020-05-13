# monsters-rolodex
https://ghewadesumit.github.io/monsters-rolodex/
# React-Course

Learning react

```
npx create-react-app <app-name>
```

- In react you create two types of component

  - Class based component
  - Function based component

# Class based Component-

- Class based component gets access to the state.
- The state is an global object which we can access anywhere inside our class at any point of time.
- To use the state in a class based component.
  - create constructor with super
  - Here super calls the constructor method on the Component class. Doing this gives access to the state.
  - Component also provides us with the **_setState_** method
  - **_setState_** allows us to modify the **_state_** object.  
    **Note:**
- Whenever the state is changed then render function is executed.

- Function based components takes props as argument.

-props : one of the most important about props is that i

    - props has a property named as children

- When we update the setState it doesn't immediatley showcase the updates.
- what setState provides us is with two arugments.
  - First one is to update the state
  - second one is for callback function which can show immediate changes in the state.
  - if we want to see immediate changes in the state outside the setState method then we won't get the exact updated value.  
    this is because setState is asynchronous method.

### Destructuring

- It allows us to pull a property from an object and assign it to a const variable.

```
this.state = {
      monsters: [],
      searchField: ""
    };

render(){
    const {monsters, serachField} = this.state;
}
```

### Function based Components

- It doesn't have access to state because it doesn't have access to constructor which is class method on the Component which is imported from React.
- They don't have the lifecyle methods.
- A Functional component is something which takes props as argument and returns the HTML.

### this keyword

- this reference to the current context in which it is been invoked.

### Arrow Function:

- It binds this to the current context the arrow function is used for.

