# Repository Guidelines

## Project Structure & Module Organization

This workspace currently contains no application code, dependency manifest, tests, or assets. Establish the layout when adding the first implementation:

- `src/`: application code, grouped by feature or responsibility.
- `tests/`: automated tests, mirroring source modules where practical.
- `assets/`: static resources required by the application.
- `docs/`: architecture notes and contributor documentation.

These are proposed locations; create directories only when needed. Keep project configuration and a setup `README.md` at the repository root.

## Build, Test, and Development Commands

No build system, package manager, or executable development commands are configured. When selecting tooling, document exact installation, local development, build, test, lint, and formatting commands in `README.md` and update this guide. Verify those commands from a clean checkout. Commit the appropriate dependency lockfile when introducing a package manager.

## Coding Style & Naming Conventions

No language or formatting convention has been established. Follow the selected language’s standard conventions and configure a formatter and linter alongside the first code. Use consistent indentation, descriptive names, and small modules with clear responsibilities. Match existing naming patterns as the codebase develops, and avoid unrelated formatting changes.

## Testing Guidelines

No testing framework or coverage threshold exists yet. Introduce tests with the first executable behavior, covering expected results, edge cases, and failure paths. Use descriptive test names and the chosen framework’s standard file naming. Document the full test command and how to run an individual test.

## Commit & Pull Request Guidelines

This workspace has no Git metadata, so existing commit conventions cannot be inferred. Once Git is initialized, use concise, imperative subjects such as `Add room creation validation`. Keep commits focused on one coherent change.

Pull requests should explain the purpose, summarize behavior changes, link relevant issues, and report validation performed. Include screenshots for visible interface changes and disclose checks that were not run.

## Security & Configuration

Keep credentials, local environment files, and generated artifacts out of version control. Document required configuration using placeholder values in an example file when configuration is introduced.
