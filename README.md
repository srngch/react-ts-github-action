# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Set up github pages

Github actions are used to run the tests and build the project. The build is then deployed to github pages.

Change the following in the `package.json` file:

```json
{
  // ...
  "homepage": "https://<username>.github.io/<repo-name>"
  // ...
}
```

Set up github pages:

1. Go to the settings page of the repo
2. Select the "Pages" tab
3. Select the "gh-pages" branch and save

## Set up vscode to use typescript

Install the following extensions:
[ZipFS](https://marketplace.visualstudio.com/items?itemName=arcanis.vscode-zipfs)

Run the following command to install the typescript sdk:

```shell
$ yarn dlx @yarnpkg/sdks vscode
```

Select the typescript sdk in vscode:

1. Open the command palette (Cmd+Shift+P)
2. Select "TypeScript: Select TypeScript Version"
3. Select "Use Workspace Version"

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
