
# State and Props

**Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?**

The Render happens first.

**What is the very first thing to happen in the lifecycle of React?**

Mounting
When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase. Constructor, static getDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount all occur in this order during mounting.

**Put the following things in the order that they happen:** componentDidMount, render, constructor, componentWillUnmount, React Updates

1. constructor
1. render
1. React Updates
1. componentDidMount
1. componentWillUnmount

**What does componentDidMount do?**

This method is a good place to set up any subscriptions.

Reference [**React: Component Lifecycle Events**](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

---

## React State vs Props

**What types of things can you pass in the props?**
counter component  

**What is the big difference between props and state?**

props you pass into the component and must be update outside the component
state is handel inside that component and you can update it inside the component

**When do we re-render our application?**
It happens with state, we usually re-render an application based on something that the user have done.

**What are some examples of things that we could store in state?**

titles and sub titles

Reference [**Web Dev Simplified-React State vs Props**](https://www.youtube.com/watch?v=IYvD9oBCuJI)

---

## Things I want to know more about

I would like to know more about states and props.
