# Setting up Variables on folder, global and environment level:

pm.variables.get(); 
pm.variables.set();

pm.globals.get(); 
pm.globals.set();

pm.environment.get(); 
pm.environment.set();

# Debugging script using console command:

console.log()
console.info() 
console.warn() 
console.error()

# How to run postman script from command line:

Run through command line using newman: https://www.npmjs.com/package/newman

Install:
$ npm install -g newman

Usage:
$ newman run examples/sample-collection.json

Checking help:
$ newman run -h


