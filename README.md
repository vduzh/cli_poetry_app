# My CLI App

## Description

A simple CLI application built with Python using Poetry.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/vduzh/cli_poetry_app.git
    cd cli_poetry_app
    ```

2. Install the dependencies:

    ```bash
    poetry install
    ```

3. Run tests

    ```bash
    poetry run pytest
    ```

4. Run scripts:

    ```bash
    poetry run cli_poetry_app
    poetry run cli_poetry_app greet "World"
    poetry run cli_poetry_app add 3 4
    ```

5. Install the application in editable mode:

    ```bash
    poetry shell
    ```

6. Run the application:

    ```bash
    cli_poetry_app
    cli_poetry_app greet "World"
    cli_poetry_app add 3 4
    ```

