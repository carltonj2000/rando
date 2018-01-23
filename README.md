# Express, React, Docker Application

The code in this repository is based on the
[Create React App with Express in Production](https://daveceddia.com/create-react-app-express-production/)
article.
Heroku is not used for deployment but docker is as described in the
[Dockerizing a Node.js web app](https://nodejs.org/en/docs/guides/nodejs-docker-webapp/)
document and the docker file was optimized based on the
[Building Efficient Dockerfiles - Node.js](http://bitjudo.com/blog/2014/03/13/building-efficient-dockerfiles-node-dot-js/)
article.

The docker build steps are in the package.json file
which sets `"private": true` in order to stops a number of npm warnings which includes the `No repository field` warning.
