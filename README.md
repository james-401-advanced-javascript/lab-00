# LAB - 00

## Proof of Life Server

### Author: James Dunn

### Links and Resources
* [submission PR](https://github.com/james-401-advanced-javascript/lab-00/pull/1)
* [travis](https://travis-ci.com/james-401-advanced-javascript/lab-00)
* [front-end](https://jamesdunn-lab00.herokuapp.com/)

#### Documentation
* [jsdoc](https://jamesdunn-lab00.herokuapp.com/docs/)

### Modules
#### `pos.js`
##### Exported Values and Methods

###### `isAlive(dead) -> boolean`
Returns true/false to indicate how the server works

### Setup
#### `.env` requirements
* `PORT` - Port Number

#### Running the app
* `npm start`
* Endpoint: `/`
  * Returns a Boolean.
* Endpoint: `/docs`
  * Returns JSDoc Documentation Pages.
  
#### Tests
* Unit Tests: `npm test`
* Lint Tests: `npm run lint`

#### UML
![UML Diagram](lab-00-uml.png)
