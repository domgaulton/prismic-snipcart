## Sample eCommerce Website with API-based CMS

This is a sample Node.js eCommerce website with content managed with prismic.io (API-based CMS).

### DG Instructions
https://user-guides.prismic.io/examples/nodejs-samples/sample-ecommerce-site-with-snipcart-in-nodejs

#### Getting started
Read [this guide](https://intercom.help/prismicio/examples/nodejs-samples/sample-ecommerce-site-with-snipcart-in-nodejs) for instructions to create your repository and use this sample eCommerce site.

#### Nodemon
https://nodemon.io/ - Nodemon is a utility that will monitor for any changes in your source and automatically restart your server. Perfect for development. Install it using npm.

#### Running
`npm start` or `nodemon` if installed

#### Deploy your Node.js website
An easy way to deploy your Node.js website is to use [Heroku](http://www.heroku.com). Just follow these few simple steps once you have successfully [signed up](https://id.heroku.com/signup/www-header) and [installed the Heroku toolbelt](https://toolbelt.heroku.com/):

Create a new Heroku application
```
$ heroku create
```
Initialize a new Git repository:
```
$ git init
$ heroku git:remote -a your-heroku-app-name
```
Commit your code to the Git repository and deploy it to Heroku:
```
$ git add .
$ git commit -am "make it better"
$ git push heroku master
```
Ensure you have at least one node running:
```
$ heroku ps:scale web=1
```
You can now browse your application online:
```
$ heroku open
```

### Git Repositories
`git push heroku master`
heroku  https://git.heroku.com/prismic-snipcart.git (fetch)
heroku  https://git.heroku.com/prismic-snipcart.git (push)

`git push origin master` or `git push origin 'branch-name'`
origin  https://github.com/domgaulton/prismic-snipcart.git (fetch)
origin  https://github.com/domgaulton/prismic-snipcart.git (push)


### TO DO
* Custom Types json object add to repo and API
* SASS and components

### Licence

This software is licensed under the Apache 2 license, quoted below.

Copyright 2017 Prismic.io (http://www.prismic.io).

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this project except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0.

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.