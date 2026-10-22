# Google Keep Clone — Flask & Tailwind CSS

A lightweight, responsive note-taking web application inspired by Google Keep. Built with **Flask**, **Python**, **HTML**, **Tailwind CSS**, and **Vanilla JavaScript**, this project demonstrates full-stack web development fundamentals and REST API integration.

## Overview

The Google Keep Clone provides a simple and intuitive interface for creating and managing notes. Developed as a hands-on learning project, it focuses on frontend design, backend development, API integration, and version control using Git and GitHub.

## Features

- **Create Notes** — Add notes quickly through a simple interface.
- **Organize Content** — Keep notes structured and easy to access.
- **Responsive UI** — Use a clean interface designed with Tailwind CSS.
- **REST API Integration** — Connect frontend interactions with the Flask backend.
- **Lightweight Architecture** — Use vanilla JavaScript for frontend interactions without a heavy JavaScript framework.
- **Learning-Focused Development** — Practice Git, GitHub, Python, Flask, and web development workflows.

*Note: Features should be adjusted to match the functionality currently implemented in the project.*

## Tech Stack

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| Flask | Web application framework and REST API |
| HTML5 | Page structure |
| Tailwind CSS | Styling and responsive layouts |
| JavaScript | Frontend interactions |
| Git & GitHub | Version control and project collaboration |

## Project Structure

```text
first-pratice-2021/
├── .vscode/          # Editor configuration
├── templates/        # HTML templates
├── .gitignore        # Git ignore rules
├── README.md         # Project documentation
├── animi.txt         # Supporting project file
├── app.py.txt        # Backend-related file
├── app_v2.py         # Application implementation
├── fasta3.txt        # Supporting project file
├── fasta4.txt        # Supporting project file
├── fastmain.txt      # Supporting project file
└── info.txt          # Project information
```

*The structure above reflects the files visible in the repository. Update it as the project evolves, and rename or remove placeholder files as appropriate.*

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Python 3.9 or later
- pip (Python package manager)
- Git

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/maahii-in/first-pratice-2021.git
```

**2. Navigate to the project directory**

```bash
cd first-pratice-2021
```

**3. Create a virtual environment**

```bash
python -m venv venv
```

**4. Activate the virtual environment**

Windows:

```bash
venv\Scripts\activate
```

macOS / Linux:

```bash
source venv/bin/activate
```

**5. Install dependencies**

If a `requirements.txt` file is available:

```bash
pip install -r requirements.txt
```

Otherwise, install the dependencies used by the application, for example:

```bash
pip install Flask
```

**6. Run the application**

If `app_v2.py` is the main Flask application:

```bash
python app_v2.py
```

If the main application file is different, replace `app_v2.py` with the correct filename.

**7. Open the application**

Visit the local URL displayed in your terminal, typically:

```text
http://127.0.0.1:5000
```

## How It Works

The application follows a simple full-stack architecture:

1. The frontend displays the note-taking interface using HTML and Tailwind CSS.
2. JavaScript handles user interactions and communicates with the backend.
3. Flask processes application requests and exposes backend functionality through routes or REST API endpoints.
4. The frontend updates the interface based on the responses received from the backend.

## Learning Objectives

This project was created to strengthen practical knowledge of:

- Building web applications with Python and Flask.
- Designing responsive user interfaces with Tailwind CSS.
- Connecting frontend components to backend APIs.
- Understanding basic application architecture.
- Managing source code and project history with Git and GitHub.

## Future Improvements

Potential enhancements include:

- Edit and delete notes.
- Search and filter notes.
- Pin important notes.
- Add labels, colors, and categories.
- Implement persistent storage using SQLite or another database.
- Add user authentication and personalized notes.
- Improve accessibility and mobile responsiveness.
- Add automated tests and deployment support.

## Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push the branch to your fork.
5. Open a pull request describing your improvements.

## License

No license has been specified yet. Add a `LICENSE` file to define how others may use, modify, and distribute this project.

## Author

**MAHI BUDATI** (`maahii-in`)

GitHub: [https://github.com/maahii-in](https://github.com/maahii-in)

---

*Built as a practical project to explore full-stack web development and learn Git and GitHub.*
