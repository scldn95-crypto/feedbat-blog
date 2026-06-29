---
title: "Getting Started with React"
date: 2026-06-25
slug: getting-started-with-react
excerpt: "A beginner's guide to building your first React component from scratch."
published: true
---

# Getting Started with React

React is a JavaScript library for building user interfaces. In this post we'll build a simple component from scratch.

## Your First Component

```jsx
function Greeting({ name }) {
  return <h1>Hello, {name}!</h1>;
}
```

Components are the building blocks of every React app. They accept props and return JSX — a syntax that looks like HTML but compiles to JavaScript.

## State and Hooks

Use `useState` to add interactivity:

```jsx
import { useState } from 'react';

function Counter() {
  const [count, setCount] = useState(0);
  return <button onClick={() => setCount(count + 1)}>Count: {count}</button>;
}
```

That's all you need to get started.
