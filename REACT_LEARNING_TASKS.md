# React + TypeScript Learning Tasks

Goal: Learn React using TypeScript (`.tsx`) without Next.js and without external state managers.

Rules for all tasks:
- [ ] Use React + TypeScript only
- [ ] Prefer functional components
- [ ] Use `useState`, `useEffect`, `useMemo`, `useRef`, and custom hooks where needed
- [ ] Do not use Redux, Zustand, MobX, or other state managers
- [ ] Keep components small and reusable
- [ ] Use CSS, CSS Modules, or inline styles, but keep it simple

## Setup Task

### Task 1: Create a React + TypeScript app
- [ ] Set up a React project with Vite + TypeScript
- [ ] Confirm the app runs locally
- [ ] Create a simple `App.tsx` with a heading and a paragraph
- [ ] Make sure the project uses `.tsx` files

Suggested command:
```bash
npm create vite@latest my-react-app -- --template react-ts
cd my-react-app
npm install
npm run dev
```

---

## Basics

### Task 2: Learn component structure
- [ ] Create an `App` component
- [ ] Create a `Header` component
- [ ] Create a `Card` component
- [ ] Create a `Button` component
- [ ] Pass data using props
- [ ] Type props with TypeScript interfaces
- [ ] Show at least 3 cards with different titles and descriptions

### Task 3: Render lists and keys
- [ ] Create a list of products or users using `map()`
- [ ] Use a TypeScript type for each item
- [ ] Add a unique `key`
- [ ] Show items with text and a button

### Task 4: Events and user interaction
- [ ] Build a simple counter app
- [ ] Add buttons for increment, decrement, and reset
- [ ] Type the state value as `number`
- [ ] Show the current value in the UI

### Task 5: Conditional rendering
- [ ] Create a component that shows a login form when not logged in
- [ ] Show a welcome message when logged in
- [ ] Include a button to toggle state

---

## State and Forms

### Task 6: Controlled form inputs
- [ ] Build a form with name, email, and message
- [ ] Use `useState` for each input
- [ ] Show the form data on submit
- [ ] Validate basic required fields

### Task 7: Add and remove list items
- [ ] Create a task list
- [ ] Add tasks with a form input
- [ ] Mark tasks as done/undone
- [ ] Delete tasks
- [ ] Filter completed tasks or show total count

### Task 8: Lifting state up
- [ ] Create a parent component that holds the main state
- [ ] Create child components for form and list
- [ ] Pass state and handlers through props
- [ ] Understand how data flows in React

---

## Hooks and Data Flow

### Task 9: Use `useEffect`
- [ ] Build a component that loads a list of posts or users from an API
- [ ] Use `fetch` in `useEffect`
- [ ] Show loading state
- [ ] Show error state
- [ ] Render the fetched data

### Task 10: `useMemo` and derived data
- [ ] Create a list of products with prices
- [ ] Calculate subtotal, tax, and total using `useMemo`
- [ ] Show the values in a summary section
- [ ] Keep the calculation logic separate from UI logic

### Task 11: `useRef` for DOM access
- [ ] Build a component with an input field
- [ ] Add a button to focus the input
- [ ] Add a button to clear the input
- [ ] Use `useRef` to access the input element

### Task 12: Custom hook
- [ ] Create a custom hook named `useToggle` or `useFetch`
- [ ] Move repeated logic from a component into a custom hook
- [ ] Reuse it in at least two components

---

## Intermediate React

### Task 13: Component composition
- [ ] Build a small dashboard with `Sidebar`, `Header`, `Card`, and `Table`
- [ ] Reuse components in different places
- [ ] Keep props typed with interfaces
- [ ] Use simple but clean styling

### Task 14: Context API (without external state managers)
- [ ] Create a theme toggle app
- [ ] Use `createContext` and `useContext`
- [ ] Add light/dark mode toggle
- [ ] Apply the theme to the page

Note: This is not a state manager. It is built-in React.

---

## Mini Projects

### Task 15: Build a mini TODO app
- [ ] Add task
- [ ] Delete task
- [ ] Mark complete
- [ ] Filter: all / active / completed
- [ ] Count completed tasks
- [ ] Save tasks to `localStorage`

This is a great project to solidify all core React concepts.

### Task 16: Build a mini product catalog
- [ ] Create product cards
- [ ] Add a search box
- [ ] Add category filter
- [ ] Add items to cart
- [ ] Show cart total
- [ ] Remove from cart
- [ ] Use TypeScript interfaces
- [ ] Keep state in the parent component

---

## Final Challenge

### Task 17: Build one complete React app
Choose one of these:
- [ ] Todo app
- [ ] Notes app
- [ ] Expense tracker
- [ ] Product catalog
- [ ] Blog list app

Requirements:
- [ ] React + TypeScript only
- [ ] No state manager
- [ ] At least 3 reusable components
- [ ] At least one custom hook
- [ ] At least one API fetch or localStorage usage
- [ ] Clean UI and readable code

---

## Suggested Learning Order

1. [ ] Components + props
2. [ ] State + events
3. [ ] Forms + validation
4. [ ] Lists + conditional rendering
5. [ ] Effects + API fetching
6. [ ] Custom hooks
7. [ ] Context API
8. [ ] Final app project

---

## Recommended Practice Rules

- [ ] Build small features, then combine them
- [ ] Read the error messages carefully
- [ ] Try to solve problems yourself before searching
- [ ] Keep components small and focused
- [ ] Use TypeScript types everywhere possible
- [ ] Refactor after each feature so the code stays clean

---

## Good Next Step

After completing these tasks, you should be comfortable with:
- [ ] React component structure
- [ ] TypeScript in `.tsx` files
- [ ] State management with `useState`
- [ ] Data fetching with `useEffect`
- [ ] Hooks and reusable logic
- [ ] Building small real-world apps without external state libraries

If you want, I can next turn this into:
- [ ] a daily study plan
- [ ] a beginner project roadmap
- [ ] or a starter React + TypeScript project structure for you to build step by step.
