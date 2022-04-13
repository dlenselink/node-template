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

### 1)

-

* [ ] **Copy the file path of the `.prettierrc.json` file**

![Copy prettier config path](./docs/setup-1.png)

### 2)

- [ ] **Press `Ctrl/⌘` + `,` to open vscode settings, then paste in the value for the _Prettier Config Path_ value.**

![Update prettier config path](./docs/setup-2.png)

### 3)

- [ ] **Enable the _Format on Save_ setting for Prettier.**

![Enable format on save](./docs/setup-3.png)

### 4)

- [ ] **Update dev dependencies**

Open a terminal with this project as the working directory. Then, run the following command and follow the instructions in any ensuing prompts:

```bash
npx npm-check-updates
```

### 5)

- [ ] **Install all dependencies**

In that same terminal (or any terminal with this project as the current working directory), run the following command:

```bash
npm i
```

This will download and install the node_modules dependencies for the few static dev dependencies this template uses. You are now ready to modify the code and run the app! To run the app, just run:

```bash
npm start
```
