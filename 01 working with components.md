# Date: 26 / 8 / 2021

## Module Content

- React Core Syntax & JSX
- Working with Components
- Working With Data

---

## Create React app. (install react app)

first, you install [node.js](https://nodejs.org/en/), then go to your terminal and using this command to create react app.

```jsx
npx create-react-app my-app
cd my-app
npm start
```

# What Are Components?

### ***React is all about "Components"***

Because all user interface, in the end, is made up of components.

Components are reusable building blocks in your user interface. Components are in the end just a combination of HTML (JSX), CSS, JavaScript.

<img src="https://drive.google.com/file/d/1Y52m-X-lwVrkPN2TvWRD8_lVD6zOMcfN/view" alt="Image- if image is not showing click the link" width="250">

<!-- [](https://drive.google.com/file/d/1Y52m-X-lwVrkPN2TvWRD8_lVD6zOMcfN/view) -->

[img-link](https://drive.google.com/file/d/1Y52m-X-lwVrkPN2TvWRD8_lVD6zOMcfN/view)

> ***A Components in React is Just a JavaScript Function, that returns JSX.***

When you build Components make sure the file name starts with Capitalize font.

- Nav.js
- Header.js
- Footer.js

in react to use any component, we need to export.

```js
function ComponentName (){
			return (
			<div>
			<h1>Hello world</h1>
			</div>
	)
}

export default ComponentName;

```

When our component is ready we should import the component in app.js

```jsx
// App.js
import name from "./Components/ComponentName"

function App (){
return(
<ComponentName />
	);
}
export default App;
```

## Introducing JSX

**JSX (JavaScript Syntax Extension and occasionally referred as JavaScript XML), JSX used in React to easily write HTML and JavScript together.**

### One root <div>, <>

- In JSX you should be cover all your code in a **div** tag or <> </>. you have only one root <div>, <>

### ClassName

- in JSX you have to use **className** for making **class** because class is a keyword in JavaScript so in React to make a class for we use className.

### { }

- in JSX you can write **JavaScript** is side **Curly braces** like - **{ 1 + 1 }**

### An element must be close

- in JSX, therefore JSX elements must be closed.

```jsx
<input type="text" />
```