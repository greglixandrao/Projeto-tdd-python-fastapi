# TDD Project

A Python project focused on Test-Driven Development (TDD) practices.

## Overview

This project demonstrates TDD principles and best practices using Python. It includes examples of writing tests first, then implementing the code to make those tests pass.

## Setup

### Prerequisites

- Python 3.11+
- Poetry for dependency management

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   poetry install
   ```
3. Activate the virtual environment:
   ```bash
   poetry shell
   ```

## Running Tests

```bash
# Run all tests
poetry run pytest

# Run tests with coverage
poetry run pytest --cov

# Run tests in watch mode
poetry run pytest-watch
```

## Project Structure

```
tdd-project/
├── src/
│   └── tdd_project/
│       └── __init__.py
├── tests/
│   └── __init__.py
├── pyproject.toml
└── README.md
```

## TDD Workflow

1. **Red**: Write a failing test
2. **Green**: Write the minimum code to make the test pass
3. **Refactor**: Improve the code while keeping tests green

## Contributing

1. Write tests first
2. Follow the TDD cycle (Red-Green-Refactor)
3. Ensure all tests pass before committing
4. Maintain high code coverage

## License

This project is licensed under the MIT License.
