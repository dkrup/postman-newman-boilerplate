Postman+Newman Boilerplate for running Postman API test collections from command line
==========================================

***

Project to run Postman API test collections from the command line using Newman CLI

## Quick start

1. Clone the repository

2. Install [Newman](https://learning.postman.com/docs/collections/using-newman-cli/installing-running-newman/#installing-newman): `npm install -g newman` on your machine.

# How to run tests

Execute the command - `npm test` or `newman run postmanCollections/myCollection.json -r htmlextra` to run tests and to generate the 'htmlextra' report;

Execute the command - `newman run postmanCollections/myCollection.json` to run tests and to see the console report;

Report will be generated automatically
