# React Clone

A tiny React-like library built from scratch in vanilla JavaScript.  
This project re-implements some of React’s core ideas — **fiber architecture, reconciliation, hooks, and event handling** — in a lightweight way.

## Features
- **`createElement` & JSX support** → builds a virtual element tree
- **Fiber reconciler** → breaks rendering into units of work with `requestIdleCallback`
- **Efficient DOM updates** → handles placement, update, and deletion of nodes
- **Event handling** → adds/removes event listeners dynamically
- **Hooks system** → includes a working `useState` hook with queued state updates
- **Function components** → supports rendering components that return elements

## Why I built this
This isn’t meant to replace React. Instead, it’s a learning project:
to explore how React might work internally — fibers, reconciliation, and hooks — but in less than a few hundred lines of code.
