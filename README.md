# how-to-build-a-firebase-api

This repo accompanies my blog post on __Angular-In-Depth__ [Buliding an API with Firebase](https://blog.angularindepth.com/building-an-api-with-firebase-6108a207c1fd) 

The `functions` folder holds the backend API endpoints.

The `frontend` folder holds a basic Angular frontend application that consumes the API endpoints.

The `postman` folder holds a postman collection that has example calls that you can run.  Within the collection the `localhost` are calls when running the functions locally, and `deployed` are calls when running the functions deployed.

There is a set of npm scripts that help with running this project:
- `start-frontend` runs the Angular frontend application locally on `localhost:4200`
- `api-serve` runs the API locally on `port 5000`
- `api-deploy` deploys the API into Firebase
- `firebase-install` installs the Firebase CLI
- `firebase-init` initializes a firebase project
