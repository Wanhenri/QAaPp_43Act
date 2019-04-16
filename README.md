# QAaPp_43Act
***
## Install
- **Mandatory**
    - Node.js 
    - NPM
    - [Git](https://github.com/Wanhenri/collab_curso_2018_19)
    
    or
    
    - [Subversion](https://help.github.com/en/articles/support-for-subversion-clients)

- **Not mandatory**
    - JavaScript 
    - HTML 
    - CSS 

### Step 1

 [**JSX**](https://reactjs.org/docs/introducing-jsx.html), which stands for *JavaScript* XML, is a syntax extension 
 to *JavaScript* that enables developers  to use XML (and, as such, HTML) to describe the structure of the user 

 ```javascript
 function showRecipe(recipe) {
  if (!recipe) {
    return <p>Recipe not found!</p>;
  }
  return (
    <div>
      <h1>{recipe.title}</h1>
      <p>{recipe.description}</h1>
    </div>
  );
}
```
Show the details of **recipe** if the recipe is avaiable; or a message saying that the recupe was not found.

### Step 2
***
#### React Components 
```
The most important pieces of code.
```
```
For example, when you load a React application, the whole thing will be handled 
by a root component that is usually called App. Then, if this application 
contains a navigation bar, you can bet that this bar is defined inside a 
component called NavBar or similar. Also, if this bar contains a form where you
can input a value to trigger a search, you are probably dealing with another
component that handles this form.
```
This is piece of code that is more important about react components
```
The biggest advantage of using components to define your application is that
this approach lets you encapsulate different parts of your user interface into 
independent, reusable pieces.
```
#### Defining Components in React



-------------------------------
Lembrete:
dir Backend
node src

dir frontend
npm start
