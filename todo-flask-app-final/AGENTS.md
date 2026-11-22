AGENTS.md

1. Project Purpose

This project is a TodoList web application built with Python and Flask. It allows users to create, view, update and delete tasks. The application uses SQLite as its database.

2. Project Architecture

The project contains the following main components:

* app.py - Flask application, frontend routes and REST API.
* db.py - Database connection and CRUD operations.
* schema.sql - SQLite database schema.
* tests/test_task.py - Automated tests using pytest.
* templates/ - HTML templates.
* static/ - Static frontend files.

3. Technologies

* Python
* Flask
* SQLite
* Pytest
* HTML, CSS and JavaScript

4. Setup and Execution

1. Activate the Python virtual environment.
2. Install dependencies listed in the project requirements file.
3. Initialize the database using the application.
4. Run the application using:

python app.py

5. Testing

Run automated tests using:

python -m pytest -v

All existing tests must pass after code modifications.

New functionality should include appropriate automated tests.

6. Coding Conventions

* Follow standard Python naming conventions.
* Use clear and descriptive function names.
* Keep database operations inside db.py.
* Keep HTTP routes and request handling inside app.py.
* Use parameterized SQL queries.
* Avoid unnecessary code duplication.
* Keep changes small and focused.

7. Safety Rules and Forbidden Actions

The AI agent must follow these restrictions:

* Never expose passwords, API keys or other secrets.
* Never delete the original project files without approval.
* Never execute destructive database operations without permission.
* Never deploy the application to production.
* Never install or update dependencies without human approval.
* Never modify unrelated files.
* Never accept generated code without reviewing it.
* Never remove existing tests to make the test suite pass.

8. Review Requirements

Before accepting any modification:

1. Review the proposed code changes.
2. Check that existing functionality is preserved.
3. Run the automated test suite.
4. Review test results.
5. Obtain human approval before finalizing changes.