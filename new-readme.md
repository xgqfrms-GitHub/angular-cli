update CLI 1.0.0.beta22

$ npm i -g angular-cli@v1.0.0-beta.22

$ ng new app
# very slowly , just waiting for it install all mpackages!

$ cd app
# open app folder path

## test version (./src)
$ ng server

# why not show the localhost://4200 in the terminal? 
# browser-sync for (./dist)
$ browser-sync start --server

## publish development version (./dist)
$ ng build

## publish production version (./dist)  
## (./angular-cli.json & ./src/environments/environment.prod.ts)
$ ng build --env=prod
