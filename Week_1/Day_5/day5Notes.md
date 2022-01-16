# Day 5

- \*\*Fridays notes will include the weekends

- still uncomfortable being uncomfortable but getting there

-key will be in the test button

- to start npm run start-exam -token-

- to submit test questions -npm run question 00 - or whatever the number

# The Keyword .this

refers to the object its being called in
except for arrow functions because they dont create their own scope
then it will refer to the global object(if running in dev tools that will be the window object)

# Recursion

## the base case

basically the stop condition. so the point we the recursion doesnt need to happen anymore
ie if n === 1 stop same as in a loop i >= 1

## the recursive case

when the base case of n in this case 1 has not been met and we want to keep 'recurring'
ie n > 1 continue

- ok so recursion is sweet

# Modules

node has access to a module object which allows us to access other files and import/export code
to check this we can console.log(module) and we will see the object and its properties

this lets us organize our code into different files

## to import a file

at the top of your file add this

- const whatYouWantToCallIt = require('./pathToFile')
  note we dont have to include the .js at the end of our file

## to export a file

at the end of your file add this

- module.exports = functionName

# json

package.json docs

https://docs.npmjs.com/cli/v8/configuring-npm/package-json

## Testing

good read

https://codeutopia.net/blog/2015/04/11/what-are-unit-testing-integration-testing-and-functional-testing/
