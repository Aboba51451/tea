# tea
Wrap hapi.js server methods with a Promise. Requires Node.js 5+.   Installation npm install smthen --save  Usage import smThen from 'smthen';  smThen(server.methods.myServerMethod, 'arg1', 'arg2' [, any number of arguments]) .then(result => {     //do something with result }) .catch(err => {     console.log(err.toString()); })
