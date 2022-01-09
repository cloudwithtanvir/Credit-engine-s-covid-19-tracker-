## About Project

Deployed on AWS: https://develop.dl2wzm3fqmzqb.amplifyapp.com/

This project has developed as a part of recruiting steps of the company of [credit engine]https://creditengine.jp/). This project will help to show the real-time update [covid-19](https://covid19.who.int/) situation around the globe.


#### Features implemented:
  * Calling the Open Covid api's & showing data from open API
  * Search by country
  * Dockerize the project
  * add css for a source
  * add global css
  * Dockerize the project
  * Deployment to AWS
 #### Future work
In future, I may add the "omicron covid" tracker on this project as well build djnago based backend with more features



This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:
### npm/yarn install
### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

# Set up the environment
Get the latest project clone to your computer:
$ git clone 
### Run with Docker

Install Docker Engine from the tutorial https://docs.docker.com/engine/installation/.
Install Docker Compose from the tutorial https://docs.docker.com/compose/install/.

Run docker-compose commands to start containers:
$ sudo docker build -t credit-engine-s-covid-19-tracker .

### Run the Docker Container
Run and test the Docker Container
docker run — rm -it -p 8080:80 credit-engine-s-covid-19-tracker
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
