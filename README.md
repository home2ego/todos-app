# Todos App

A React todo app that allows users to create, manage, and organize their to-do lists.

## 🚀 Live Demo

Try it here: https://todos-web.pages.dev/

## 📦 Technologies

### Core
- `React` — UI framework
- `TypeScript` — Type safety
- `HTML5` — Structure
- `SCSS & Bulma` — Styling
- `REST APIs (Fetch API)` — Server communications

### UI/UX
- `React Transition Group` — Smooth animations

### Development & Deployment
- `Vite` — Build tool
- `ESLint & Prettier` — Code quality & formatting
- `Cloudflare` — Hosting and deployment

## ✨ Features
- **Storage**: Tasks are stored on the server.
- **Loading**: Slightly delayed server responses (100 ms) with loading indicators for better UX.
- **Add Todos**: Create new tasks by typing in the input field and pressing `Enter`.

<div align="center">
    <img src="docs/todos-add.gif" width="500" height="300" alt="Add Todos" />
</div>

- **Inline Editing**: Double-click to edit existing task, `Esc` to cancel editing.

<div align="center">
    <img src="docs/todos-edit.gif" width="500" height="300" alt="Inline Editing" />
</div>

- **Toggle Completion & Deletion**: Delete individual tasks, or toggle the completion status of all tasks to clear them at once.

<div align="center">
    <img src="docs/todos-delete.gif" width="500" height="300" alt="Toggle Completion & Deletion" />
</div>

- **Filtering**: View all tasks, only active ones, or completed ones. Also displays the count of active tasks.

<div align="center">
    <img src="docs/todos-filter.gif" width="500" height="300" alt="Filtering" />
</div>

- **Error Notifications**: Alerts for issues like network failures, empty inputs, or API errors.

<div align="center">
    <img src="docs/todos-error.gif" width="500" height="300" alt="Error Notifications" />
</div>

## 💭 How Can It Be Improved?

- Add user authentication to support multiple users and private todo lists.
- Implement real backend integration (e.g., with Node.js/Express and a database like MongoDB/PostgreSQL).
- Add drag-and-drop reordering of tasks.
- Integrate dark mode toggling for improved accessibility.

## 🚦 Running the Project

```bash
git clone https://github.com/home2ego/todos-app
cd todos-app
npm install    # or pnpm install / yarn install
npm run dev    # or pnpm dev / yarn dev