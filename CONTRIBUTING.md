# Contributing to Brain-Tumor-MRI-Segmentation

Thank you for considering contributing to this project! By helping out, you enable better tools for brain tumor segmentation tasks, support reproducibility, and improve the codebase for everyone.  

This document explains how to contribute, guidelines to follow, and standards to maintain.  

---

## Table of Contents

- [Code of Conduct](#code-of-conduct)  
- [How to Contribute](#how-to-contribute)  
  - [Reporting Bugs](#reporting-bugs)  
  - [Suggesting Enhancements](#suggesting-enhancements)  
  - [Pull Requests](#pull-requests)  
- [Development Workflow](#development-workflow)  
- [Coding Standards](#coding-standards)  
- [Testing](#testing)  
- [Documentation](#documentation)  
- [License](#license)  

---

## Code of Conduct

- Be respectful and considerate in discussions.  
- Provide constructive feedback.  
- No discriminatory or harassing behavior.  

(You may want to adopt an existing Code of Conduct like the [Contributor Covenant](https://www.contributor-covenant.org/).)

---

## How to Contribute

### Reporting Bugs

If you find a bug or incorrect behavior:

1. Check first if the issue has already been reported in [Issues].  
2. If not, open a **new issue**. Include:  
   - A clear description of the problem  
   - Steps to reproduce it  
   - The expected result vs what you observed  
   - The environment (e.g., Python version, TensorFlow / Keras version, OS)  
   - Sample data if possible (or small subset)  

### Suggesting Enhancements

If you have an idea for a new feature or an improvement:

- Open an issue describing your idea.  
- Explain the motivation and the benefit.  
- If you have thoughts about implementation, share those.  

### Pull Requests

When you're ready to contribute code:

1. Fork the repository.  
2. Create a branch with a descriptive name:  
   ```
   feature/your-feature-name
   bugfix/issue-123
   ```
3. Make your changes.  
4. Ensure your changes follow coding standards (see below).  
5. Add or update tests if relevant.  
6. Update the documentation (README or others) for any new features or API changes.  
7. Commit with clear messages.  
8. Submit a Pull Request (PR) to the `main` branch.  

**What a PR should contain:**

- Description of what has been changed.  
- What issue or feature it addresses.  
- Any impact on existing interfaces, configs, performance.  
- If any migrations or setup changes are required.  

---

## Development Workflow

- Use Git for version control.  
- Main branch should always be stable.  
- Feature branches for development.  
- Rebase or merge main to keep it updated.  

---

## Coding Standards

- Use **Python 3.x** (declare version in `requirements.txt` or similar).  
- Follow [PEP 8](https://www.python.org/dev/peps/pep-0008/) style guidelines.  
- Use meaningful names for variables, functions, classes.  
- Write docstrings for functions and modules.  
- Keep functions/methods reasonably short and single-purpose.  
- Use type hints where useful.  

---

## Testing

- Include unit tests for new functionality.  
- Tests should cover both typical and edge‑cases.  
- Use a test framework like `pytest` or `unittest`.  
- Ensure existing tests pass before submitting PR.  

---

## Documentation

- Update `README.md` where applicable.  
- Document how to run preprocessing, training, evaluation.  
- If adding new modules/scripts, describe their purpose and usage.  
- Include examples of expected input and output where relevant (especially for data preprocessing).  

---

## License

By contributing, you agree that your contributions will be licensed under the project's license (MIT).  
