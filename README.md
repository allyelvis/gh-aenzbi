# aenzbi-artist

**aenzbi-artist** is a GitHub CLI extension designed to enhance your GitHub workflow by providing powerful commands for CI/CD setup, code linting, testing, issue management, pull requests, and repository scaffolding.

## Features

- **CI/CD Integration**: Set up workflows for popular CI/CD providers like GitHub Actions and GitLab CI/CD.
- **Linting**: Automatically lint your code and fix issues with a single command.
- **Testing**: Run tests with optional code coverage reporting to ensure code quality.
- **Issue Management**: Easily create new GitHub issues using predefined templates.
- **Pull Request Management**: Streamline the process of creating and managing pull requests.
- **Repository Scaffolding**: Quickly initialize new repositories with project templates and boilerplate code.

## Installation

To install **aenzbi-artist**, ensure you have the [GitHub CLI](https://cli.github.com/) installed. You can then install this extension using the following command:

```bash
gh extension install allyelvis/aenzbi-artist
```

## Usage

Here’s a quick overview of the available commands:

```bash
# Set up CI/CD for your project
gh aenzbi ci setup

# Lint the code
gh aenzbi lint [--fix]

# Run tests
gh aenzbi test [--coverage]

# Create a new issue
gh aenzbi issue create [--template <template>] [options]

# Create a new pull request
gh aenzbi pr create [options]

# Initialize a new repository with a template
gh aenzbi repo init --template <template>

# Scaffold a new project component
gh aenzbi scaffold --type <type>
```

For detailed information on each command, run:

```bash
gh aenzbi <command> --help
```

## Development

To contribute to **aenzbi-artist**, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/allyelvis/aenzbi-artist.git
   cd aenzbi-artist
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Run tests to ensure everything is working correctly:

   ```bash
   npm test
   ```

4. Make your changes and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [GitHub CLI](https://cli.github.com/) for the underlying command-line interface.
- All contributors for their valuable input and feedback.
