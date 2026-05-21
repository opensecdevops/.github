# Contributing to OSDO

Thank you for your interest in contributing to the Open SecDevOps framework!

## Code of Conduct

This project adheres to a [Code of Conduct](https://github.com/opensecdevops/osdo/blob/main/CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## How to Contribute

### Reporting Bugs

1. Check [existing issues](https://github.com/opensecdevops/osdo/issues) first
2. Use the bug report template when creating a new issue
3. Include steps to reproduce, expected behavior, and actual behavior
4. Include your environment details (OS, tool versions)

### Suggesting Features

1. Open a feature request issue using the template
2. Explain the use case and expected behavior
3. Indicate if you're willing to implement it

### Submitting Changes

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Make your changes following our coding standards
4. Write or update tests as needed
5. Commit with conventional commits: `feat:`, `fix:`, `docs:`, `chore:`
6. Push and open a Pull Request

### Commit Convention

We use [Conventional Commits](https://www.conventionalcommits.org/):

- `feat: add new scanning rule` — New feature
- `fix: correct false positive in SAST` — Bug fix
- `docs: update getting started guide` — Documentation
- `chore: update dependencies` — Maintenance
- `security: patch CVE-2026-XXXX` — Security fix

### Development Setup

```bash
# Clone the specific component you want to work on
git clone https://github.com/opensecdevops/COMPONENT.git
cd COMPONENT

# Follow the README for component-specific setup
```

### Pull Request Guidelines

- Fill out the PR template completely
- Link related issues
- Ensure CI passes
- Request review from maintainers
- Keep PRs focused — one feature or fix per PR

## Security

If you discover a security vulnerability, please follow our [Security Policy](SECURITY.md) instead of opening a public issue.

## License

By contributing, you agree that your contributions will be licensed under the MIT License.
