# BlogHub – React + Vite Project

A minimal setup for building React applications using **Vite** with fast HMR (Hot Module Replacement) and ESLint configured.

---

## Live Demo

Check out the live project here:  
[https://Dar-Jasif.github.io/BlogHub/](https://Dar-Jasif.github.io/BlogHub/)

---

## Features

- ✅ Fast development with **Vite**  
- ✅ React support with optional **Fast Refresh**  
- ✅ ESLint configured for better code quality  
- ✅ Easy to expand with TypeScript and advanced lint rules  

---

## Plugins Available

Two official plugins are supported:

- **[@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react)**  
  Uses Babel (or oxc with rollup-vite) for Fast Refresh  

- **[@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc)**  
  Uses **SWC** for Fast Refresh (faster compilation than Babel)  

---

## React Compiler

The React Compiler is **not enabled** in this template due to its impact on dev & build performance.  
To enable it, check the [React Compiler documentation](https://react.dev/learn/react-compiler/installation).  

---

## ESLint Configuration

For production apps, we recommend:

- Using **TypeScript**  
- Enabling type-aware lint rules with [`typescript-eslint`](https://typescript-eslint.io)  

See the [React + TypeScript Vite template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for more details.  

---

## Getting Started

1. Clone the repository:  
```bash
git clone https://github.com/Dar-Jasif/BlogHub.git
cd BlogHub
