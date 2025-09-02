# Contributing to VENOM DRM Glass Template V3

Thank you for your interest in contributing to the VENOM DRM Glass Template V3 project! This document provides guidelines and procedures for contributing to the project.

## Table of Contents

1. [Code of Conduct](#code-of-conduct)
2. [Getting Started](#getting-started)
3. [Development Workflow](#development-workflow)
4. [Coding Standards](#coding-standards)
5. [Commit Message Guidelines](#commit-message-guidelines)
6. [Pull Request Process](#pull-request-process)
7. [Reporting Issues](#reporting-issues)

## Code of Conduct

This project adheres to a code of conduct that we expect all contributors to follow. Please treat all participants with respect and courtesy.

## Getting Started

1. Fork the repository
2. Clone your forked repository
3. Set up the development environment following the instructions in PROJECT_SPECIFICATION.md
4. Create a new branch for your feature or bug fix

## Development Workflow

### Branch Naming Convention

- Feature branches: `feat/<short-description>`
- Bugfix branches: `fix/<short-description>`
- Hotfix branches: `hotfix/<short-description>`
- Documentation branches: `docs/<short-description>`
- Refactor branches: `refactor/<short-description>`

### Development Process

1. Ensure your branch is up to date with the main branch
2. Make your changes following the project's coding standards
3. Write tests for your changes when applicable
4. Run the test suite to ensure nothing is broken
5. Commit your changes using Conventional Commits format
6. Push your changes to your fork
7. Create a pull request

## Coding Standards

### PHP Standards

- Follow PSR-12 coding standards
- Use Laravel Pint for code formatting
- Write clear, self-documenting code
- Include PHPDoc comments for all public methods and classes

### JavaScript Standards

- Follow ESLint configuration
- Use modern ES6+ syntax where appropriate
- Write modular, reusable code
- Include JSDoc comments for complex functions

### CSS/Tailwind Standards

- Use TailwindCSS utility classes primarily
- Create custom CSS only when necessary
- Follow the existing design system
- Maintain consistency with the Neon Glass aesthetic

### Blade Template Standards

- No inline CSS or JavaScript
- Use Blade components for reusable UI elements
- Follow the existing component structure
- Maintain accessibility standards

## Commit Message Guidelines

We follow the Conventional Commits specification. Commit messages must be in the format:

```
type(scope): description

[optional body]

[optional footer]
```

### Commit Types

- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting, missing semicolons, etc.)
- `refactor`: Code changes that neither fix a bug nor add a feature
- `perf`: Performance improvements
- `test`: Adding or modifying tests
- `build`: Changes that affect the build system or external dependencies
- `ci`: Changes to CI configuration files and scripts
- `chore`: Other changes that don't modify src or test files

### Examples

```
feat(reports): add admin notes functionality
fix(auth): check user status before login
docs(readme): update contribution guide
refactor(users): optimize user search query
```

## Pull Request Process

1. Ensure your branch is up to date with the main branch
2. Run all tests and ensure they pass
3. Write a clear, descriptive pull request title using Conventional Commits format
4. Provide a detailed description of the changes
5. Link any related issues
6. Request review from maintainers

### Pull Request Checklist

Before submitting your pull request, ensure you've completed the following:

- [ ] Code follows project coding standards
- [ ] No inline CSS/JS in Blade files
- [ ] No external CDN references
- [ ] Tests cover new/changed code
- [ ] Accessibility (WCAG) not broken
- [ ] CI/CD pipeline passes
- [ ] Code is properly documented
- [ ] Commit messages follow Conventional Commits

### Pull Request Review Process

1. All pull requests require review by at least one maintainer
2. Automated checks must pass before review
3. Reviewers may request changes or approve the pull request
4. Once approved, maintainers will merge the pull request

## Reporting Issues

### Before Creating an Issue

1. Check if the issue already exists
2. Ensure you're using the latest version of the project
3. Try to reproduce the issue

### Creating an Issue

When creating an issue, please include:

1. A clear, descriptive title
2. Detailed steps to reproduce the issue
3. Expected behavior
4. Actual behavior
5. Environment information (PHP version, Laravel version, etc.)
6. Any relevant screenshots or error messages

### Issue Types

- **Bug Report**: Something isn't working as expected
- **Feature Request**: A new feature or enhancement
- **Documentation**: Issues with documentation
- **Question**: Questions about the project or implementation

## Additional Resources

- [Project Specification](PROJECT_SPECIFICATION.md)
- [Implementation Plan](PROJECT_PLAN.md)
- [README](README.md)

Thank you for contributing to VENOM DRM Glass Template V3!