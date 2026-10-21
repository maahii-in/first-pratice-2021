# Google Keep Clone — Flask & Tailwind CSS

A lightweight note-taking web application inspired by Google Keep. It uses **Flask** for the Python backend and REST API, with **Tailwind CSS** and **vanilla JavaScript** for the frontend.

This project was created as a hands-on practice project while learning Git and GitHub.

## Features

- **Create notes:** Add notes with a title and content, with support for note color themes.
- **Pin notes:** Keep important notes at the top in a dedicated pinned section.
- **Edit notes:** Update the title and content of existing notes.
- **Delete notes:** Remove notes you no longer need.
- **Search notes:** Filter notes by title or content as you type.
- **REST API:** Flask backend with support for the main note operations: `GET`, `POST`, `PUT`, and `DELETE`.
- **Responsive, lightweight UI:** Tailwind CSS styling and vanilla JavaScript for frontend interactions.

## Tech Stack

- **Backend:** Python, Flask
- **Frontend:** HTML, Tailwind CSS, JavaScript
- **API:** REST
- **Development tools:** Git and GitHub

## Project Structure

```text
first-pratice/
├── app.py          # Flask application and REST API routes
├── templates/      # HTML templates and frontend interface
├── .venv/          # Local Python virtual environment (create locally)
└── README.md       # Project documentation
```

> The `.venv/` directory is a local development environment. It generally should not be committed to Git; create it on your own machine when setting up the project.

## Getting Started

### Prerequisites

- Python 3.9 or later
- `pip`
- Git (optional, for cloning the repository)

### 1. Clone the repository

```bash
git clone <repository-url>
cd first-pratice
```

Replace `<repository-url>` with the URL of your GitHub repository.

### 2. Create and activate a virtual environment

**Windows — Command Prompt**

```bat
python -m venv .venv
.venv\Scripts\activate
```

**Windows — PowerShell**

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
```

**Linux / macOS**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install Flask

```bash
python -m pip install Flask
```

If the project has a `requirements.txt` file, install the listed dependencies instead:

```bash
python -m pip install -r requirements.txt
```

### 4. Run the application

```bash
python app.py
```

Open the local address printed in your terminal (commonly `http://127.0.0.1:5000`) in your browser.

## API Overview

The Flask backend provides REST-style operations for managing notes:

| HTTP method | Purpose |
|---|---|
| `GET` | Retrieve notes |
| `POST` | Create a note |
| `PUT` | Update an existing note |
| `DELETE` | Delete a note |

The exact endpoint paths and request payloads depend on the routes implemented in `app.py`.

## Development Notes

- Keep secrets, local environment files, and the `.venv/` directory out of version control.
- If you add dependencies, record them in `requirements.txt` so the project is easier to set up on another machine.
- Test note creation, editing, pinning, searching, and deletion after making changes.

## Learning Goals

This project is a practical introduction to:

- Building a small Python web application with Flask.
- Connecting frontend interactions to backend API routes.
- Practicing everyday Git and GitHub workflows, including commits and repository updates.

## License

No license has been specified yet. Add a `LICENSE` file if you intend to distribute or reuse this project publicly.
