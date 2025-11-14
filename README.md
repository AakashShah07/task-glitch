# TaskGlitch - Task Management Dashboard

TaskGlitch is a modern, single-page React application designed for managing and analyzing sales tasks. It provides a comprehensive dashboard with metrics, charts, and analytics to help sales managers track their team's performance and make data-driven decisions.

## Features

*   **Task Management:** Create, edit, and delete tasks with details like title, revenue, time taken, priority, and status.
*   **Interactive Task Table:** A sortable and filterable table to view and manage tasks.
*   **Detailed Task View:** Click on a task to view and edit its details in a dialog.
*   **Metrics Bar:** A real-time overview of key performance indicators (KPIs) like total revenue, time efficiency, revenue per hour, and average ROI.
*   **Charts and Insights:** Visualize data with charts for revenue by priority, revenue by status, and ROI distribution.
*   **Advanced Analytics:** An analytics dashboard with a sales funnel, weekly throughput, weighted pipeline, revenue forecast, and velocity by priority.
*   **Activity Log:** A log of recent activities like adding, updating, and deleting tasks.
*   **Undo Functionality:** Undo accidental task deletions with a snackbar notification.
*   **Export to CSV:** Export the filtered task list to a CSV file.

## Tech Stack

*   **Framework:** [React](https://reactjs.org/)
*   **Build Tool:** [Vite](https://vitejs.dev/)
*   **UI Library:** [Material-UI (MUI)](https://mui.com/)
*   **Charting Library:** [MUI X Charts](https://mui.com/x/react-charts/)
*   **Language:** [TypeScript](https://www.typescriptlang.org/)

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

*   [Node.js](https://nodejs.org/en/) (v14 or later)
*   [npm](https://www.npmjs.com/)

### Installation

1.  Clone the repo
    ```sh
    git clone https://github.com/AakashShah07/task-glitch
    ```
2.  Install NPM packages
    ```sh
    npm install
    ```

### Running the Application

To run the application in development mode, use the following command:

```sh
npm run dev
```

This will start the development server and open the application in your default browser at `http://localhost:5173`.

## Available Scripts

In the project directory, you can run:

*   `npm run dev`: Runs the app in the development mode.
*   `npm run build`: Builds the app for production to the `dist` folder.
*   `npm run preview`: Serves the production build locally for preview.

## Project Structure

The project structure is organized as follows:

```
/
├── public/
│   └── tasks.json      # Static JSON data for tasks
├── src/
│   ├── components/     # React components
│   ├── context/        # React context for state management
│   ├── hooks/          # Custom React hooks
│   ├── utils/          # Utility functions
│   ├── App.tsx         # Main application component
│   ├── main.tsx        # Application entry point
│   ├── theme.ts        # MUI theme configuration
│   ├── types.ts        # TypeScript type definitions
│   └── ...
├── .gitignore
├── index.html
├── package.json
└── ...
```
