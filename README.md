# Seia-Soto/Typescript-Boilerplate

A new awesome project! ✨

## Table of Contents

- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Scripts](#scripts)
  - []
- [License](#license)

----

# Getting started

This repository requires following pre-dependencies to be installed:

- Node.JS LTS RC
- NPM
- Yarn
- Git

Also, this repository includes following utilities:

- Yarn berry
- Husky
- ESLint with Standard.JS (TypeScript support)
- TypeScript
- GitHub Actions
  - workflows
    - changelog-rc.yml, when prerelease created, this updates its body with current changelog.
    - codeql-analysis.yml, when commit pushed, this runs codeql analysis for security.
    - eslint.yml, when commit pushed or PR created, this runs eslint for code style.
  - lock.yml, when issue is determinded as OLD, this locks the issue. (90 days)
  - no-response.yml, when issue is determined as OLD, this closes the issue. (28 days)

## Installation

To start with this project, put following commands:

```sh
yarn
```

## Scripts

### `yarn lint`

Runs ESLint, to fix errors attach `--fix` at the end of command.

### `yarn build`

Build this project into single JavaScript file, for configuration please refer [tsconfig.json](/tsconfig.json).

### `yarn changelog`

Generates new changelog into CHANGELOG.md file.

# LICENSE

This project is distributed with [MIT License](./LICENSE).
