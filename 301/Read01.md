
the logic behind components is a way to divide the problem into [sub problem] - > multi functions or components , which gives higher abstraction more readable code , also more reusable code. And these advantages makes it more better than the traditional object-oriented approaches

**Views of a Component:**

*Object-oriented view*
a class (parent component that may inherit it's features to some other sub classes (child component)
  

*Conventional view*
a functional style which gives high abstraction , the implementation is in it's own place and can be invoked in the parent component

*Process-related view*
instead of creating elements from scratch we can create a component and call it.[Reusability]

**Characteristics of Components**
Reusability − "usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task."

Replaceable − freely substituted with other similar components.

Not context specific − designed to operate in different environments and contexts.

Extensible − it can be extended from existing components to provide new behavior.

Encapsulated − A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.

Independent − Components are designed to have minimal dependencies on other components.

props is an Object special keyword in React, that is designed to send data from one component to another, ex(adding props object in the super method constructor to make props available across the components) one way from parent component to Childs

Additional Resources:
[https://overreacted.io/why-do-we-write-super-props/](https://overreacted.io/why-do-we-write-super-props/)