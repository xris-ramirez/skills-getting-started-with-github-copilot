# Copilot Instructions for AI Coding Agents

## Project Overview
This repository is a self-paced exercise hub for learning and customizing GitHub Copilot. It contains assignment templates and starter code for Python programming, including basics, classes, games, and data analysis.

## Directory Structure
- `assignments/`: Contains subfolders for each assignment topic. Each has a `README.md` (instructions) and `starter-code.py` (editable code).
- `assets/`: Static files (CSS, JS, images) for web-based content.
- `templates/`: Markdown templates for assignments.
- `config.json`: Project configuration (if present).

## Key Patterns & Conventions
- **Assignment Flow:** Each assignment folder has a clear README with objectives and stepwise tasks. Starter code is provided for learners to edit.
- **Python Code:** All code is in Python 3. Use standard libraries unless otherwise specified in the assignment. For data analysis, use `pandas` if available.
- **No Central Build/Test:** There is no global build or test script. Each assignment is run and tested independently, usually by executing the relevant `starter-code.py`.
- **No External Dependencies:** Except for data analysis (which may use `pandas`), assignments are designed to run with standard Python installations.
- **Web Assets:** The `index.html` and files in `assets/` are for static web content and do not interact with Python code.

## Example Workflows
- To work on an assignment, open its `starter-code.py` and follow the steps in the corresponding `README.md`.
- For data analysis, load `data.csv` using `pandas` and save plots as images in the same folder.
- No automated grading or CI is present; manual review is expected.

## Project-Specific Guidance
- **Do not introduce frameworks or tools not already present.**
- **Keep code and instructions beginner-friendly.**
- **Preserve the structure of assignment folders.**
- **Do not modify files in `assets/` unless updating static web content.**
- **If adding new assignments, follow the existing folder and file naming conventions.**

## References
- See each assignment's `README.md` for detailed requirements and examples.
- For overall project context, see the root `README.md`.

---
For questions or updates, follow the conventions in this file and reference assignment-level documentation.
