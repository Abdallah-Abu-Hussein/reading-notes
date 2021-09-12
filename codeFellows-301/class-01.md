# Component-Based Architecture

A component architecture is a type of application architecture composed of independent, modular, and reusable building blocks called components. When designing an app following component-based architecture principles, developers combine, reuse, and version these objects, saving a lot of time from building every inch of an app from scratch.

# what is a Component ?

A component is a reusable object that speeds up application creation and delivery and provides additional features. It turns code for common use cases, such as accessing a device’s GPS or calling an employee directory, into a module. Developers can easily add this module to applications so they don’t have to repeat themselves. They don’t need to write custom code for a common feature or capability that numerous applications require, significantly reducing time and effort.

# What are the charactistics of a component?
 
* **Reusability** − Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task.

* **Replaceable** − Components may be freely substituted with other similar components.

* **Not context specific** − Components are designed to operate in different environments and contexts.

* **Extensible** − A component can be extended from existing components to provide new behavior.

* **Encapsulated** − A A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.

* **Independent** − Components are designed to have minimal dependencies on other components.

<br>

# What are the advantages of using component based architecture?

* **Ease of deployment** − As new compatible versions become available, it is easier to replace existing versions with no impact on the other components or the system as a whole.

* **Reduced cost** − The use of third-party components allows you to spread the cost of development and maintenance.

* **Ease of development** − Components implement well-known interfaces to provide defined functionality, allowing development without impacting other parts of the system.

* **Reusable** − The use of reusable components means that they can be used to spread the development and maintenance cost across several applications or systems.

* **Reliability** − The overall system reliability increases since the reliability of each individual component enhances the reliability of the whole system via reuse.

* **System maintenance and evolution** − Easy to change and update the implementation without affecting the rest of the system.

* **Independent** − Independency and flexible connectivity of components. Independent development of components by different group in parallel. Productivity for the software development and future software development.

# What is Props and How to Use it in React:

# What is props short for?
“Props” is a special keyword in React, which stands for properties and is being used for passing data from one component to another.
But the important part here is that data with props are being passed in a uni-directional flow. (one way from parent to child)
Furthermore, props data is read-only, which means that data coming from the parent should not be changed by child components.

# How are props used in React?

 1. Define an attribute and its value(data)

2. Pass it to child component(s) by using Props
 
3. Render the Props Data

# What is the flow of props?
The flow of the props is a uni-directional flow. (one way from parent to child)

