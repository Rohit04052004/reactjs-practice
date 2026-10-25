# React Practice — Rohit Chigatapu

My practice work following [Scrimba's "Learn React"](https://scrimba.com/learn-react-c0e) course — each numbered folder is a checkpoint/challenge from the course, going from JSX basics up through two full capstone projects.

## What's covered

**01. Static Pages**
- JSX, `React.createElement()`, why React is declarative & composable
- Custom components, fragments, parent/child components, organizing components, styling with classes
- Project: **ReactFacts** — a static multi-component page

**02. Data-Driven React**
- Props: passing, receiving, destructuring, non-string props, spreading objects as props
- Rendering arrays with `array.map()`, the `key` prop
- Importing static assets
- Project: **Travel Journal** — reusable `Entry` components driven by data

**03. React State**
- `useState`, array destructuring, updating state (incl. via callback functions)
- Complex state: arrays and objects, immutable updates
- Forms: controlled inputs, `textarea`/`defaultValue`, radio, checkbox, select, `Object.fromEntries`
- Conditional rendering: `&&`, ternaries
- Passing state as props / lifting state up, dynamic styles
- Projects: **Chef Claude** (AI-powered recipe generator calling an LLM API), **Sound Pads** (shared vs. local state, updating items in an array)

**04. Side Effects**
- Controlled components, fetching data in React
- `useEffect`: syntax, dependency arrays, cleanup functions
- Project: **Meme Generator** — fetches memes from an API and lets the user cycle through them

**05. Capstone Project #1 — Tenzies**
- A dice-rolling game built end to end: component structure, generating/holding dice, win-condition logic, lazy state initialization, accessibility improvements

**06. Capstone Project #2 — Assembly Endgame**
- A hangman-style word game: keyboard UI, tracking guessed/wrong letters, win/lose states, conditional rendering via helper functions, accessibility (a11y) improvements, "new game" reset flow

## Tech stack

React, Vite, JSX/JavaScript, CSS — each lesson folder is an independent Vite project with its own `package.json`.

## Running a lesson

```bash
cd "<section folder>/<lesson folder>"
npm install
npm run dev
```

## Credits

Course content and starter files from [Scrimba's Learn React course](https://scrimba.com/learn-react-c0e), worked through and maintained here by Rohit Chigatapu.
