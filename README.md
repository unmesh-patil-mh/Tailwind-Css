# 🚀 Tailwind CSS Manual Setup

A clean and beginner-friendly Tailwind CSS setup using Node.js, Tailwind v3, PostCSS, and Autoprefixer.

This project demonstrates how to manually install and configure Tailwind CSS without using any framework.

---

## 📂 Project Structure
```
tailwindCss/
│
├── node_modules/
├── dist/
│ └── output.css
│
├── src/
│ └── input.css
│
├── index.html
├── package.json
├── postcss.config.js
└── tailwind.config.js
```

## Initalize the Node In Your Project 
```
npm init -y
```

## Install TailwindCss Version 3
```
npm install -D tailwindcss@3 postcss autoprefixer
```

## Generate Config Files
```
npx tailwindcss init -p
```
This Creates Two Files in Our Project
-> tailwind.config.js
-> postcss.config.js

