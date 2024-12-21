# HTML

## 1. HTML Structure
- Basic HTML Document Structure
  - `<!DOCTYPE html>`
  - `<html>`, `<head>`, `<body>`
- The role of HTML in web development

## 2. HTML Tags and Elements
- Basic Syntax: Opening and Closing Tags
- Common Tags: `<h1>`, `<p>`, `<a>`, `<img>`, `<ul>`, `<li>`

## 3. Text Formatting
- Headings: `<h1>` to `<h6>`
- Paragraph: `<p>`
- Bold: `<b>`, `<strong>`
- Italic: `<i>`, `<em>`
- Line Break: `<br>`

## 4. Links
- Creating Links with `<a>` Tag
  - `href` Attribute
  - Opening Links in a New Tab (`target="_blank"`)

## 5. Images
- Inserting Images with `<img>` Tag
  - `src` and `alt` Attributes
  - Image Size with `width` and `height`

## 6. Lists
- Unordered Lists: `<ul>`, `<li>`
- Ordered Lists: `<ol>`, `<li>`

## 7. HTML Forms
- Form Structure: `<form>`
- Input Fields: `<input>`, `<textarea>`, `<button>`, `<select>`
- Submit Button: `<input type="submit">`

## 8. HTML Attributes
- Common Attributes: `id`, `class`, `style`, `title`
- `alt` Attribute for Images
- `action` and `method` in Forms

## 9. Comments
- Writing Comments in HTML: `<!-- Comment -->`

## 10. HTML5 Features
- Semantic Tags: `<header>`, `<footer>`, `<article>`, `<section>`
- Video and Audio Tags: `<video>`, `<audio>`

## 11. HTML Block vs. Inline Elements
- Block-level Elements: `<div>`, `<p>`, `<ul>`
- Inline Elements: `<span>`, `<a>`, `<strong>`

## 12. Document Metadata
- Setting Document Title: `<title>`
- Meta Tags: `<meta charset="UTF-8">`, `<meta name="viewport">`


# CSS

## 1. CSS Basics
- What is CSS?
- How to link CSS to HTML (`<link>` tag)
- Inline CSS, Internal CSS, External CSS

## 2. CSS Selectors
- Universal Selector: `*`
- Element Selector: `p`, `h1`, etc.
- Class Selector: `.className`
- ID Selector: `#idName`
- Attribute Selector: `[type="text"]`
- Grouping Selectors

## 3. CSS Properties
- Color: `color`, `background-color`
- Font: `font-family`, `font-size`, `font-weight`, `font-style`
- Text: `text-align`, `text-transform`, `line-height`, `letter-spacing`
- Box Model: `margin`, `padding`, `border`, `width`, `height`

## 4. CSS Layout
- Display Property: `block`, `inline`, `inline-block`
- Positioning: `static`, `relative`, `absolute`, `fixed`, `sticky`
- Box Sizing: `box-sizing`
- Flexbox Basics: `display: flex`, `justify-content`, `align-items`, `flex-direction`
- CSS Grid Basics: `display: grid`, `grid-template-columns`, `grid-template-rows`

## 5. CSS Colors and Backgrounds
- Using Color Names, Hex, RGB, RGBA, HSL
- Background Images and Positioning: `background-image`, `background-position`, `background-repeat`

## 6. CSS Borders and Shadows
- Border: `border-width`, `border-style`, `border-color`
- Border Radius: `border-radius`
- Box Shadow: `box-shadow`

## 7. CSS Styling Links
- Styling Link States: `a:hover`, `a:active`, `a:visited`, `a:focus`
- Text Decoration: `text-decoration`

## 8. CSS Transitions and Animations
- Transitions: `transition-property`, `transition-duration`, `transition-timing-function`
- Animations: `@keyframes`, `animation-name`, `animation-duration`

## 9. Responsive Design
- Media Queries: `@media`
- Mobile-First Design Approach
- Viewport Meta Tag for Responsive Design

## 10. CSS Pseudo-classes and Pseudo-elements
- Pseudo-classes: `:hover`, `:focus`, `:nth-child()`, `:first-child`, `:last-child`
- Pseudo-elements: `::before`, `::after`

