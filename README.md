# Novatore MEAN Boilerplate

This is a MEAN (MongoDB, Express, Angular, Node) boilerplate, used and maintained by Novatore Solutions. The server side code structure has largely been taken from [yoeman angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) generated code.

## Requirements To Run

1. Node and npm
2. Mongodb

## Installation

1. Clone the repository and move to it
2. Install npm modules: `npm install`
3. Install bower dependencies `bower install`
4. Start mongodb with `mongod` (default port 27107, to change that modify the config file)
5. Start up the server: `node server`
6. In another terminal/console start gulp `gulp`
7. Head to browser at http://localhost:9000

## Additional Notes

1. Although the respository and the build process is structured keeping in mind full stack applications using Angular 1, it's just the bare bones. The real code is structured and build on top of it according to the nature of the application
2. The repository is also used for server heavy web services and schedulers (cronjobs) with or without Angular application
3. The ES6 part of the yeoman borrowed boilerplate code has been changed to ES5 to get rid of babel and keep it simple for smaller Node versions. As ES6 is compatible with Node version >= 7 and does not require babel, it's preferred and recommended
4. Mocha, sinon and chai are usually used for Unit tests on server side for which `spec.js` files are included in most of the places 

