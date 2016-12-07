# angular-cli 1.0.0.beta-22

## boostarp v4-a5
https://github.com/angular/angular-cli#global-library-installation

http://tether.io/  
https://cdnjs.com/libraries/tether  
https://github.com/HubSpot/tether  


## github & chrome error

error? can not edit the file on Chrome!
what's wrong with this?

You can't perform that action at this time.

********************************************************************************************************

# update CLI 1.0.0.beta22

```sh
# https://github.com/angular/angular-cli/issues/3376#issue
# run http://localhost:4200/ & open defualt browser
$ ng server --open
``` 


```sh
# update CLI 1.0.0.beta22

$ npm i -g angular-cli@v1.0.0-beta.22

$ ng new app
# very slowly , just waiting for it install all packages!

$ cd app
# open app folder path

## test version (./src)
$ ng server

# why not show the localhost://4200 in the terminal? 
# browser-sync for (./dist)
$ browser-sync start --server

# https://github.com/angular/angular-cli/issues/3376#issue
# run http://localhost:4200/ & open defualt browser
$ ng server --open

## publish development version (./dist)
$ ng build

## publish production version (./dist)  
## (./angular-cli.json & ./src/environments/environment.prod.ts)
$ ng build --env=prod
``` 



