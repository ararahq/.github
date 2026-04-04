# Contributing to AraraHQ

Thanks for your interest in contributing! Here's how to get started.

## Getting Started

1. **Fork** the repository
2. **Clone** your fork locally
3. Create a **feature branch**: `git checkout -b feat/your-feature`
4. Make your changes
5. **Test** your changes
6. **Commit** with a clear message (see below)
7. **Push** to your fork and open a **Pull Request**

## Commit Messages

We use conventional commits. No emojis, no fluff.

```
feat(scope): add new feature
fix(scope): fix the bug
refactor(scope): restructure code
test(scope): add tests
docs(scope): update documentation
chore(scope): maintenance task
```

## Code Style

- Write clean, readable code
- Use meaningful variable and function names (no abbreviations like `e`, `req`, `usr`)
- Prefer immutable variables (`const`, `val`, `final`)
- Use early returns to avoid deep nesting
- Keep functions small (under 25 lines ideally)

## Pull Requests

- Keep PRs focused on a single change
- Write a clear title and description
- Ensure all tests pass before submitting
- Link any related issues

## Reporting Issues

- Use GitHub Issues to report bugs
- Include steps to reproduce
- Include expected vs actual behavior
- Include your environment (language version, OS, SDK version)

## Questions?

- Check our [documentation](https://docs.ararahq.com)
- Open a GitHub Issue

## License

By contributing, you agree that your contributions will be licensed under the MIT License.
