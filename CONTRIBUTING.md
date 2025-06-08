# Contributing to BOPPA

BOPPA is not currently accepting external contributions.

This organization is a tight team working on private and internal projects. If you're part of the team, read below.

## 💡 Got an Idea? Start Here!

**Everyone can contribute - coding skills not required!**

### For New Project Ideas

If you have an idea for a completely new project, improvement, or solution:

1. **Visit our [Project-Proposals](https://github.com/BOPPALabs/Project-Proposals) repository**
2. **Create a new issue** using the `💭 MVP Proposal` template
3. **Share your idea** - the rest of the team will help with the technical details!

### For Existing Projects

If you want to suggest features, improvements, or report bugs for projects that already have their own dedicated repositories:

1. **Navigate to the specific project's repository**
2. **Create an issue** using the appropriate template:
   - `✨ Feature Request` for new features
   - `⚠️ Bug Report` if something isn't working as expected
3. **Describe your idea or issue** - no coding knowledge needed!

Your business insights, user experience ideas, and problem-solving perspectives are just as valuable as code. Many of our best projects started as non-technical ideas that sparked great technical solutions.

## 🚀 Getting Started (For Development)

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

## 🐛 Reporting Issues & Ideas

### For Code Issues (in individual project repos)

Use our issue templates to report:

- **⚠️ Bug Reports** - for problems with existing functionality
- **✨ Feature Requests** - for new capabilities

### For New Project Ideas (in Project-Proposals repo)

- **💭 MVP Proposals** - for new project ideas (anyone can contribute!)
- **📋 MVP Planning** - for detailed planning of approved proposals

## 🎯 Contributing Without Coding

### Business & Strategy

- **Identify problems** worth solving with technology
- **Research market needs** and user pain points
- **Propose solutions** using the MVP Proposal template
- **Provide feedback** on proposed projects and priorities

### User Experience & Design

- **Share user experience insights** from your domain expertise
- **Suggest interface improvements** for existing projects
- **Identify usability issues** and propose solutions
- **Contribute to planning** by defining user requirements

### Documentation & Communication

- **Improve project documentation** and README files
- **Create user guides** and tutorials
- **Write project descriptions** that explain technical concepts clearly
- **Help with project naming** and messaging

### Testing & Feedback

- **Test applications** and provide detailed feedback
- **Report bugs** using our issue templates
- **Suggest improvements** based on real-world usage
- **Validate project ideas** from a business perspective

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

### Cross-Functional Collaboration

- **Developers**: Explain technical concepts clearly to non-technical team members
- **Non-technical contributors**: Share domain expertise and user perspectives
- **Everyone**: Ask questions and contribute ideas regardless of technical background

## 🆘 Getting Help

- **For project ideas**: Create an issue in [Project-Proposals](https://github.com/BOPPALabs/Project-Proposals)
- **For code bugs**: Create an issue in the relevant project repository
- **For questions**: Ask in PR comments, issue discussions, or team channels
- **For learning**: Document your process and ask for guidance from the team

## 🤝 Our Philosophy

We believe the best projects come from diverse perspectives. Whether you contribute code, ideas, feedback, or domain expertise, your input helps make our projects better. Don't hesitate to contribute just because you're not sure about the technical implementation - that's what the team is for!
