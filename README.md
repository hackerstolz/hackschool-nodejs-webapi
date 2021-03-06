# Node.js Web APIs

This repository contains a Web API sample built with Node.js. A Angular 2 client is used to communicate with the APIs. A lot of things in this repo are covered by a [blog series](https://manuel-rauber.com/tag/series-node-js-and-asp-net-core-1-0-usage-comparison/).

This project has been forked from [Thinktecture Node.js & ASP.NET Core 1.0 Web API](https://github.com/thinktecture/nodejs-aspnetcore-webapi) and was adopted for usage in the Hackerstolz Hackschool.

## Web APIs

* `HTTP GET api/customer/list`: Returns a list of all customers
* `HTTP POST api/customer`: Creates a new customer
* `HTTP DELETE api/customer/{id}`: Removes a customer

## Setup

* Install [Node.js](https://nodejs.org/en/) > v5 .
* Execute `npm install` within the root of this repository to install all necessary dependencies. You will encounter some `npm err` or `npm warn`. That's okay, since this repository uses a lot beta versions. It will not break the application.

## Starting

* To start the Web APIs execute `node index.js` in `src/nodejs`. It will then be accessible via `http://localhost:5000`.

### Angular 2 Client

To start the Angular 2 Client, run `npm run watch` within the root of the repository. You can access the client via `http://localhost:8000`. The credentials are

* Username: `bob`
* Password: `bob`

Since both backends lack a support for user management, those credentials are the only one which are working. :-)

## Third-Party Libraries

This section contains notable third-party libraries.

### Node.js

* [restify](http://restify.com/) Used for Web API hosting.
* [restify-cors-middleware](https://github.com/TabDigital/restify-cors-middleware) An actually working middleware for handling cors in restify.
* [express](http://expressjs.com/) Used for STS hosting.
* [SequelizeJS](http://sequelizejs.com) Used to provide an ORM accessing the PostgreSQL database. 

### Angular 2 Client

* [Angular 2](https://angular.io) itself. ;-)
* [Gulp](http://gulpjs.com) for building and watching

## Additional resources

* [Node.js at Paypal](https://www.paypal-engineering.com/?s=node)
* [Node.js at Netflix](http://techblog.netflix.com/search/label/node.js)
* [Node.js at Walmart](https://www.joyent.com/developers/videos/node-js-at-walmart-introduction)
