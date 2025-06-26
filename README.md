# AI Article Summarizer Website

A modern web application that summarizes articles using AI. Built with **React**, **Vite**, **Redux Toolkit**, and **TailwindCSS**.

## Features

- 🔗 Summarize articles by pasting URLs
- 📝 Clean, responsive UI with TailwindCSS
- 🕑 History of summarized articles (saved in local storage)
- 📋 Copy summaries to clipboard
- ⚡ Fast development with Vite

## Tech Stack

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Redux Toolkit](https://redux-toolkit.js.org/) (RTK Query for API requests)
- [TailwindCSS](https://tailwindcss.com/)

## Getting Started

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/ai-article-summarizer.git
   cd ai-article-summarizer

2. **Install dependencies:**
  npm install

3. **Run the development server:**
  npm run dev

4. Open http://localhost:5173 in your browser.

Project Structure
├── public/
├── src/
│   ├── assets/
│   ├── [App.jsx](http://_vscodecontentref_/0)
│   ├── [App.css](http://_vscodecontentref_/1)
│   ├── [main.jsx](http://_vscodecontentref_/2)
│   └── ...
├── [index.html](http://_vscodecontentref_/3)
├── [package.json](http://_vscodecontentref_/4)
└── ...

Development Notes
  1. Uses RTK Query for conditional API requests.
  2. Saves summary history in local storage.
  3. Handles form events and errors gracefully.
  4. Implements copy-to-clipboard functionality.
