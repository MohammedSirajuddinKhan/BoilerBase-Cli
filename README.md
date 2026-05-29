# BoilerBase

> Generate a backend starter project from the terminal in seconds.

[![npm version](https://img.shields.io/npm/v/boilerbase.svg)](https://www.npmjs.com/package/boilerbase)
[![npm downloads](https://img.shields.io/npm/dm/boilerbase.svg)](https://www.npmjs.com/package/boilerbase)


BoilerBase is a fast, interactive CLI for scaffolding backend projects with an opinionated starter structure. It asks a few setup questions, generates the files for you, installs dependencies, and can open the result in VS Code.

## Features

- Interactive terminal prompts for project setup
- Generates folders and starter files automatically
- Installs dependencies after generation
- Optional VS Code launch for the new project
- Clean, modular structure for extending templates later

## Install

Install it globally for local development:

```bash
npm install
npm link
```

Or run it directly with `npx` once published:

```bash
npx boilerbase
```

## Usage

Start the CLI from the terminal:

```bash
boilerbase
```

You will be prompted for things like:

- Project name
- Database choice
- Authentication style
- Template engine
- CSS framework
- Whether to open VS Code after generation

## Example

```bash
boilerbase
```

Then answer the prompts and BoilerBase will create a project in your current directory.

## What gets generated

The generated starter includes:

- Express server scaffold
- Optional MongoDB config
- JWT auth routes and middleware
- EJS or HTML views
- CSS starter file and public assets
- Environment and package setup

## Publish

To publish a new version to npm:

```bash
npm version patch
npm publish --otp=123456
```

If your account uses 2FA, you can also publish with a granular access token that has `bypass 2fa` enabled.

## Tech Stack

- Node.js
- inquirer
- chalk
- ora
- fs-extra

## License

MIT
