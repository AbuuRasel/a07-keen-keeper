# React + Vite
# Knee Keeper

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.
Knee Keeper is a dedicated relationship management dashboard designed to help you maintain meaningful connections. It tracks your last interactions, sets contact goals, and provides visual analytics to ensure you never lose touch with the people who matter most.

Currently, two official plugins are available:
## Technologies Used

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)
* **Core:** React.js
* **Routing:** React Router DOM
* **Styling:** Tailwind CSS.
* **Data Visualization:** Recharts
* **State Management:** Local & JSON Fetching

## React Compiler
## Key Features

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).
### 1. Interaction Tracking & Timeline
Effortlessly log every **Call, Message, and Video Call** with a single click. Every interaction is automatically timestamped and added to a persistent Timeline page, allowing you to see the history of your relationship at a glance.

## Expanding the ESLint configuration
### 2.Advanced Relationship Analytics
Keep your social life on track with dedicated **Stats & Goal Cards**.
* **Days Since Contact:** Live counter of the time passed since your last chat.
* **Goal Tracking:** Set specific contact frequencies (e.g., every 14 days).
* **Next Due Date:** Automatically calculated reminders to help you stay proactive.
* **Editable Goals:** Quickly adjust your relationship goals as your schedule changes.

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
### 3.Robust User Experience
* **Intelligent Routing:** Includes a custom **404 Error Page** to handle any invalid links gracefully.
* **Responsive Design:** Fully optimized for mobile, tablet, and desktop views.
* **Toast Notifications:** Real-time feedback for every interaction logged.
