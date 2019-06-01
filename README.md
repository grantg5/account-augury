## Account Augury

### Background
Like many others, I like knowing if I have enough money to pay for food, rent, gas, insurance, and other boring adult stuff, as well as stupid stuff like glow-in-the-dark golf balls, while still ensuring I have enough in the bank to handle "large expenses". I've used budgeting tools like Mint for years to track my savings growth (or shrinkage), and they've worked well day-to-day, but I don't like how many of them handle large, expected purchases or income events, like:

* Renewing my car insurance for another 6 months
* Receiving my year-end bonus (thanks boss)

The tools will either try to average these into my monthly budget, meaning my expected inflow/outflow never matches my actual inflow/outflow, or inform me that I really blew my budget that month, even though I couldn't not pay for car insurance without selling my car or living on the lam for the most boring reason possible.

So I'm building the Account Augury, to place those larger monitary events alongside my month-to-month paycheck/spending difference, to help me visualize where my savings will be 6 months/1 year/5 years/etc. from now.

### Rough Iteration Plan
* Version 1: One page app where you can enter income, budget, future income events, & future spending events, click Submit, and view a beautiful, interactable, scalable graph of your expected savings growth/shrink
* Version 2: Backend/User Authentication/Saving the numbers & events you entered
* Version 3: Factoring predicted inflation & possible salary growth into long-term projections
* Version 4 (if possible): Pulling past account data from your bank to compare projections with actual account inflow/outflow

https://trello.com/b/eGJ73t1l/account-augury

________________________________________________________________________________________________________
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

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

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
