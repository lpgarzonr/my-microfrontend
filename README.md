# MyMicrofrontend

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.3.10.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## Deploy to GH pages

Follow the steps in [Deploy to GitHub Pages](https://v17.angular.io/guide/deployment#deploy-to-github-pages)
and [Publish source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#choosing-a-publishing-source)

```shell
g add .
g commit -m "chore: Change"
g push
gco gh-pages
g merge main
ng build --output-path docs --base-href /my-microfrontend/
mv docs/browser/* docs/
rm -r docs/browser/
g add .
g commit -m "new deploy"
g push
gco main
```

```
g add . && g commit -m "chore: Change" && g push && gco gh-pages && g merge main && ng build --output-path docs --base-href /my-microfrontend/ && mv docs/browser/* docs/ && rm -r docs/browser/ && g add . && g commit -m "new deploy" && g push && gco main

```
Check the gh pages wf run
https://github.com/lpgarzonr/my-microfrontend/actions

check the changes on
 
https://lpgarzonr.github.io/my-microfrontend/
https://lpgarzonr.github.io/my-microfrontend/assets/content-configuration.json
