# Task 2: Coding Conf Component Library & Demo

This repository contains the solution for **Task 2**, where a reusable React component library is built from scratch (without any external UI libraries) and used to create two demo pages for a Coding Conference registration and ticket system.

## 🚀 Tech Stack
- **Vite + React**
- **CSS Modules** for component-level styling
- **No external UI libraries**

## 📦 Features
- Self-contained, reusable UI components (`Button`, `Input`, `Card`)
- Clean, DRY code and scalable folder structure
- Two demo pages:
  - **Home:** Registration form for Coding Conf 2025
  - **Ticket:** Displays the generated ticket

## 🛠️ How to Run Locally

```bash
cd frontend
npm install
npm run dev
```
Open the local URL shown in the terminal (usually http://localhost:5173/).

## 📚 How to Use Components

All reusable components are in `src/components/`.  
Import and use them in your pages like this:

```jsx
import Button from '../components/Button';
import Input from '../components/Input';
import Card from '../components/Card';
```

## 📄 License

This project is licensed under the MIT License.
