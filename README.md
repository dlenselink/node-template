# General Purpose Node Template

This template provides a good starting point for any Node.js application.

## Pre-Requisites

Before attempting to set up the project for the first time, ensure that you have successfully installed the following utilities. If not, install them in the following order:

- [ ] [NodeJS](https://nodejs.org/en/) - **[Install NodeJS here](https://nodejs.org/en/)** for all operating systems.

## First Time Setup

### 1) Run the `setup` command

**In a terminal with this project as the current working directory, run the following command:**

```bash
npm run setup
```

### 2) Set the `Prettier` config file location

**In the VScode explorer window, right-click the `.prettierrc.json` file and select `Copy Path`.**

![Copy prettier config path](./docs/setup-1.png)

**Then, press `Ctrl/⌘` + `,` to open VScode settings. Search for `prettier config` then paste in the value for _Prettier Config Path_.**

![Update prettier config path](./docs/setup-2.png)

### 3) Enable the _Format on Save_ setting for Prettier

![Enable format on save](./docs/setup-3.png)

**Still in VScode settings, search for `format on save` in the search bar and enable that setting.**

## Running the application

Run `npm start` to launch a [nodemon](https://github.com/remy/nodemon) session which will run your app and watch for changes with hot reloading. The entrypoint for nodemon is `src/index.js`.

## Committing via Git

This project template uses [Husky](https://github.com/typicode/husky) to run a pre-commit hook which uses the [lint-staged](https://github.com/okonet/lint-staged) package to lint and format only the staged files as defined in `.lintstagedrc.json`. This helps prevent bad code from polluting the repository.

As your project grows, please edit the Husky & lint-staged configurations to include automated testing or any other additional pre/post commit logic you might come to need.