## 11. CSS Variables
- Defining Variables: `--variable-name: value`
- Using Variables: `var(--variable-name)`

## 12. CSS Flexbox and Grid (Advanced Layouts)
- Flexbox: `flex`, `align-self`, `flex-wrap`
- CSS Grid: `grid-gap`, `grid-template-areas`
---

# Git and GitHub

## 1. Introduction to Git and GitHub
- What is Git? (Version control)
- What is GitHub? (Cloud-based Git repository hosting)
- Basic Git workflow

## 2. Installing Git
- Installing Git on Windows, Mac, and Linux
- Configuring Git: `git config --global user.name` and `git config --global user.email`

## 3. Basic Git Commands
- `git init`: Initialize a Git repository
- `git clone`: Clone a remote repository
- `git status`: Check the status of your working directory
- `git add`: Add changes to the staging area
- `git commit`: Commit changes with a message
- `git log`: View commit history
- `git diff`: See differences between changes
- `git reset`: Unstage changes or reset to a previous commit

## 4. Working with Branches
- `git branch`: List, create, and delete branches
- `git checkout`: Switch branches
- `git merge`: Merge branches
- `git rebase`: Rebase branches (optional for beginners)

## 5. Remote Repositories
- `git remote`: Add, view, and remove remote repositories
- `git push`: Push local commits to a remote repository
- `git pull`: Fetch and merge changes from a remote repository
- `git fetch`: Fetch changes from a remote repository without merging

## 6. GitHub Basics
- Creating a GitHub account and repository
- Pushing a local repository to GitHub
- Cloning a GitHub repository to your local machine
- Forking a repository and creating pull requests

## 7. Working with Commits
- Writing good commit messages
- Amending commits: `git commit --amend`
- Viewing commit history: `git log` and `git log --oneline`

## 8. Handling Merge Conflicts
- What is a merge conflict?
- Resolving merge conflicts manually
- Using Git tools to help resolve conflicts

## 9. Pull Requests (GitHub)
- Creating a pull request on GitHub
- Reviewing pull requests
- Merging pull requests on GitHub
- Resolving conflicts in pull requests

## 10. Git Staging Area and the Index
- Understanding the staging area
- Staging files selectively: `git add <file>` and `git add .`
- Unstaging changes: `git reset <file>`

## 11. Git Ignore
- Creating a `.gitignore` file to exclude files from version control
- Common `.gitignore` patterns

## 12. Git Collaboration Workflow
- Forking repositories and contributing to open-source projects
- Working with multiple collaborators using branches
- Keeping your fork up-to-date with the upstream repository

---


# JAVASCRIPT

## 1. Introduction to JavaScript
- What is JavaScript?
- How to include JavaScript in HTML: `<script>` tag
- JavaScript Syntax and Structure

## 2. Variables and Data Types
- Declaring Variables: `var`, `let`, `const`
- Primitive Data Types: `string`, `number`, `boolean`, `null`, `undefined`, `symbol`
- Reference Data Types: `object`, `array`, `function`

## 3. Operators
- Arithmetic Operators: `+`, `-`, `*`, `/`, `%`, `++`, `--`
- Assignment Operators: `=`, `+=`, `-=`, `*=`, `/=`
- Comparison Operators: `==`, `===`, `!=`, `!==`, `>`, `<`, `>=`, `<=`
- Logical Operators: `&&`, `||`, `!`
- Ternary Operator: `condition ? expr1 : expr2`

## 4. Control Flow
- Conditional Statements: `if`, `else`, `else if`, `switch`
- Loops: `for`, `while`, `do...while`
- `break` and `continue` Statements

## 5. Functions
- Function Declaration: `function name() { }`
- Function Expression
- Arrow Functions: `const func = () => { }`
- Parameters and Return Values
- Function Scope and Closures

## 6. Arrays
- Creating Arrays: `let arr = [1, 2, 3]`
- Array Methods: `.push()`, `.pop()`, `.shift()`, `.unshift()`, `.slice()`, `.splice()`
- Iterating through Arrays: `for`, `forEach()`, `map()`, `filter()`
- Accessing Array Elements

