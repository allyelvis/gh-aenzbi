# gh-aenzbi

## Overview
`gh-aenzbi` is a GitHub CLI extension designed to enhance your workflow with powerful commands for Continuous Integration/Continuous Deployment (CI/CD) integration, linting, testing, issue management, and repository scaffolding. It aims to streamline common development tasks and improve productivity.

## Features
- **CI/CD Integration**: Easily set up workflows with customizable options tailored to your project needs.
- **Linting and Testing**: Configure linting rules, automatically fix issues, and generate code coverage reports.
- **Collaboration Tools**: Simplify the management of issues and pull requests for better team collaboration.
- **Repository Management**: Quickly initialize and scaffold new projects with predefined templates.

## Installation
To install the extension, run the following command:

```bash
gh extension install allyelvis/gh-aenzbi
```

## Commands
### CI/CD Commands
- `gh aenzbi ci setup`: Guides the user through setting up a CI/CD workflow with their preferred provider.

### Linting Commands
- `gh aenzbi lint [--fix]`: Lints the code and automatically fixes any fixable issues. Use `--fix` to apply fixes.

### Testing Commands
- `gh aenzbi test [--coverage]`: Runs tests and generates a code coverage report. Use `--coverage` to include coverage metrics.

### Issue Management
- `gh aenzbi issue create [--template <template-name>]`: Creates a new issue using a pre-defined template. Available templates include `bug-report` and `feature-request`.

### Repository Management
- `gh aenzbi repo init [--template <template-name>]`: Initializes a new repository with a basic structure based on the specified template. Available templates include `react-app`, `node-api`, and `python-lib`.

## Usage Examples
- Set up a CI/CD workflow:
  ```bash
  gh aenzbi ci setup
  ```

- Lint your code and fix issues:
  ```bash
  gh aenzbi lint --fix
  ```

- Run tests with coverage:
  ```bash
  gh aenzbi test --coverage
  ```

- Create a bug report issue:
  ```bash
  gh aenzbi issue create --template bug-report
  ```

- Initialize a new React app repository:
  ```bash
  gh aenzbi repo init --template react-app
  ```

## Contributing
Contributions are welcome! If you have suggestions for improvements or features, please submit a pull request or open an issue for discussion.

## License
This project is licensed under the MIT License.

## Author
**Ally Elvis Nzeyimana**

```
