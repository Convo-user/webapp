# Window Installer For Convo
**Convo** is a team collaboration tool, founded in 2011.

## Table of Contents
 2. [Installation](#installation)
 3. [Usage]()
 4. [Running unit tests]()
 5. [Configuring IDE]()
 6.  [Tools]()
 7. [Code style guide]()
 8. [Application Structure]()
 9. [Localisation]()
 10. [License]()
 

## Installation
You'll need [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com/)) installed on your computer.
````
#Clone this repository
$ git clone https://[username]@bitbucket.org/convolabs/webapp.git

#Go into the repository
$ cd path_to_your_repository

#Install dependencies
$ npm install
````

## Usage

````
#Go into the repository
$ cd path_to_your_repository

#Run tsc app command to compile .ts file into .js
$ tsc app

#Run npm run start command to run it on electron
$ npm run start

#Run npm run build command to build project and make and .exe file
$ npm run build


#this will open your project in electronjs default browserwindow
````

## Running unit tests

## Tools

## Configuring IDE
To make sure consistency in the code style standards we need to configure our IDE so that everyone can follow the same code style guideline.

````
#To configure IDE for typescript
#Use tslint.json file and configure your IDE to pick setting it.
#E.g. For webstorm;
Go to; 
	Webstorm -> Preferences -> Languages and frameworks -> typescript -> TSLint -> Enable
Note: Webstorm will automatically find path to tslint.json if not you can do that by browse option under Enable radio button. 
````

## Code style guide

- **Files**
	- **Do** use dashes to separate words in the descriptive name E.g. hero-list
	- **Do** use lower case for file names
	- **Consider** limiting files to 400 lines of code.
- **Functions**
	- **Do** define small functions
	- **Consider** limiting functions to no more than 15 lines.
	- **Consider** writing function names in camelCase E.g. thisIsMyFunction()
- **Classes**
	- **Do** use upper camel case when naming classes E.g. HeroClass
- **Variables and constants**
	- **Do** declare all local variables with either `const` or `let`. Use const by default, unless a variable needs to be reassigned. The `var` keyword must not be used.
	- **Do** writing type for each variable E.g. let employeeName: string;
	- **Do**  use lower camel case to name properties, methods, variables and constants.
	- **Avoid**  prefixing private properties and methods with an underscore.
- **Formatting**
	- **Indentation**
		- **Do** keep 2 spaces indentation
	- **Spacing**
		- **Consider** space before each '{' i.e. in functions, if statement, loops etc E.g. testFunc() {, if () {, for () {
		- **Consider** a line space between each logical block

## Application Structure

	- App
	- Main
	- src
		- js
		- notificaiton
		- installers
		- typing
		- index.html

## Localisation

## License
Convo 2.0 is licensed to Convo Inc.