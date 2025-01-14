# React Crash Course 2024

Based on the youtube video by Traversy Media: https://www.youtube.com/watch?v=LDB4uaJ87e0

### React Notes

#### Different types of applications using React - SPA, SSR, SSG

-   **Single Page App** - Load a single HTML file and JavaScript, loads the entire UI including routes
-   Server-Side Rendered - Server sends fully rendered page to client. You can fetch data and load it as well
-   Static Site Generation - The react framework generates static HTML files at build time. These are very fast

---

#### Components

Reusable piece of code that can be reused to build elements on the page
Break down complex UIs
Components can get **props** passed in and can hold their own **state**

#### State

State represents the data that a component manages internally
This could be form input data, fetched data from APIs, UI-related data like if a modal is open/closed
There is also global state, which relates to the app as a hole and not a single component

#### Hooks

Allow us to use state and other React features within functional components

-   useState
-   useEffect
-   useRef
-   useReducer

#### JSX (JavaScript Syntax Extension)

Besides props and state, components have JSX as output, an HTML-like syntax within JavaScript
Like HTML but dynamic

---

### Project creation using Vite

#### Vite

Vite is a super fast front-end toolkit that can be used for all kinds of JS projects including React
It is build on top of ESBuild, which is a very fast JS bundler
Fast development server with hot-reload
Installed with `npm create vite@latest`

---

#### Installing and Running

Install: `npm install`
Run: `npm run dev`
