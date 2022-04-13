# General Purpose Node Template

This template provides a good starting point for any Node.js application.

## Pre-Requisites

Before attempting to set up the project for the first time, ensure that you have successfully installed the following utilities. If not, install them in the following order:

- [ ] [NodeJS](https://nodejs.org/en/) - **[Install NodeJS here](https://nodejs.org/en/)** for all operating systems.

- [ ] [npx](https://www.npmjs.com/package/npx) - Install **npx** with the following command:

```bash
npm install -g npx
```

## First Time Setup

### 1) Update dev dependencies

**Open a terminal with this project as the working directory. Then, run the following command and follow the instructions in any ensuing prompts:**

```bash
npx npm-check-updates
```

### 2) Install all dependencies

**In that same terminal (or any terminal with this project as the current working directory), run the following command:**

```bash
npm i
```

**This will download and install the node_modules dependencies for the few dev dependencies this template uses.**

### 3) Copy `Prettier` config

**In the vscode explorer window, right-click the `.prettierrc.json` file and copy its file path.**

![Copy prettier config path](./docs/setup-1.png)

### 4) Update `Prettier` config

**Press `Ctrl/⌘` + `,` to open vscode settings, then paste in the value for the _Prettier Config Path_ value.**

![Update prettier config path](./docs/setup-2.png)

### 5)

**Enable the _Format on Save_ setting for Prettier.**

![Enable format on save](./docs/setup-3.png)

**You are now ready to run the app! Use the `npm start` command to execute the contents of `src/index.js`.**
