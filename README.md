# Anecdotes

A small React app that displays a random anecdote, lets users vote on it, and highlights the anecdote with the most votes.

## Features

- Random anecdote selector
- Vote counter for each anecdote
- Automatically highlights the most popular anecdote
- Built with React and Vite for a fast development experience

## Tech Stack

- React 19
- Vite
- JavaScript
- ESLint

## Project Structure

```text
Anecdotes/
├── public/
├── src/
│   ├── App.jsx
│   ├── main.jsx
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── package-lock.json
├── vite.config.js
└── README.md
```

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/Ibrocold/Anecdotes.git
cd Anecdotes
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

4. Open the local development URL shown in the terminal.

## Build for Production

```bash
npm run build
```

This creates a production-ready bundle in the `dist/` folder.

## Preview Production Build

```bash
npm run preview
```

## Linting

```bash
npm run lint
```

## Notes

This project is a simple front-end exercise inspired by the classic anecdote voting application pattern from full-stack React tutorials.
