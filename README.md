<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://sepod.codegenio.com/assets/images/logos/star-edition-logo.svg" width="200"></a></p>

## About SEPOD

SEPOD Angular is backoffice panel of Star Edition Admin, Employees and Clients build using Google's framework [Angular](https://github.com/angular/)

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.0.1.

[NPM](https://www.npmjs.com/) is being used as dependency manager. 


## Deployment steps
 - Server Requirements:

    The Anuglar framework has a few system requirements. You should ensure that your web server has the following items installed:
    - Apache 2.4
    - NodeJS > 12
    - NPM
    - Git Client
    - Composer
- Clone Repository with ```www-data``` user: ```git clone REPO_PATH``` Make sure to use SSH cloning with deployment keys being used
- Run ```npm install```
- Run ```npm install -g @angular/cli```
- Make build ```ng build``` 
- Point your domain to SEPOD_Angular/dist/SEPOD_Angular/index.html
- FLY :rocket:

## Repo Branches
During development you can elimintate the need for a server by using  
```ng serve```
it will default to the development config. and point to development-api.starfulfil.co.uk

## Repo Branches 
There are three branches setup. Use related commands to generate related builds:
- Development `ng build --configuration development`
- Staging `ng build --configuration staging`
- Main (Production) `ng build`

## About Angular
Angular is an application design framework and development platform for creating efficient and sophisticated single-page apps.
For more details visit docs [here](https://angular.io/docs)


