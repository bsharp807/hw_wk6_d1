Answer the following questions:

- Where do we directly access an element from the DOM in our React application?
<br>
<br>
<b>Through the ReactDOM.render function in src/index.js
<br>

- From looking at the code, what do you think might be the difference between the components in the containers and components directories?
<br>
<br>
<b>The container component has multiple components within it, whereas the component components are single responsibility sections

- What is the responsibility of the ReleasesBox component?
<br>
<br>
<b> The ReleasesBox component collects all the opther components and orders them in JSX, it creates the movies as it's state then passes that down via props to MovieList

- What is the responsibility of the MovieList component?
<br>
<br>
<b> MovieList creates the JSX list containing all the movies in the ReleasesBox state that was passed down to it. It does this by creating an array of li elements using the MovieItem component

- What is the responsibility of the MovieItem component?
<br>
<br>
<b> MovieItem is the component which takes the state initially created in the ReleasesBox component, which is then passed to it via the MovieList component, and turns it into the li elements used in the MovieList component.
