# Contributing to MacetDym

Thank you for considering contributing to MacetDym! This document outlines the process for contributing to the project and how to report issues.

## Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](./CODE_OF_CONDUCT.md).

## How Can I Contribute?

### Reporting Bugs

If you find a bug in the application:

1. Check if the issue already exists in the [GitHub issues](https://github.com/yourusername/macetdym/issues)
2. If it doesn't exist, create a new issue using the bug report template
3. Include detailed steps to reproduce the bug
4. Include screenshots if applicable
5. Describe the expected behavior vs. the actual behavior

### Suggesting Enhancements

Have an idea to improve MacetDym?

1. Check if the enhancement has already been suggested in the [GitHub issues](https://github.com/yourusername/macetdym/issues)
2. If it hasn't, create a new issue using the feature request template
3. Clearly describe the enhancement and the value it adds
4. If possible, outline a potential implementation approach

### Pull Requests

1. Fork the repository
2. Create a new branch for your feature (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Run tests to ensure your changes don't break existing functionality
5. Commit your changes (`git commit -m 'Add some amazing feature'`)
6. Push to the branch (`git push origin feature/amazing-feature`)
7. Open a Pull Request

## Development Setup

1. Clone the repository
   ```
   git clone https://github.com/yourusername/macetdym.git
   cd macetdym
   ```

2. Install dependencies
   ```
   npm install
   ```

3. Start the development server
   ```
   npm run dev
   ```

### Project Structure

- `/client` - React frontend
  - `/src/components` - UI components
  - `/src/context` - React context providers
  - `/src/lib` - Utility functions
  - `/src/pages` - Application pages
- `/server` - Express backend
  - `routes.ts` - API endpoints
  - `storage.ts` - Data storage implementation
- `/shared` - Shared code between frontend and backend

## Coding Standards

- Use TypeScript for type safety
- Follow the existing code style
- Write unit tests for new features
- Document public APIs

### TypeScript Guidelines

- Use proper type annotations for function parameters and return values
- Avoid using `any` when possible
- Prefer interfaces for object types

### React Guidelines

- Use functional components with hooks
- Prefer controlled components
- Keep components small and focused
- Use context for state that needs to be accessed by multiple components

## Documentation

- Update README.md with details of changes to the interface
- Update documentation in the code when necessary
- Add JSDoc comments to functions and classes

## Testing

- Write tests for new features
- Run all tests before submitting a pull request
- Ensure all tests pass

## Git Workflow

- Keep commits small and focused
- Write clear commit messages that explain the "why" not just the "what"
- Rebase your branch on the latest main branch before submitting a PR

## License

By contributing to MacetDym, you agree that your contributions will be licensed under the project's [MIT License](./LICENSE).

Thank you for contributing to MacetDym! Your efforts help improve traffic management in Jakarta through decentralized technology.