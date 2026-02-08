# Contributing to BlueprintKit

Thank you for your interest in contributing to BlueprintKit! This document provides guidelines and instructions for contributing to this project.

## Code of Conduct

By participating in this project, you agree to maintain a professional and respectful environment. We are committed to providing a welcoming and inclusive experience for all contributors.

## How to Contribute

### Reporting Issues

Before creating an issue, please:

1. Check if the issue already exists in the [Issues](https://github.com/JustineDevs/StarterPack/issues) section
2. Search for similar issues to avoid duplicates
3. Provide a clear title and description
4. Include steps to reproduce the issue (if applicable)
5. Add relevant labels if you have permission

### Suggesting Enhancements

We welcome suggestions for improvements! When suggesting an enhancement:

1. Open an issue with the `enhancement` label
2. Clearly describe the proposed feature or improvement
3. Explain the use case and benefits
4. Provide examples if possible

### Contributing Code

#### Getting Started

1. **Fork the repository**
   ```bash
   # Click the "Fork" button on GitHub, then clone your fork
   git clone https://github.com/YOUR_USERNAME/StarterPack.git
   cd StarterPack
   ```

2. **Set up the development environment**
   ```bash
   # Navigate to starter-pack directory
   cd starter-pack
   
   # Install dependencies
   npm install
   
   # Start development server
   npm run dev
   ```

3. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b fix/your-bug-fix
   ```

#### Making Changes

1. **Follow coding standards**
   - Use TypeScript for type safety
   - Follow ESLint and Prettier configurations
   - Write clear, descriptive commit messages
   - Add comments for complex logic

2. **Test your changes**
   ```bash
   # Run linter
   npm run lint
   
   # Run type checking
   npm run type-check
   
   # Run tests
   npm test
   ```

3. **Update documentation**
   - Update README.md if needed
   - Add JSDoc comments for new functions
   - Update relevant documentation files

4. **Commit your changes**
   ```bash
   # Use descriptive commit messages
   git commit -m "feat: add new feature description"
   git commit -m "fix: resolve issue description"
   git commit -m "docs: update documentation"
   ```

#### Commit Message Format

We follow conventional commit format:

- `feat:` - New feature
- `fix:` - Bug fix
- `docs:` - Documentation changes
- `style:` - Code style changes (formatting, etc.)
- `refactor:` - Code refactoring
- `test:` - Adding or updating tests
- `chore:` - Maintenance tasks

Example:
```
feat: add user authentication system
fix: resolve planning page path resolution
docs: update installation instructions
```

#### Submitting Changes

1. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

2. **Create a Pull Request**
   - Go to the original repository on GitHub
   - Click "New Pull Request"
   - Select your fork and branch
   - Fill out the PR template (if available)
   - Link any related issues

3. **PR Requirements**
   - Clear description of changes
   - Reference related issues (e.g., "Fixes #123")
   - All tests must pass
   - Code follows project standards
   - Documentation updated if needed

## Project Structure

### Monorepo Organization

This project is organized as a monorepo with two main components:

- **`skill/`** - Skills-only files for skills.sh
- **`starter-pack/`** - Complete starter pack with frontend

### Where to Make Changes

- **Frontend code**: `starter-pack/src/`
- **Documentation**: `starter-pack/docs/`
- **Skills**: `skill/.claude/skills/blueprintkit/`
- **Scripts**: `starter-pack/scripts/`
- **Configuration**: Root and `starter-pack/` directories

## Development Guidelines

### TypeScript

- Use TypeScript for all new code
- Avoid `any` types when possible
- Define proper interfaces and types
- Use type inference where appropriate

### Code Style

- Follow ESLint rules (run `npm run lint`)
- Use Prettier for formatting (run `npm run format`)
- Keep functions small and focused
- Use descriptive variable and function names

### Testing

- Write tests for new features
- Maintain or improve test coverage
- Test edge cases and error handling
- Run tests before submitting PRs

### Documentation

- Update README.md for user-facing changes
- Add JSDoc comments for public APIs
- Update relevant documentation files
- Keep examples up to date

## Review Process

1. **Automated Checks**: All PRs must pass CI/CD checks
2. **Code Review**: At least one maintainer will review your PR
3. **Feedback**: We may request changes or ask questions
4. **Approval**: Once approved, your PR will be merged

## Questions?

If you have questions about contributing:

- Open an issue with the `question` label
- Check existing documentation
- Review similar PRs for examples

## Recognition

Contributors will be recognized in:
- Project README (if significant contribution)
- Release notes (for major contributions)
- GitHub contributors page

Thank you for contributing to BlueprintKit!

