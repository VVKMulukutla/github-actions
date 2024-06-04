# Sample GitHub Actions Repository

This repository is a sample project demonstrating the use of GitHub Actions. It contains a simple Python program and corresponding tests, which are automatically run using GitHub Actions.

## Structure

The repository is structured as follows:

- `src/`: This directory contains the source code for the project.
    - `add.py`: A simple Python program.
    - `tests.py`: Tests for the `add.py` program.
- `.github/workflows/actions.yml`: This file defines the GitHub Actions workflow that automatically runs the tests whenever code is pushed to the repository.

## Running the Tests Locally

To run the tests locally, navigate to the `src/` directory and run the following command:

```bash
python tests.py
