# Plagiarism-checker

- [Introduction](#introduction)
- [Installation](#installation)

## Introduction

### Getting started: 
See the Guide on how to contribute [here](CONTRIBUTING.md) for instructions on how to fork and set up your repository. Refer [here](CODE_OF_CONDUCT.md) for code of conduct.

### About Plagiarism-checker
Plagiarism-checker is a utility that checks if the given code is plagiarised from other sources on GitHub. This is done using the GitHub API.

The idea is to divide the code into smaller segments and search for each of them using the GitHub API and give a score to each segment.
Finally using some algorithm, accumulate all scores of segment, and report how much plagiarised and the sources where the code can be found. 

### About DWoC

<a href="url"><img src="https://camo.githubusercontent.com/1ba815f1289125317c999a059ec95bfa5cba3894/68747470733a2f2f696d6775722e636f6d2f544c78357273762e706e67" height="180" width="550"> </a>

DWoC is a winter long program organised by [Delta Force](https://delta.nitt.edu/), the coding club of NIT Trichy. With an aim to support and improve the culture of open source software around us, this serves as a platform for young student developers (or even starters) to hone their technical skills by working on projects of their interests. We hope this encourages collabrative experiences and allows students from all backgrounds to contribute to quality technical projects from diverse fields. 
For more information, visit [DWoC](https://dwoc.io/)

## Installation

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### Available Scripts

In the project directory, you can run:
- `yarn start`: Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser. The page will reload if you make edits. You will also see any lint errors in the console.
- `yarn test`: Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.
- `yarn build`: Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance. The build is minified and the filenames include the hashes. Your app is ready to be deployed! <br />
See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.
- `yarn eject`: **Note: this is a one-way operation. Once you `eject`, you can’t go back!**
If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project. <br />
Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.<br >
You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

### Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

- Code Splitting: This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

- Analyzing the Bundle Size: This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

- Making a Progressive Web App: This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

- Advanced Configuration: This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

- Deployment: This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

- `yarn build` fails to minify: This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
