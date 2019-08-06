# how-to-build-a-firebase-api

This repo accompanies my blog post on __Angular-In-Depth__ [Buliding an API with Firebase](https://blog.angularindepth.com/building-an-api-with-firebase-6108a207c1fd).

In order to create an app with Firebase please access the [Firebase Console](https://console.firebase.google.com/).

In order to learn about the Firebase Admin SDK please access [Firebase Documentation](https://firebase.google.com/docs/reference/admin).

The `functions` folder holds the backend API endpoints.

The `frontend` folder holds a basic Angular frontend application that consumes the API endpoints.

The `presentation` folder holds a copy of the presentation that I did for the Capital One Summit Course in August 2019.

The `postman` folder holds a postman collection that has example calls that you can run.  
- Folder `localhost` are calls when running the functions locally
- Folder `deployed` are calls when running the functions deployed.
- Collection uses the environment variable `project-id` for `localhost` vs `deployed` project values.  Please review the Postman documentation for more info on [how to set this up here](https://blog.getpostman.com/2014/02/20/using-variables-inside-postman-and-collection-runner/).

There is a set of npm scripts that help with running this project:
- `start-frontend` runs the Angular frontend application locally on `localhost:4200`
- `api-serve` runs the API locally on `port 5000`
- `api-deploy` deploys the API into Firebase
- `firebase-install` installs the Firebase CLI
- `firebase-init` initializes a firebase project
