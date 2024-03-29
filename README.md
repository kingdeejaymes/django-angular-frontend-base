# App Angular FrontEnd Base Code
### Can integrate to Django REST and/or Other Backedn via REST Apis

Open in Visual Studio

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.2.1.

[Optional] Install bootstrap and bootswatch https://bootswatch.com/
> `npm install bootstrap --save`

then add to src/style.scss

> "@import "../node_modules/bootstrap/dist/css/bootstrap.min.css";"

then add to angular.json

> "scripts": [
>   "node_modules/bootstrap/dist/js/bootstrap.js"
> ]

### NPM Install
Run `npm install` 

[Optional] If you install bootstrap and you want the bootswatch, download the files from https://bootswatch.com/ for the template that you want:

> bootstrap.css
> bootstrap.min.css
> _variables.scss

and update the file in this directory:
Instruction here: https://bootswatch.com/help/

> node_modules/bootstrap/dist/css/bootstrap.css
> node_modules/bootstrap/dist/css/bootstrap.min.css
> node_modules/bootstrap/scss/_variables.scss

### Development server

Run `ng serve --port 8081` for a dev server. Navigate to `http://localhost:8081/`. The app will automatically reload if you change any of the source files.

### Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

### Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

### Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
