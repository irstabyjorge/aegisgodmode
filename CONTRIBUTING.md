# Contributing to AEGIS GOD MODE

Thank you for your interest in contributing to AEGIS GOD MODE! We welcome contributions from the community and appreciate your help in making this project better.

## Getting Started

1. **Fork the repository** -- Click the "Fork" button on the [AEGIS GOD MODE GitHub page](https://github.com/irstabyjorge/aegisgodmode) to create your own copy.

2. **Clone your fork:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/aegisgodmode.git
   cd aegisgodmode
   ```

3. **Install dependencies:**
   ```bash
   npm install
   ```

4. **Create a feature branch:**
   ```bash
   git checkout -b feature/your-feature-name
   ```
   Use a descriptive branch name. Prefix with `feature/`, `fix/`, `docs/`, or `refactor/` as appropriate.

## Development Workflow

### Code Style

- Follow the existing code style and conventions used throughout the project
- The project uses TypeScript -- ensure all new code is properly typed
- Run the linter before submitting:
  ```bash
  npm run lint
  ```
- Use meaningful variable and function names
- Add comments for complex logic, but prefer self-documenting code

### Testing

- Write tests for all new features and bug fixes
- Ensure all existing tests pass before submitting your pull request:
  ```bash
  npm test
  ```
- Aim for meaningful test coverage -- focus on critical paths and edge cases

### Commit Messages

- Write clear, concise commit messages
- Use the imperative mood (e.g., "Add feature" not "Added feature")
- Reference related issues where applicable (e.g., "Fix #42: resolve login timeout")

## Submitting a Pull Request

1. **Push your branch** to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```

2. **Open a Pull Request** against the `main` branch of the upstream repository.

3. **In your PR description**, include:
   - A clear summary of the changes
   - The motivation and context for the change
   - Any related issue numbers
   - Screenshots or examples (if applicable)

4. **Wait for review** -- A maintainer will review your PR. Be prepared to make revisions based on feedback.

## Important Guidelines

### No Secrets or Credentials

- **Never** commit API keys, passwords, tokens, or any sensitive credentials
- Use environment variables for configuration
- Check your changes carefully before committing to ensure no secrets are included
- If you accidentally commit a secret, notify the maintainers immediately

### Dual-License Terms

By submitting a contribution (pull request, patch, or any code) to this project, you agree to the following:

- Your contribution will be licensed under the same dual-license terms as the project: the MIT (Non-Commercial) License for non-commercial use, and the Commercial License for commercial use (see `LICENSE` and `COMMERCIAL_LICENSE.md`).
- You grant the project maintainer (Jorge Francisco Paredes / irstabyjorge) a perpetual, worldwide, non-exclusive, royalty-free, irrevocable license to use, reproduce, modify, distribute, sublicense, and commercially exploit your contribution as part of the Software.
- You represent that you have the legal right to grant this license and that your contribution is your original work (or you have permission to submit it under these terms).
- You understand that your contribution may be used in commercially licensed versions of the Software.

### Code of Conduct

- Be respectful and constructive in all interactions
- Focus on the technical merits of contributions
- Welcome newcomers and help them get started
- Disagreements about technical approaches should be resolved through discussion, not hostility

## What We Are Looking For

- Bug fixes with clear reproduction steps
- Performance improvements with benchmarks
- New features that align with the project goals
- Documentation improvements
- Test coverage improvements
- Accessibility enhancements

## Questions?

If you have questions about contributing, feel free to:

- Open a discussion on GitHub
- Contact the maintainer at IRSTAXBYJORGE@GMAIL.COM

---

*Thank you for contributing to AEGIS GOD MODE!*
