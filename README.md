# Onit Landing

A landing page for the Onit app based on the Ellie template by Cruip. This briefly gives some information about the app and a way to log in.


## Local Setup

The project can be cloned and set up locally by the following CLI commands from the **onit-landing directory**.

### `npm install`

Install all of the Node dependencies for React and other third party packages used in this project.

### `npm run build`

Execute various linting, minifying and bundling sub-scripts on the CSS, JS and images to prepare the app for production.

### `npm run start` (Local only)

This starts the project by spinning up a new development server using BrowserSync, opens a new browser window / tab and then watches for SCSS or JS changes in the `src` directory. BrowserSync will automatically recompile when a change is made and reflect the change in the browser.

### `npm run start-hosted` (Hosted only)

This is used to spin up an Express server in a remote (headless) environment. The app has been set up for Heroku specifically, and as such has a Procfile that instructs the automatic execution of this script.
