# Copilot/AI Instructions for This Repository

## Project Overview
This repository is a template for quickly bootstrapping new projects with a standardized structure, automation scripts, and best practices for collaboration and AI-assisted development. The `init.sh` script generates all foundational files and folders, including configuration for code quality, documentation, and contribution workflows.

## Key Structure & Workflow
- **`src/`**: Place all source code here. Organize by feature or domain as needed.
- **`docs/`**: Project documentation, guides, and usage examples.
- **`init.sh`**: Run this script to initialize the full project structure and all base files. Customize generated files as needed.
- **`.github/`**: Contains templates and rules for issues, pull requests, commit conventions, security, and Copilot/AI agent instructions.

## Conventions & Patterns
- Use clear, descriptive comments to guide Copilot/AI for code generation.
- Follow formatting and linting rules as defined in `.editorconfig`, `.prettierrc`, `.eslintrc.json`, `.flake8`.
- Use docstrings for all public functions and classes. Example:
  ```python
  def add(a, b):
      """Return the sum of two numbers."""
      return a + b
  ```
- Commit messages should follow the rules in `.github/COMMIT_CONVENTION.md` (if present).
- Place all tests and test configuration in the root or as specified by language (e.g., `pytest.ini`, `jest.config.js`).

## AI Agent Guidance
- When generating new files, mirror the structure and naming conventions found in this template.
- For documentation, follow the style and structure in `README.md` and `docs/`.
- When in doubt, prefer explicitness and clarity in both code and comments.
- Reference the output of `init.sh` for the canonical set of files and their intended purpose.

## Example Prompts
- "Write a function that calculates the mean of a list of numbers."
- "Generate a docstring for this function."
- "Create a new module in `src/` for user authentication."

## Integration & Customization
- After running `init.sh`, review and adapt generated files to fit your project's needs.
- Add or remove files in `.github/` to match your workflow.
- Update linting and formatting configs as your team prefers.

---
For further details, see `README.md` and the comments in `init.sh`.
