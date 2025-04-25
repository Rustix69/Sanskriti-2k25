# Contributing to Sanskriti-2k25

Thank you for your interest in contributing to Sanskriti-2k25! We welcome contributions from everyone, whether you're fixing a typo, adding a feature, or reporting a bug.

## Getting Started

1. **Fork the repository** on GitHub.
2. **Clone your fork** to your local machine:
   ```bash
   git clone https://github.com/YOUR-USERNAME/Sanskriti-2k25.git
   cd Sanskriti-2k25
   ```
3. **Set up the development environment** by following the instructions in the README.md or by running the setup script:
   ```bash
   ./setup.sh
   ```

## Development Workflow

1. **Create a new branch** for your feature or bugfix:
   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b bugfix/the-bug-name
   ```

2. **Make your changes** and ensure they follow our coding standards.

3. **Test your changes** locally to make sure everything works as expected.

4. **Commit your changes** with a descriptive commit message:
   ```bash
   git add .
   git commit -m "Add feature: your feature description"
   ```

5. **Push your changes** to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```

6. **Create a Pull Request** from your fork to the main repository.

## Coding Standards

- Follow the existing code style and conventions
- Use TypeScript type annotations where applicable
- Format your code using Prettier (configuration is in the repository)
- Write meaningful commit messages

## Component Guidelines

When creating or modifying components:

1. **Follow the component organization structure**:
   - UI components in `src/components/ui`
   - Page-specific components in their respective feature directories
   - Shared components in `src/components/common`

2. **Use Tailwind CSS** for styling:
   - Prefer Tailwind utility classes over custom CSS
   - Use composition with `cn()` utility for conditional classes

3. **Make components accessible**:
   - Use semantic HTML elements
   - Add proper ARIA attributes when necessary
   - Ensure keyboard navigation works

## Pull Request Process

1. Update the README.md or documentation if needed
2. Make sure all tests pass
3. Ensure the code follows our style guidelines
4. Link any related issues in the pull request description
5. Request a review from a maintainer

## Reporting Bugs

When reporting bugs, please include:

- A clear and descriptive title
- Steps to reproduce the issue
- Expected behavior
- Actual behavior
- Screenshots if applicable
- Your environment details (browser, OS, etc.)

## Feature Requests

We welcome suggestions for new features. Please provide:

- A clear description of the feature
- Any relevant use cases
- How the feature would benefit the project

## Questions?

If you have any questions, feel free to create an issue with the "question" label or reach out to the maintainers.

Thank you for contributing to Sanskriti-2k25! 