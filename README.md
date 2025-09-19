# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.


```
gpt-3/
├── public/
│   └── vite.svg                   # Vite logo/favicon
├── src/
│   ├── assets/                    # Static images and logos
│   │   ├── ai.png
│   │   ├── atlassian.png
│   │   ├── blog01.png
│   │   ├── blog02.png
│   │   ├── blog03.png
│   │   ├── blog04.png
│   │   ├── blog05.png
│   │   ├── dropbox.png
│   │   ├── google.png
│   │   ├── logo.png
│   │   ├── logo.svg
│   │   ├── people.png
│   │   ├── possibility.png
│   │   ├── shopify.png
│   │   └── slack.png
│   ├── components/                # Reusable UI components
│   │   ├── article/
│   │   │   ├── Article.jsx
│   │   │   └── article.css
│   │   ├── brand/
│   │   │   ├── Brand.jsx
│   │   │   ├── brand.css
│   │   │   └── imports.js
│   │   ├── cta/
│   │   │   ├── CTA.jsx
│   │   │   └── cta.css
│   │   ├── feature/
│   │   │   ├── Feature.jsx
│   │   │   └── feature.css
│   │   ├── navbar/
│   │   │   ├── Navbar.jsx
│   │   │   └── navbar.css
│   │   └── index.js              # Component exports
│   ├── containers/               # Page sections/containers
│   │   ├── blog/
│   │   │   ├── Blog.jsx
│   │   │   ├── blog.css
│   │   │   └── imports.js
│   │   ├── features/
│   │   │   ├── Features.jsx
│   │   │   └── features.css
│   │   ├── footer/
│   │   │   ├── Footer.jsx
│   │   │   └── footer.css
│   │   ├── header/
│   │   │   ├── Header.jsx
│   │   │   └── header.css
│   │   ├── possibility/
│   │   │   ├── Possibility.jsx
│   │   │   └── possibility.css
│   │   ├── whatGPT3/
│   │   │   ├── WhatGPT3.jsx
│   │   │   └── whatGPT3.css
│   │   └── index.js              # Container exports
│   ├── App.css                   # Main app styles
│   ├── App.jsx                   # Main app component
│   ├── index.css                 # Global styles
│   └── main.jsx                  # React app entry point
├── .gitignore                    # Git ignore file
├── eslint.config.js              # ESLint configuration
├── index.html                    # HTML entry point
├── package-lock.json             # Dependency lock file
├── package.json                  # Project dependencies and scripts
├── README.md                     # Project documentation
└── vite.config.js               # Vite configuration
'''
