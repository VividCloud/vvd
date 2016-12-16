# Stack Design

## Components

* [hiddentao/robe](https://github.com/hiddentao/robe) as Data ODM
* [Apollo Data](https://github.com/apollostack) as Data Transmission Layer
* [Passport.js](https://github.com/passport) as default Accounts system (Should be wrapped for easier usage)
   * [apollo-passport](https://www.npmjs.com/package/apollo-passport) works as Apollo with Passport.js
* [Vue.js](https://vuejs.org) as View Layer, with server-side rendering works out of box
* [Express.js](http://expressjs.com/) as server-side router
* [Webpack 2 with Rollup](https://www.npmjs.com/package/rollup-loader) as bundle builder for both client and server
