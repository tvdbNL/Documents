# Copilot Agent Instructions: Conventional Commit Messages

## Purpose
These instructions guide AI agents to generate and review commit messages that follow the Conventional Commits specification in this repository.

## Commit Message Format
Each commit message must be structured as follows:

```
<type>[optional scope]: <short summary>

[optional body]

[optional footer(s)]
```

### 1. Types
Use one of the following types:
- feat:     A new feature
- fix:      A bug fix
- docs:     Documentation only changes
- style:    Changes that do not affect meaning (formatting, missing semi-colons, etc.)
- refactor: Code change that neither fixes a bug nor adds a feature
- perf:     Code change that improves performance
- test:     Adding or correcting tests
- build:    Changes that affect the build system or dependencies
- ci:       Changes to CI configuration files and scripts
- chore:    Other changes that don't modify src or test files
- revert:   Reverts a previous commit

### 2. Scope (optional)
- Use parentheses to specify the area affected, e.g., `feat(markdown): ...`
- Scope should be a file, feature, or module name

### 3. Summary
- Use the imperative mood: "fix", "add", "update", not "fixed" or "adds"
- Keep under 50 characters
- Be specific and concise

### 4. Body (optional)
- Explain the motivation and context for the change
- Wrap lines at 72 characters

### 5. Footer (optional)
- Reference issues, breaking changes, or other notes

## Examples
- `docs(markdown): fix heading levels and typos`
- `feat(spellcheck): add grammar validation for .md files`
- `fix: correct broken image links in documentation`
- `chore: update copilot-instructions.md with review checklist`

## References
- [Conventional Commits v1.0.0](https://www.conventionalcommits.org/en/v1.0.0/)

---

All commit messages must follow this format for clarity and automation compatibility.
