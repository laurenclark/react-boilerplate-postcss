## Create React App + PostCSS

- `PostCSS` with `postcss-nesting`, `autoprefixer` and `npm-run-all` for boilerplating projects quickly.
- All the styles and App setup with the spinning react logo are removed for convenience. 

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

I've replaced the usual `yarn start` command with one which watches css changes too.

### `yarn start-js`

The regular `yarn start` that ships with create-react-app this just watches for JS.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn watch:css`

Watches and compiles PostCSS

### `yarn test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

I've changed `yarn build` to also compile PostCSS if you want the regular build command you can run `yarn build-js` which will just compile js, or `yarn build:css` to just compile css.

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

