# Day 2 Notes

## ASync Notes
 * When adding tasks to the event loop - the event loop will not run until the main thread tasks have finished

### Tip:
Other examples of how asynchronous functions might be used include:
* Making a network API request
* Connecting to a chat server
* Anything that takes time and where we want users to know that the code is still running, like showing a basic loading animation

## Higher order functions:
* Higher order functions do not work by themselves.
* functions that return a function definition

## Terminal Notes
* process.stdout.write --> writes new characters on same line in terminal (prompt will be on same line use \n after)
* \r is rewrite and replaces words equal to new string length at beginning of string 'hello from spinner1.js... \rheyyy\n', becomes: heyyy from spinner1.js...

## Readline
### Function call:
const readline = require('readline');

const rl = readline.createInterface({
  input: process.stdin,
  output: process.stdout
});