## 7. Objects
- Creating Objects: `let person = { name: "John", age: 30 }`
- Accessing and Modifying Object Properties: `obj.property` or `obj["property"]`
- Object Methods
- Iterating through Objects: `for...in` loop

## 8. DOM Manipulation
- Selecting DOM Elements: `document.getElementById()`, `document.querySelector()`
- Modifying HTML Content: `.innerHTML`, `.textContent`
- Modifying Styles: `.style.property`
- Event Handling: `.addEventListener()`
- Creating and Removing Elements: `createElement()`, `removeChild()`

## 9. Events
- Event Types: `click`, `submit`, `keydown`, `change`, etc.
- Event Listeners: `addEventListener()`
- Event Object and Event Propagation (bubbling and capturing)

## 10. Error Handling
- `try...catch` Statements
- `throw` Statement
- `finally` Block

## 11. JSON (JavaScript Object Notation)
- What is JSON?
- Parsing JSON: `JSON.parse()`
- Stringifying JSON: `JSON.stringify()`

## 12. ES6 Features (Modern JavaScript)
- Template Literals: `` `Hello, ${name}` ``
- Destructuring Assignment
- Spread Operator: `...`
- Default Parameters
- Classes and Objects in ES6
- Promises and Async/Await (Intro)

## 13. Basic Debugging
- Using `console.log()` for Debugging
- Inspecting Variables and Functions in the Browser Console
---

# REACT

## 1. Introduction to React
- What is React?
- Benefits of React (Component-based, Virtual DOM)
- Setting up a React project using Create React App or other tools

## 2. JSX (JavaScript XML)
- What is JSX?
- Writing JSX code inside JavaScript
- JSX expressions and curly braces
- Nesting HTML elements in JSX

## 3. React Components
- Functional Components
- Class Components (basic knowledge)
- Returning JSX from components
- Props in components

## 4. Props
- Passing data to components using `props`
- Accessing `props` in functional and class components
- Default props and prop types

## 5. State in React
- Introduction to `useState` hook
- Managing state in functional components
- Updating state using `setState` (in class components)
- Handling state in forms and inputs

## 6. Event Handling
- Handling events like `onClick`, `onChange`, `onSubmit`
- Binding event handlers in class components
- Arrow functions in event handlers (functional components)

## 7. Conditional Rendering
- Rendering components conditionally using `if` statements
- Ternary operators for conditional rendering
- Logical AND (`&&`) for conditional rendering

## 8. Lists and Keys
- Rendering lists using `.map()`
- Using `key` prop to help React identify list items
- Avoiding common mistakes with keys

## 9. React Hooks (Functional Components)
- Introduction to hooks
- `useState`: Managing state in functional components
- `useEffect`: Running side effects (like fetching data)
- Cleaning up side effects with `useEffect`

## 10. Forms and Controlled Components
- Creating controlled components
- Managing form inputs with state
- Handling form submission

## 11. Component Lifecycle (Class Components)
- Lifecycle methods in class components: `componentDidMount`, `componentDidUpdate`, `componentWillUnmount`
- Using hooks for lifecycle events (`useEffect`)

## 12. React Router (Intro)
- Basic routing using `react-router-dom`
- Defining routes with `<Route>` and `<Switch>`
- Navigation with `<Link>` and programmatically with `history`

## 13. Basic Context API (Optional but useful)
- Using Context for passing data through the component tree
- `React.createContext()` and `useContext` for sharing state

## 14. Error Boundaries (Optional)
- Handling errors in React components using `componentDidCatch`
- Error boundaries for catching JavaScript errors in a component tree

---

# Next.js

## 1. Introduction to Next.js
- What is Next.js? (React Framework for Server-side Rendering and Static Site Generation)
- Benefits of Next.js (SSR, SSG, API routes, built-in routing)
- How Next.js enhances React applications

## 2. Setting Up Next.js
- Installing Next.js using `npx create-next-app`
- Running the development server (`npm run dev`)
- File-based routing in Next.js

## 3. Pages and Routing
- Creating pages with `.js` or `.tsx` files inside the `pages` folder
- Dynamic routing using file-based routes (e.g., `[id].js`)
- Nested routes and linking between pages using `<Link />` component

