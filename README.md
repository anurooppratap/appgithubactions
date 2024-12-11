# Python CI Project

This project demonstrates how to set up Continuous Integration (CI) for a Python project using **GitHub Actions**. The workflow automatically runs tests to ensure code quality and functionality.

## Features

- Automatically triggered on:
  - Push events to the `main` branch.
  - Pull requests targeting the `main` branch.
- Runs unit tests using `pytest`.
- Validates the Python environment and dependencies.

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.8 or later
- `pip` package manager
- `pytest` for testing

## Setup

### Clone the Repository

```bash
git clone <repository-url>
cd <repository-directory>
