# CLAUDE.md

This file provides guidance for AI assistants working on this repository.

## Repository Overview

**hello-world** is a minimal introductory GitHub repository created by tschussl (Trent Schussler) in April 2016. It serves as a learning/demonstration project for Git and GitHub workflows. There is no application code — the repository contains only documentation.

## Repository Structure

```
hello-world/
├── README.md       # Project description (sole source file)
└── CLAUDE.md       # This file
```

## Project State

- **Language/Framework**: None — no source code exists
- **Dependencies**: None
- **Build system**: None
- **Tests**: None
- **CI/CD**: None

## Git Workflow

This repository follows a simple GitHub-style branching model:

- `master` — stable, default branch
- Feature branches (e.g., `readme-edits`) are created for changes and merged via pull requests

### Branch Naming

Claude-managed branches follow the pattern: `claude/<description>-<session-id>`

### Commit Style

Commits in this repository use short, lowercase imperative messages:

```
Initial commit
finish read me
```

Keep commit messages concise and descriptive of the actual change.

### Common Git Commands

```bash
# Check current branch and status
git status

# Create and switch to a new branch
git checkout -b <branch-name>

# Stage and commit changes
git add <file>
git commit -m "description of change"

# Push branch to remote
git push -u origin <branch-name>
```

## Development Guidelines

Since this repository has no code, any future additions should:

1. Add a source file appropriate to the chosen language/framework
2. Include a dependency manifest if external libraries are needed
3. Set up a test suite before adding logic
4. Update this CLAUDE.md to reflect the new structure and workflows

## Making Changes

When editing this repository:

- **README.md**: The only existing content file. Keep edits consistent with its casual, brief tone.
- **New files**: Add them to the root or create subdirectories only when there is enough content to warrant organization.
- There are no linters, formatters, or pre-commit hooks to satisfy.

## Remote Configuration

- Remote name: `origin`
- Repository: `tschussl/hello-world`
