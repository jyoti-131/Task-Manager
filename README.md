# Task Manager

A simple task management app built with React that allows users to add, delete, and persist tasks even after refreshing the page. The app utilizes `localStorage` to store tasks locally in the browser, ensuring they remain on the list even after the page is reloaded.

## Features:
- Add tasks to the list.
- Delete tasks from the list.
- Prevent adding duplicate tasks.
- Persist tasks across page refreshes using `localStorage`.

## Technologies Used:
- React
- JavaScript
- CSS (for styling)
- `localStorage` (for persistent data storage)

## Getting Started:

### Prerequisites:
Make sure you have `Node.js` installed on your machine.

### Installation:
1. Clone this repository:
   ```bash
   git clone https://github.com/jyoti-131/task-manager.git
   ```

2. Navigate to the project directory:
   ```bash
   cd task-manager
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm start
   ```

5. Open your browser and go to `http://localhost:3000` to view the app.

### Usage:
- Type your task into the input field and click "Save" to add it to the list.
- Tasks will be saved in `localStorage` and remain even after refreshing the page.
- If you try to add a duplicate task, an alert will notify you.
- Click "Delete" next to a task to remove it from the list.

### Example:

1. **Adding Tasks:**
   - Type "Buy groceries" and click "Save". The task will appear in the list.
   - Type "Clean the house" and click "Save". Both tasks will appear in the list.

2. **Deleting Tasks:**
   - Click "Delete" next to "Buy groceries" to remove it from the list.
