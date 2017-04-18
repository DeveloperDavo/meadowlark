# meadowlark
Project app from Web Development with Node and Express by Ethan Brown

## Set Up
### Install node
https://nodejs.org/en/

### Install dependencies
`npm install`

### Copy third party libraries
```
cp node_modules/mocha/mocha.js public/vendor
cp node_modules/mocha/mocha.css public/vendor

cp node_modules/chai/chai.js public/vendor
```

### Setting up Grunt
```
sudo npm install -g grunt-cli
```

## Instructions
### Start Server
`node meadowlark.js`

### Run Tests
Start server and then:
```
mocha -u tdd -R spec qa/tests-crosspage.js
mocha -u tdd -R spec qa/tests-unit.js
```

### Start Grunt
Start server and then `grunt`




