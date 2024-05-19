# Task Management App

This is a simple command-line Task Management App built using Python. It allows you to add, remove, list, and recommend tasks based on their priority. The task recommendations are powered by a machine learning model using the Naive Bayes algorithm.

## Features

- **Add Task**: Add a new task with a description and priority (Low/Medium/High).
- **Remove Task**: Remove a task by its description.
- **List Tasks**: Display all the tasks.
- **Recommend Task**: Recommend a high-priority task.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/task-management-app.git
    cd task-management-app
    ```

2. **Create and activate a virtual environment** (optional but recommended):
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required dependencies**:
    ```bash
    pip install pandas scikit-learn
    ```

## Usage

1. **Run the app**:
    ```bash
    python task_management.py
    ```

2. **Follow the on-screen menu**:
    - **Add Task**: Enter the task description and its priority (Low/Medium/High).
    - **Remove Task**: Enter the description of the task to remove.
    - **List Tasks**: View all the tasks.
    - **Recommend Task**: Get a recommendation for a high-priority task.
    - **Exit**: Exit the application.

## Files

- `task_management.py`: The main script containing the task management logic.
- `tasks.csv`: The CSV file where tasks are stored. This file is created automatically when you add tasks.

## Machine Learning

The task priority recommendation is based on a Naive Bayes classifier. The model is trained on the tasks stored in `tasks.csv`. The training happens each time the application is started.

## Note

- Ensure you have a `tasks.csv` file in the same directory as the script or the script will create one when tasks are added.
- The application uses a simple text-based interface.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

