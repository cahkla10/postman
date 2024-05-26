# postman
An example restful api automation testing using postman.

# pre-condition
- install postman
- install node.js
- install newman using npm
- install newman-reporter-htmlextra using npm
- clone or download this repository

# run through postman
- import DummyJson.postman_collection.json in postman
- import DummyJson.postman_environment.json in postman
- open Runner
- drag and drop collection
- click Start Run

# run through terminal or command prompt
- open terminal or command prompt
- go to directory where collection and environment already downloaded or cloned
- type ```newman run DummyJson.postman_collection.json -e DummyJson.postman_environment.json -r htmlextra```
- press enter keyboard button
- go to finder or file explorer where collection and environment already downloaded or cloned, there is will ```newman``` folder
- open ```newman``` folder
- open html report