## 4. Static Site Generation (SSG)
- What is Static Site Generation (SSG)?
- Using `getStaticProps` for fetching data at build time
- Generating static pages with `getStaticPaths` for dynamic routes

## 5. Server-Side Rendering (SSR)
- What is Server-Side Rendering (SSR)?
- Using `getServerSideProps` for fetching data on each request

## 6. API Routes
- Creating API routes in the `pages/api` folder
- Making API requests within the app
- Returning JSON responses from API routes

## 7. Client-Side Rendering (CSR) and useEffect
- Client-side rendering with React hooks like `useEffect`
- Fetching data client-side (inside `useEffect`) in Next.js

## 8. CSS and Styling in Next.js
- Adding global CSS in `pages/_app.js`
- Scoped CSS using CSS Modules
- Using styled-components or other CSS-in-JS solutions

## 9. Image Optimization with Next.js
- Using the `next/image` component for optimized images
- Benefits of automatic image optimization in Next.js

## 10. Environment Variables
- Setting up environment variables in Next.js (`.env.local`)
- Using `process.env` to access environment variables

## 11. Deployment of Next.js App
- Deploying to Vercel (Next.js’ official platform)
- Deploying to other platforms (Netlify, AWS, etc.)
- Optimizing performance during deployment

## 12. Static File Serving
- Using the `public` folder to serve static assets (e.g., images, fonts)
- Accessing static assets in Next.js with `/public/`

## 13. Next.js Development Tools
- Using Next.js development tools (e.g., Fast Refresh, Error Overlay)
- Debugging in Next.js
- Using Next.js with TypeScript (Optional for beginners)

---

# Docker

## 1. Introduction to Docker
- What is Docker? (Containerization technology)
- Difference between Virtual Machines and Containers
- Benefits of Docker (portability, isolation, scalability)

## 2. Installing Docker
- How to install Docker on Windows, Mac, and Linux
- Verifying installation with `docker --version`
- Docker Desktop vs. Docker Engine

## 3. Docker Architecture
- Docker Daemon (dockerd)
- Docker CLI (docker command-line interface)
- Docker Images, Containers, and Registries
- Docker Hub: Public image repository

## 4. Docker Images
- What is a Docker image?
- Pulling images from Docker Hub (`docker pull <image-name>`)
- Creating custom Docker images using a `Dockerfile`
- Inspecting images with `docker images`

## 5. Docker Containers
- What is a Docker container?
- Running containers: `docker run <image-name>`
- Stopping containers: `docker stop <container-id>`
- Starting and restarting containers: `docker start`, `docker restart`
- Removing containers: `docker rm <container-id>`

## 6. Dockerfile Basics
- What is a Dockerfile? (Automated image build process)
- Basic Dockerfile commands: `FROM`, `RUN`, `COPY`, `CMD`, `EXPOSE`
- Building a Docker image using `docker build -t <image-name> .`

## 7. Docker Volumes
- What are Docker volumes?
- Creating and using volumes to persist data (`docker volume create`)
- Mounting volumes to containers: `docker run -v`
- Managing volumes: `docker volume ls`, `docker volume rm`

## 8. Docker Networks
- What are Docker networks?
- Creating custom networks (`docker network create`)
- Connecting containers to networks
- Inspecting networks (`docker network ls`)

## 9. Docker Compose
- What is Docker Compose? (Managing multi-container applications)
- Writing a `docker-compose.yml` file
- Starting services with `docker-compose up`
- Stopping services with `docker-compose down`
- Using `docker-compose ps` to list running services

## 10. Docker Registries
- What is a Docker registry?
- Pushing custom images to Docker Hub (`docker push <image-name>`)
- Pulling images from private registries

## 11. Docker Best Practices
- Writing efficient Dockerfiles
- Minimizing image size
- Avoiding unnecessary layers
- Using `.dockerignore` to exclude unnecessary files from Docker builds

## 12. Docker Commands Cheat Sheet
- Commonly used commands: `docker ps`, `docker logs`, `docker exec`, `docker rm`, `docker rmi`
- Docker help system (`docker --help`)
