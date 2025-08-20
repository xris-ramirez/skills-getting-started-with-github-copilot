# Copilot Instructions for AI Coding Agents

## Project Overview
This repository is a self-paced exercise for customizing the GitHub Copilot experience. It is organized as a set of Python programming assignments, each in its own subdirectory under `assignments/`. The project is designed for educational purposes, focusing on Python basics, OOP, simple games, and data analysis.

## Directory Structure
- `assignments/` — Contains all assignment modules. Each subfolder has:
  - `README.md` — Assignment instructions and requirements
  - `starter-code.py` — The initial code template for students
  - (For data analysis) `data.csv` — Sample dataset for analysis
- `assets/` — Static files for the web interface (HTML, CSS, JS, images)
- `templates/` — Markdown templates for assignments
- `index.html` — Main landing page for the exercise
- `config.json` — Configuration for the exercise (if present)

## Key Patterns & Conventions
- **Assignment Flow:** Each assignment is self-contained. Instructions are in the local `README.md`, and code is written in `starter-code.py`.
- **No Central Build/Test:** There is no global build or test runner. Each Python file can be run independently (e.g., `python3 assignments/python-basics/starter-code.py`).
- **No External Dependencies** (except for data analysis, which may use `pandas` and `matplotlib`).
- **Web Assets:** The `assets/` directory supports the web UI. JS files (`assignment.js`, `script.js`) may interact with the HTML pages in `assets/pages/`.
- **Data Analysis:** The `assignments/data-analysis/` module expects use of `pandas` and `matplotlib` for CSV loading and plotting.

## Examples
- To implement the "Python Basics" assignment, read `assignments/python-basics/README.md` and edit `starter-code.py` in the same folder.
- For the Hangman game, see `assignments/games-in-python/README.md` and use its `starter-code.py`.
- For data analysis, use `pandas.read_csv()` on `data.csv` and save plots to the same directory.

## Agent Guidance
- **Do not introduce frameworks or tools not already present.**
- **Preserve the educational structure:** Do not combine assignments or alter the starter templates unless explicitly instructed.
- **Document code clearly** for learners, using comments and simple patterns.
- **Do not add CI/CD, test runners, or package managers** unless requested.
- **Reference assignment-specific README.md files** for requirements and context.

## Integration Points
- No backend or API integration is present.
- All code is local and file-based.

---
For further details, see the main `README.md` and assignment-specific `README.md` files.
