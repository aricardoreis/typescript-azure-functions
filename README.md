# typescript-azure-functions

Base repository for typescript projects.

The main purpose of this repository is to be a basic template for node projects using typescript. The purpose is not to be a comprehensive project, it's just to be a good start for new projects. If you are interested in starting a new TypeScript project - check out the bootstrapping tools reference in [the TypeScript Website](https://www.typescriptlang.org/docs/home.html).

# Pre-requirements

To build and run this project locally you need to install some dependencies:

- Install [Node.js](https://nodejs.org/en/)
- Install [VS Code](https://code.visualstudio.com/)

# Getting started

- Install dependencies

```
npm install
```

- Build and run the project

```
npm run build
```

- Run the project locally using nodemon

```
npm run start:dev
```

- Fix formatting with prettier

```
npm run prettier:fix
```

# Working with Azure functions

- Create a new typescript function app
```
func init <func-app-name> --typescript
```

- Add a new HTTP-triggered function to the project
```
func new --name <func-name> --template "HTTP trigger" --authlevel "anonymous"
```
- Run the function locally
```
npm install
npm start
```
Now you will be able to access the function at localhost.