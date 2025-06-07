# Contributing to BOPPA

BOPPA is not currently accepting external contributions.

This organization is a tight team working on private and internal projects. If you’re part of the team, read below.

## 🚀 Getting Started

1. **Fork the repository** and create your branch from `main`
2. **Set up your development environment** following the project's README
3. **Install dependencies** and ensure all tools are working
4. **Run tests** to make sure everything is working before you start

## 🔄 Development Workflow

We follow **GitHub Flow** for most projects:

1. Create a feature branch from `main`
2. Make your changes with clear, descriptive commits
3. Push your branch and create a Pull Request
4. Address any feedback from code review
5. Once approved, your PR will be merged

## 📝 Code Standards

### General Guidelines

- Write clear, readable code with meaningful variable names
- Add comments for complex logic or business rules
- Keep functions small and focused on a single responsibility
- Follow the existing code style in the project

### Language-Specific Standards

#### Web Development (JavaScript/TypeScript)

- **Prettier** is required for code formatting
- Run `npm run format` or `yarn format` before committing
- Use modern ES6+ syntax when possible
- Follow semantic HTML practices

#### Python

- **Black** is required for code formatting
- Run `black .` before committing
- Follow PEP 8 guidelines
- Use type hints when appropriate

### File Structure

- Keep related files organized in logical directories
- Use clear, descriptive file names
- Include a README in each major directory explaining its purpose

## 🧪 Testing Requirements

### Unit Testing

- **All new features must include unit tests**
- Aim for meaningful test coverage, not just high percentages
- Test both happy paths and edge cases
- Use descriptive test names that explain what is being tested

### Test Commands

- JavaScript: `npm test` or `yarn test`
- Python: `pytest` or `python -m pytest`

### CI/CD

- All tests must pass before merging
- CI/CD pipelines are preferred when applicable
- Ensure your changes don't break existing functionality

## 📋 Commit Guidelines

Use the [Conventional Commits](https://www.conventionalcommits.org/) style:

### Commit Message Format

```
type(scope): brief description

Longer explanation if needed, including:
- What changed and why
- Any breaking changes
- Links to relevant issues
```

### Commit Types

- `feat:` - new feature
- `fix:` - bug fix
- `docs:` - documentation changes
- `test:` - adding or updating tests
- `refactor:` - code refactoring

### Examples

```
feat(auth): add user login functionality

Implements basic email/password authentication with JWT tokens.
Includes input validation and error handling.

Closes #23
```

## 🐛 Reporting Issues

Use our issue templates to report:

- **Bug Reports** - for problems with existing functionality
- **Feature Requests** - for new capabilities
- **MVP Proposals** - for new project ideas
- **MVP Planning** - for structured project planning after an MVP proposal has been approved

## 📚 Learning and Knowledge Sharing

### Documentation

- Document your learning process in PR descriptions
- Share interesting discoveries or solutions in comments
- Update project documentation when you learn something new
- Create or update README files for better onboarding

### Code Reviews

- Use reviews as learning opportunities
- Ask questions if you don't understand something
- Explain your reasoning behind implementation choices
- Be open to feedback and alternative approaches

## 🆘 Getting Help

- **Create an issue** for bugs or feature requests
- **Ask questions** in PR comments or reviews
- **Document solutions** you find for others
- **Share resources** that helped you learn

## 📞 Contact

For questions about contributing or project direction, reach out to the lead developer through GitHub issues or PR comments.

---

Thank you for contributing to BOPPA! Every contribution helps us learn, grow, and build better products together. 🚀
