### Udagram Application
 This is Full-Stack project built for a retailer and deploy it to a cloud service provider so that it is available to customers.

The project will also include writing documentation covering the operations of the deployment process. Which will serve as a way to 
communicate with future developers and anybody involved in diagnosing outages of the Full-Stack application.

![info](./Docs/screenshots/infrastructure-diagram.png)
![pipeline](./Docs/screenshots/pipeline.png)

## Website Link

* Use this link:  [Link](http://finalversion.s3-website-us-west-2.amazonaws.com/)


## Hosting

* This website is being hosted on AWS.
* Elastic Beanstalk is used for the Backend API.
* S3 bucket for the frontend and uploaded images.
* RDS database running Postgres.



## CI/CD pipeline
* The CircleCi is linked to the project on Github.
* It is used to automatically deploy the website to the AWS.
* It is set to automatically execute once the code is being pushed into the master Github project.



## Installation

Provision the necessary AWS services needed for running the application:

1. In AWS, provision a publicly available RDS database running Postgres. <Place holder for link to classroom article>
1. In AWS, provision a s3 bucket for hosting the uploaded files. <Place holder for tlink to classroom article>
1. Export the ENV variables needed or use a package like [dotnev](https://www.npmjs.com/package/dotenv)/.
1. From the root of the repo, navigate udagram-api folder `cd starter/udagram-api` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run dev`.
1. Without closing the terminal in step 1, navigate to the udagram-frontend `cd starter/udagram-frontend` to intall the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

## Unit Tests:

Unit tests are using the Jasmine Framework.

## End to End Tests:

The e2e tests are using Protractor and Jasmine.

## build status

[![CircleCI](https://circleci.com/gh/Elbassel511/hosting-full-stack-app-udacity/tree/master.svg?style=svg&circle-token=2024127671f542f7d2659199e559ee069519abc6)](https://circleci.com/gh/Elbassel511/hosting-full-stack-app-udacity/tree/master)


## App dependencies

- [Node js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [npm](https://www.npmjs.com/)
- [Angular](https://angular.io/)
- [node-postgres](https://www.npmjs.com/package/pg)
- [sequelize](https://sequelize.org/)
- [Aws cli](https://aws.amazon.com/cli/)
- [postgres database](https://www.postgresql.org/)
- [eb cli](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3.html)
- [RDS postgres database](https://aws.amazon.com/rds/)
- [ionic](https://ionicframework.com/)


## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

