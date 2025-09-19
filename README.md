# GPT-3
A modern, fully-responsive GPT-3 landing page UI, inspired by the JavaScript Mastery (jsmastery) YouTube channel.

## Overview
This repository contains a React application built with Vite, replicating the design and feel of a premium GPT-3 landing page. It is meant to showcase advanced React practices, modern styling, and project structuring, based on a step-by-step learning process from the JavaScript Mastery tutorial series.

## Features
-React 18 and Vite for fast development and build
-Fully responsive design using CSS Flexbox & Grid
-Modern components with clean separation of concerns
-Animated, modular sections and smooth scrolling
-Easy to expand, maintain, and customize

## Tech Stack
-Framework: React (with Vite for bundling and HMR)
-Languages: JavaScript, CSS, HTML
-Deployment: Vercel (live at gpt-3-fawn-alpha.vercel.app)
-Linting: ESLint (with recommended rules)
-References: JavaScript Mastery on YouTube


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
```
Components are split into components (reusable UI) and containers (layout/sections).

##Getting Started
To run the project locally:
```sh
git clone https://github.com/sayeedmunees/gpt-3.git
cd gpt-3
npm install
npm run dev
```
The app will be available at http://localhost:5173 by default.

##Credits & Acknowledgements
-UI and code patterns inspired by the JavaScript Mastery "GPT-3" tutorial.
-Starter template configuration thanks to Vite’s official React plugin.

##License
This project is licensed under the MIT License.
