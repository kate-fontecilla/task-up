# Task Up

A lightweight, browser-based to-do list application for keeping track of everyday tasks. Task Up is built with HTML, CSS, and vanilla JavaScript, with Bootstrap for responsive layout and UI components.

## Features

- **Add tasks:** Enter a task and add it using the Add button or the Enter key.
- **Persistent task data:** Tasks are saved in the browser's `localStorage`, so they remain available after refreshing the page in the same browser.
- **Task list:** View the tasks saved in your browser.
- **Date display:** Shows the current date at the top of the app.
- **Responsive styling:** Uses Bootstrap 5 and custom CSS for the interface.

> **Note:** In the current implementation, checking a task removes it from the saved task list. It does not retain a completed-task history.

## Built With

- HTML5
- CSS3
- JavaScript (vanilla)
- [Bootstrap 5.3.3](https://getbootstrap.com/)
- [Bootstrap Icons](https://icons.getbootstrap.com/)
- Browser `localStorage`

## Getting Started

Task Up is a static web application. No package installation, build process, or backend server is required.

### Run locally

1. Clone the repository:

   ```bash
   git clone https://github.com/kate-fontecilla/task-up.git
   ```

2. Move into the project directory:

   ```bash
   cd task-up
   ```

3. Open `index.html` in your web browser.

You can also use a local development server (for example, the Live Server extension in Visual Studio Code) if you prefer.

## Project Structure

```text
task-up/
├── assets/
│   └── background.jpg
├── css/
│   └── style.css
├── index.html
└── README.md
```

## Usage

1. Open Task Up in your browser.
2. Type a task into the **Add task** field.
3. Select **Add** or press **Enter**.
4. Your task appears in the task list and is saved in the browser's local storage.
5. Select a task's checkbox to remove it from the current list.

### Data Storage

Task data is stored locally in the browser under the `tasks` key in `localStorage`. It is not synced across browsers or devices. Clearing the browser's site data may remove saved tasks.

## Contributing

Contributions and suggestions are welcome.

1. Fork the repository.
2. Create a feature branch:

   ```bash
   git checkout -b feature/your-feature-name
   ```

3. Commit your changes:

   ```bash
   git commit -m "Add your feature"
   ```

4. Push your branch and open a pull request.

## License

No license is currently specified in this repository. Unless a license is added, the project should be treated as having all rights reserved.
