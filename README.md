# To-Do App

This is a simple and functional **To-Do App** built with React. The app allows users to manage tasks by adding, deleting, and rearranging them. The project is styled using CSS to provide a user-friendly interface.

## Features

- Add new tasks to your to-do list.
- Delete tasks that are no longer needed.
- Move tasks up or down to prioritize them.

## Tech Stack

- **React**: For building the user interface.
- **CSS**: For styling the application.
- **Vite**: For fast development and build setup.

## Folder Structure

```
.
├── App.jsx          # Main app component
├── TodoList.jsx     # To-do list component with functionality
├── main.jsx         # Entry point for the React app
├── index.css        # Styling for the application
```

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone 
   cd todolist
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173` to view the app.

## Components

### 1. App.jsx
This is the root component of the application. It renders the `TodoList` component.

### 2. TodoList.jsx
This component manages the task list and contains the following functionality:

- **Add Tasks**: Users can type a task in the input box and click the `Add` button to add it to the list.
- **Delete Tasks**: Each task has a `Delete` button to remove it from the list.
- **Move Tasks**: Tasks can be moved up or down using the respective buttons.

### 3. main.jsx
The entry point for the React application. It initializes the app and renders it inside the `root` div in `index.html`.

### 4. index.css
Contains all the styles for the app, including the layout and themes for buttons and list items.


## License

This project is open-source and available under the [MIT License](LICENSE).

"# To-Do-List" 
