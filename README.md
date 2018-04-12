
**Warning: we strongly recommend node >=v6.9.0 and npm >=3.0.0**

`npm i` - Installs everything needed

`npm start` - Starts the app. Then, go to `localhost:4200`

`npm run test` - Runs unit tests with karma and jasmine

`npm run e2e` - Runs end to end tests

`npm run e2e:home` - Runs end to end tests only for the home directory. There are more commands like this one, for development purposes

`npm run build` - Builds the app for production

`npm run lint` - Runs the linter (tslint)

`npm run ci` - Executes linter and tests

`npm run deploy` - Builds the app and deploy it to Github pages (angular-cli-ghpages) (fork to do this and remove CNAME file)

`npm run sme` - Builds and runs source map explorer, really cool :)

`npm run release` - Creates a new release using standard-version

`npm run docker` - Builds the docker image and run the container

**Windows: use precompilation to speed up**

`tsc --project tsconfig.json`
`npm start`

## Features
* Responsive layout (flex layout module)
* Internationalization
* Lazy loading modules
* Interceptors and Events (Progress bar active, if a request is pending)
* CRUD: create, update and remove heroes
* Custom example library
* Search bar, to look for heroes
* Custom loading page
* Modal and toasts (snakbar)!
* Unit tests with Jasmine and Karma including code coverage
* End-to-end tests with Protractor
* ES6 Promises
* Github pages deploy ready
* Google Tag Manager
* Modernizr (browser features detection)
* Following the [best practices](https://angular.io/guide/styleguide)!

## Docker

You can build the image and run the container with Docker. The configuration is in the nginx folder if you want to change it.

`docker build -t angularexampleapp .`

`docker run -d -p 4200:80 angularexampleapp`

## Do you want to create your own library with Angular?

This project is using an example library in angular, which you can check it [here](https://github.com/Ismaestro/angular-example-library).

This library contains a sample module, component, pipe, directive, all with tests, AOT compilation and an Angular-CLI playground too.

You can see how to use it, or develop a new one in the repository. Any doubts, please submit an issue or make a pull request.

## Travis CI
We use Travis CI to run this tasks in order:
* Linter
* Tests
* Build for production
* Deploy in Github pages
:)

## Contributing
- Please see the CONTRIBUTING file for guidelines.
- Create **pull requests, submit bugs, suggest new features** or documentation updates :wrench:

## Server

This repo is using an API which is [a minimal app](https://github.com/Ismaestro/nodejs-example-app) in NodeJS deployed on Heroku and using PostGreSQL, to create, modify and delete heroes.

## Contributors

Thanks to all contributors and their support!

## License

MIT

Enjoy :metal:

We are always happy to hear your feedback!
