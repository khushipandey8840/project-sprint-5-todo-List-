

# Task Management Board - React.js MVP

This project is a state-driven, Trello-style Kanban board built using **React.js** and **Vite**. It transitions from direct DOM manipulation to modern declarative UI patterns.

## Project Structure
- **Vite** is used as the build tool.
- **State Management** is handled via React's `useState` hook.
- **Persistence** is managed via `localStorage`.

--- Link:  https://project-sprint-5-todo-list.vercel.app/

## Sprint Roadmap & Deliverables

### Phase 1: Base MVP (P0 - Mandatory)
This phase establishes the foundational UI and state-driven architecture.
* **UI Architecture:** 3-column layout (To Do, In Progress, Done).
* **Add Task:** Input field to dynamically inject new task objects into the "To Do" state array.
* **Delete Task:** Functionality to remove a task from any column.
* **Move Task:** Directional action buttons (left/right) to update a task's status state.

### Phase 2: Priority 1 Features (Recommended)
This phase focuses on user experience and data integrity.
* **Inline Editing:** Toggle state to convert task text into an editable input field without needing a separate modal.
* **Priority System:** Dropdown during creation (High, Medium, Low) with conditional CSS rendering (e.g., color-coded borders or badges).
* **State Persistence:** Synchronization logic to save the Kanban board state to `localStorage`, ensuring data survival across browser hard refreshes.

---

## Technical Guidelines
1.  **Do Not Direct-Manipulate DOM:** React manages the view layer based on state changes.
2.  **Component Architecture:** Break the UI into reusable components (e.g., `Column`, `TaskCard`, `Board`).
3.  **State Lifting:** Ensure state is managed at the appropriate level to facilitate easy communication between columns and task actions.
README.md
Displaying README.md.
