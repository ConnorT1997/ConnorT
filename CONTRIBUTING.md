# Contributing to Connor T's Portfolio

Thank you for your interest in contributing to this portfolio! This document provides guidelines for contributing to the projects within this repository.

## 🌟 How to Contribute

### Reporting Issues

If you find a bug, have a question, or want to suggest an improvement:

1. **Search existing issues** to avoid duplicates
2. **Open a new issue** with a clear title and description
3. **Include relevant details:**
   - Steps to reproduce (for bugs)
   - Expected vs. actual behavior
   - Environment details (OS, Python version, etc.)
   - Screenshots or error messages (if applicable)

### Suggesting Enhancements

Enhancement suggestions are welcome! Please:

1. **Check existing issues** to see if it's already suggested
2. **Describe the enhancement** clearly
3. **Explain the use case** and potential benefits
4. **Consider implementation** if you have ideas

### Pull Requests

We accept pull requests for bug fixes, enhancements, and documentation improvements.

#### Process

1. **Fork the repository** and create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b fix/your-bug-fix
   ```

2. **Make your changes:**
   - Write clear, commented code
   - Follow existing code style and conventions
   - Add tests if applicable
   - Update documentation as needed

3. **Test your changes:**
   - Ensure all existing tests pass
   - Add new tests for new functionality
   - Verify code runs without errors

4. **Commit your changes:**
   ```bash
   git commit -m "Brief description of changes"
   ```
   - Use clear, descriptive commit messages
   - Reference issue numbers if applicable (e.g., "Fixes #123")

5. **Push to your fork:**
   ```bash
   git push origin feature/your-feature-name
   ```

6. **Open a Pull Request:**
   - Provide a clear title and description
   - Link to related issues
   - Explain what changed and why
   - Include screenshots for UI changes

## 💻 Development Guidelines

### Code Style

- **Python:** Follow PEP 8 guidelines
  - Use 4 spaces for indentation
  - Maximum line length: 88 characters (Black formatter)
  - Use meaningful variable and function names
  - Add docstrings for functions and classes

- **Notebooks:** 
  - Use markdown cells to explain analysis
  - Clear outputs before committing
  - Keep cells focused and well-organized

### Project Structure

When adding new code, follow the existing structure:

```
projects/<project-name>/
├── README.md           # Project-specific documentation
├── src/                # Source code
├── notebooks/          # Jupyter notebooks (if applicable)
├── tests/              # Unit tests (if applicable)
├── assets/             # Images, data samples, etc.
└── requirements.txt    # Python dependencies
```

### Dependencies

- Add new dependencies to `requirements.txt` in the relevant project folder
- Pin major versions to ensure reproducibility
- Document why new dependencies are needed

### Testing

- Write unit tests for new functionality
- Ensure tests are isolated and reproducible
- Use meaningful test names that describe what's being tested
- Run tests locally before submitting PR

### Documentation

- Update README files when changing functionality
- Add comments for complex logic
- Include docstrings for public functions and classes
- Update project documentation if structure changes

## 🔍 Code Review Process

1. Maintainers will review your PR within a reasonable timeframe
2. Feedback may be provided for improvements
3. Once approved, your PR will be merged
4. You'll be credited as a contributor!

## 📋 Checklist for Contributors

Before submitting a pull request, ensure:

- [ ] Code follows project style guidelines
- [ ] All tests pass
- [ ] New functionality includes tests
- [ ] Documentation is updated
- [ ] Commit messages are clear
- [ ] No sensitive data (API keys, credentials) in code
- [ ] .gitignore updated if needed

## ❓ Questions?

If you have questions about contributing:

- Open an issue with the "question" label
- Check existing documentation
- Review closed issues and PRs for similar topics

## 🙏 Recognition

All contributors will be recognized in the project. Thank you for helping improve this portfolio!

## 📜 License

By contributing, you agree that your contributions will be licensed under the same license as this project (see [LICENSE](LICENSE)).

---

Thank you for contributing! Your efforts help make this portfolio better for everyone. 🚀
