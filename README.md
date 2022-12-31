# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## `Connect to AWS Amplify`
The AWS Amplify Console provides continuous deployment and hosting for modern web apps (single page apps and static site generators) with serverless backends. The Amplify Console offers globally available CDNs, custom domain setup, feature branch deployments, and password protection.

Login to the Amplify Console [here](https://aws.amazon.com/amplify/pricing/)

Connect your Create React App repo and pick a branch. If you're looking for a Create React App+Amplify starter, try the create-react-app-auth-amplify starter that demonstrates setting up auth in 10 minutes with Create React App.

The Amplify Console automatically detects the build settings. Choose Next.

Choose Save and deploy.

If the build succeeds, the app is deployed and hosted on a global CDN with an amplifyapp.com domain. You can now continuously deploy changes to your frontend or backend. Continuous deployment allows developers to deploy updates to their frontend and backend on every code commit to their Git repository.
