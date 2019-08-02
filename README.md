# node
This program is intended to add 1+2 which =3 using lodash and 
then print the results in in blue with a red background.
sample code :
var _=require('lodash');
const chalk = require('chalk');


var arr = [1,2]; 
var sum = _.sum(arr);

var obj = {'a':1, 'b':2 };
varobjSum = _.sum(obj);

const log = console.log;
log(chalk.blue.bgRed.bold(varobjSum));


