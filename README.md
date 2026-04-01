<p align="center">
    <img src=".github/logo.png" title="Project logo"><br />
    <img src="https://img.shields.io/maintenance/yes/2026?style=for-the-badge" title="Project status">
</p>

# Prompt Library

This repository contains public prompts for software development and related technical activities. Prompts are versioned as Markdown files so they can be reviewed, improved, and maintained over time.

The goal of this repository is to keep prompt instructions explicit, maintainable, and easy to locate by technology and task type.

## What Is In This Repository

Prompts are organized by domain and activity. The current structure is:

```text
dev/
  laravel/
    review-laravel-pr.md
```

Current prompt set:

- `dev/laravel/review-laravel-pr.md`: instructions for reviewing Laravel pull requests with a strict high-signal review policy.

## How The Repository Is Organized

Use this convention when adding new prompts:

```text
<area>/<domain>/<prompt-name>.md
```

Examples:

- `dev/laravel/review-laravel-pr.md`
- `dev/frontend/plan-landing-page.md`
- `dev/backend/debug-api-timeouts.md`

This keeps prompts grouped first by broad area and then by technology or domain. The filename should describe the task clearly.

## License

This project is private property of [Optidata](https://www.optidata.com).
