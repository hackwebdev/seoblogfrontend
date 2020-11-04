```
https://nextjs.org/

go to docs

$ npm install next react react-dom

"scripts": {
  "dev": "next dev",
  "build": "next build",
  "start": "next start"
}

creat a folder pages and inside create an index.js file

create components folder

Note: with Next no need to import React

use Bootstrap - https://www.bootstrapcdn.com/
https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js

nextjs docs Advanced Features > Dynamic Import > Custom `Document`
copy the example

pages > _document.js

need to fix meta tag on _document.js coz it has a warning error

for Responsive navigation
https://reactstrap.github.io/ - to implement bootstrap
$ npm install --save reactstrap react react-dom

Components > Navbar Copy the code

Adding Environment variables
create next.config.js from the root folder
create config.js from the root folder
<- need to restart the server ->

create a next.config.js

module.exports = {
    publicRuntimeConfig:{
        APP_NAME:'app name here',
        API_DEVELOPMENT:'link here',
        PRODUCTION: false or true
    }
}

note: componets > Header.js no need to use <a> only use <NavLink> because we are using reactstrap

$ npm i isomorphic-fetch
All the auth related methods
create folder actions > auth.js
```
