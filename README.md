[Live Demo](https://pedantic-stonebraker-c10870.netlify.app/)

**Gameplay**: The game consists of a 5 by 5 grid of lights. When the game starts, a random number or a stored pattern of these lights is switched on. Pressing any of the lights will toggle it and the four adjacent lights. The goal of the puzzle is to switch all the lights off, preferably in as few button presses as possible.

![Lights Out Game](public/images/lights-out-demo.gif)

---

# Tips

- Number the rows 1-5, the columns A-E.
- For each light on row 1, press the button beneath it on row 2 to turn the light off. This way row 1 is completely unlit.
- Repeat step a for rows 2-4, so that now you only have lights on row 5. This is usually called 'chasing the lights'.
- If the light at A5 is on, press D1 and E1.
- If the light at B5 is on, press B1 and E1.
- If the light at C5 is on, press D1.
- Repeat steps a-b, chasing the lights down and it will be magically solved.
- This method will not solve the puzzle in the shortest possible way, but it is very simple.

---

## Roadmap

- [ ] include a reset/restart button for when player has won, or when player decides they want to try a new puzzle
- [ ] display moves counter
- [ ] show hints

## About the branch named `centered-and-not-responsive`

Contrary to the master branch, the above mentioned branch holds a version of the layout that is centered and not responsive.

### Pros and Cons of the centered layout

`Pros` : the cells are always squared
`Cons` : doesn't fit on mobile screens

## About this project

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
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

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `yarn build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
