# placesPlugin 

The Places plugin allows you to include a list and GPS map directory of categorized entries with pictures, contact information, instant directions, and even embed images and videos

###Plugin overview

http://support.appdocumentation.com/knowledge-base/places-plugin-tutorial

##How to run and test
###Prerequisite are node.js,bower,npm,karma, karma-coverage
```bash
$ npm install -g karma-cli
$ npm install -g karma-coverage
$ npm install -g bower
```
###Install bower and node dependencies
```bash
$ bower install
$ npm install
```
###Run the test cases
```bash
$ npm test
Or
$ karma start --reporters progress
```
###Run the test cases to see coverage
```bash
$ karma start
```

##How to validate js via eslint
###Prerequisite are node.js,bower,npm,karma, karma-coverage
```bash
$ npm install -g gulp
```

###Installnode dependencies
```bash
$ npm install
```
###Run the validate
```bash
$ gulp validate
```
