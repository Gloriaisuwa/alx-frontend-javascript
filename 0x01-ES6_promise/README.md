ES6 Promises

A Promise is a proxy for a value not necessarily known when the promise is created. It allows you to associate handlers with an asynchronous action's eventual success value or failure reason. This lets asynchronous methods return values like synchronous methods: instead of immediately returning the final value, the asynchronous method returns a promise to supply the value at some point in the future.

Learning Objectives
1. Promises (how, why, and what)
2. How to use the then, resolve, catch methods
3. How to use every method of the Promise object
4. Throw / Try
5. The await operator
6. How to use an async function

Resources
1. Introduction to Javascript Promise
2. The await keyword in Js
3. async in Js
4. Try /Throw in Js

Setup
Install NodeJS 12.11.x
(in your home directory):

curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
sudo bash nodesource_setup.sh
sudo apt install nodejs -y

$ nodejs -v
v12.11.1
$ npm -v
6.11.3

Install Jest, Babel, and ESLint
In your project directory, install Jest, Babel and ESList by using the supplied package.json and run npm install.

Configuration files
Add the files below to your project directory

1. package.json
2. babel.config.js
3. .eslintrc.js
4. utils.js

Tasks
0. Keep every promise you make and only make promises you can keep
1. Don't make a promise...if you know you can't keep it
2. Catch me if you can!
3. Handle multiple successful promises
4. Simple promise
5. Reject the promises
6. Handle multiple promises
7. Load balancer
8. Throw error / try catch
9. Throw an error
10. Await / Async
