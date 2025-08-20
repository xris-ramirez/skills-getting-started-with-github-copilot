# Assignments Instructions for AI Coding Agents

## Overview
The `assignments/` folder is the core of this repository. It contains self-contained Python programming exercises, each in its own subfolder. These assignments are designed for beginners and focus on hands-on learning and Copilot customization.

## Structure & Patterns
- Each assignment is in a subfolder (e.g., `python-basics/`, `python-classes/`, `games-in-python/`, `data-analysis/`).
- Every subfolder contains:
  - `README.md`: Assignment objectives, stepwise tasks, and requirements.
  - `starter-code.py`: The only file to edit for solutions.
  - (For data analysis) `data.csv`: Input data for analysis tasks.
- Assignments are fully independent. There is no shared code or data flow between them.

## Developer Workflows
- To work on an assignment, open its `starter-code.py` and follow the instructions in the corresponding `README.md`.
- Run code directly (e.g., `python assignments/python-basics/starter-code.py`).
- For data analysis, use `pandas` to load `data.csv` and save plots as images in the same folder.
- There is no automated grading, build, or test system. Manual review is expected.

## Conventions & Constraints
- Use only standard Python 3 libraries unless the assignment explicitly allows (e.g., `pandas` for data analysis).
- Do not introduce new dependencies, frameworks, or tools.
- Keep code and solutions beginner-friendly.
- Do not change the folder/file layout. New assignments must follow the pattern: `assignments/<topic>/README.md` and `starter-code.py`.
- Do not modify files in other assignments or in `assets/`.

## Integration & External Dependencies
- No cross-assignment or external service integration exists.
- Only `pandas` is permitted as an external package, and only for data analysis assignments.

## References
- See each assignment's `README.md` for requirements and examples.
- For overall project context, see `.github/copilot-instructions.md` and the root `README.md`.

---
For questions or updates, follow the conventions in this file and reference assignment-level documentation.
