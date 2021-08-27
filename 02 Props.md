# Date: 27 / 8 / 2021

## Props

We can make out components reusable using props in react.

### **_Props simply stand for properties._**

We can pass Data by adding an Attribute in the app.js item.

## [What is Props?](https://reactjs.org/docs/components-and-props.html)

Props are a way to pass information into react components.

in JSX props are passed with the attribute syntax,

you will use props all the time And **props simply stand for properties.**

```jsx
// App.js

<ComponentsName title="Hello world" />
```

```jsx
// Components.js

function Components(props) {
  return <h1>{props.title}</h1>;
}
```
