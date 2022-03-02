# Tenzies App!

Bootstraped with a [Create React App](https://github.com/facebook/create-react-app) site that can be deployed to Vercel with zero configuration.
Developed with [Stackblitz](https://stackblitz.com/), since my current PC doesn't support the most recent Node and NPM versions. You can access and fork the project [here](https://stackblitz.com/edit/react-fkh96h).

## [Play it!](https://tenzies-app-chi.vercel.app/)

The game is simple: Roll until all dice are the same. Click each die to freeze it at its current value between rolls.

## About the project

App developed as part of [Bob Ziroll's React course on Scrimba](https://scrimba.com/learn/learnreact), totally recomended btw.
After doing it while following the tutorials and challenges, I decided to redo it all by myself to test my knowledge, and I'd like to believe it turned out pretty well (it took me only a few hours and a couple visits to StackOverflow, so I'm proud).

## Concepts applied

* [useState](https://es.reactjs.org/docs/hooks-state.html)
* [useEffect](https://es.reactjs.org/docs/hooks-effect.html)
* [Array.prototype.map()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)
* Some good ol' HTML and CSS.

### Dependencies used

* [nanoid](https://www.npmjs.com/package/nanoid) for key generation.
* [react-confetti](https://www.npmjs.com/package/react-confetti) for, well, confetti when you win.

## To do

- [ ] Add roll counter.
- [ ] Save highest score (or lowest roll count) to localstorage.
- [ ] Style dice like real dice using CSS.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes. You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode. See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.

It correctly bundles React in production mode and optimizes the build for the best performance. The build is minified and the filenames include the hashes.
