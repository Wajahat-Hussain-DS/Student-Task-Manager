# Student Task Management System

A simple front-end web project for organizing student tasks. The current version provides a basic interface for entering task titles and descriptions and includes a task-search input for future task filtering.

## Project Description

The Student Task Management System is designed to help students record, search, and manage academic tasks in one place. This repository currently contains the initial user interface and JavaScript search-input interaction. Additional task storage and management functionality can be added in future versions.

## Team Members

- **Wajahat Hussain** — Project owner and developer
-  **Muhammad Abubakar** — Project partner and developer

## Features

- Student task manager interface
- Task title input
- Task description input
- Search tasks input
- Add Task button in the user interface
- Console feedback when the search field is used
- Lightweight, browser-based implementation with no installation required

> **Current status:** Task persistence, task-list rendering, editing, deletion, and filtering logic are planned enhancements for future versions.

## Technologies

- **HTML5** — Page structure and form controls
- **CSS3** — Styling foundation
- **JavaScript** — Search-input event handling and future application behavior
- **Git** — Version control
- **GitHub** — Repository hosting and collaboration

## Git Workflow

1. Clone or open the repository.
2. Create a feature branch from `main`.
3. Make and test changes locally.
4. Stage and commit the changes with a clear message.
5. Push the branch to GitHub.
6. Open a pull request for review.
7. Merge the approved pull request into `main`.
8. Delete the branch after merging when it is no longer needed.

## Branches

- **`main`** — Default and stable project branch
- **Feature branches** — Used for isolated changes such as UI improvements, task functionality, or documentation updates

Example feature branch names:

- `feature/task-management`
- `feature/search-functionality`
- `docs/readme-update`

## Git Commands Demonstrated

```bash
git clone https://github.com/Wajahat-Hussain-DS/Student-Task-Manager.git
cd Student-Task-Manager
git status
git branch
git switch -c feature/my-change
git add .
git commit -m "Describe the change"
git push -u origin feature/my-change
git switch main
git pull origin main
```

## GitHub Features Demonstrated

- Public GitHub repository
- Default `main` branch
- Branch-based development
- Commits with descriptive messages
- Pull requests for reviewing changes
- Issues for tracking work and improvements
- Repository README documentation

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/Wajahat-Hussain-DS/Student-Task-Manager.git
   ```

2. Open the project directory.
3. Open `index.html` in a modern web browser.
4. Enter a task title and description. Use the search field and check the browser developer console to see search input feedback.

No server, package manager, or external dependencies are required for the current version.

## Screenshots

Screenshots can be added here as the interface develops. Recommended screenshots include:

1. The Student Task Manager home screen.
2. The task title and description form filled in.
3. The browser console showing search input feedback.

Example Markdown for adding a screenshot:

```markdown
![Student Task Manager interface](screenshots/student-task-manager.png)
```

## Version History

- **v0.1.0 — October 7, 2026:** Initial project interface with task title and description fields, search input, Add Task button, and basic search event logging.

## Contributors

- [Wajahat Hussain](https://github.com/Wajahat-Hussain-DS) — Project owner and developer

Contributions and suggestions are welcome through GitHub issues and pull requests.
