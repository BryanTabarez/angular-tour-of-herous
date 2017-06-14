# AngularTourOfHeroes

Based on tutorial [https://angular.io/tutorial](https://angular.io/tutorial)

The tutorial was followed using the structure provided by [Angular CLI](https://github.com/angular/angular-cli) version 1.1.1.

---
## Some of the commands used

* create new app

    `ng new angular-tour-of-heroes`

* generate component

    `ng g component hero-detail`

* generate class

    `ng g class hero`

* create service with angular-cli

    `ng g service name-service`

---

## Deploy in github-pages using [angular-cli-ghpages](https://github.com/angular-buch/angular-cli-ghpages)

* install
    `npm i -g angular-cli-ghpages`

* create the dist folder (build the project) to deploy on the same repository 
    `ng build --prod` or shorter version `ngh`