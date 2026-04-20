 Contributing to ssmctl

Thank you for your interest in contributing to ssmctl! This document outlines the standards and expectations for all contributions.

## Prerequisites

- [Go 1.25+](https://golang.org/dl/)
- [GNU Make](https://www.gnu.org/software/make/)

## Getting Started

After cloning the repository, run the one-time setup:

TODO: Finish

## Code Style

- Follow standard [Go conventions](https://go.dev/doc/effective_go) and the [Go Code Review Comments](https://github.com/golang/go/wiki/CodeReviewComments) guide.

TODO: Finish

## Testing Standards

TODO: Finsh

## Commit Messages

All commit messages must follow the format:

```
<type>(<scope>): <message>
```

Use the imperative mood in `<message>` (e.g., "add support for..." not "added support for..."). Keep the subject line under 72 characters. Separate subject from body with a blank line, and use the body to explain *what* and *why*, not *how*.

### Types

| Type | Purpose |
|------|---------|
| `feat` | New feature or user-facing functionality |
| `fix` | Bug fix |
| `refactor` | Code change that neither fixes a bug nor adds a feature |
| `test` | Adding or updating tests |
| `chore` | Maintenance, tooling, CI, dependencies, or documentation |
| `perf` | Performance improvement |
| `style` | Code formatting (no logic changes) |
| `ci` | CI/CD configuration changes |
| `release` | Release config updates |