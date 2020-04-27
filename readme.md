# FullStack Angular and SpringBoot Project

Full Stack angular project using spring boot for backend.

Springboot is run on localhost:8080

```
In order to run the entire project, start with the `01-start-files` and run your database scripts.
Next, run the Springboot server to connect to the database. (More information located in the readme.md located in 02..directory)
Finally, Run the Angular project with `ng serve` .. This will run the application on localhost:4200
There is cross origin support where Springboot is ran on localhost:8080. Angular will read the api data from the springboot server
and convert it into usable data for displaying on front end.
```

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).



# --NOTES--
```
v1. 	4/14/2020
		- Added html table for displaying the data.
v2.1 	4/15/2020
		- Installed local bootstrap and css files to Angular project.
		- Integrated new CSS template style for shop display.
		- Added images to directory in project.
		- Added new SQL DB SCRIPT for adding 100 new products. (Removes the old DB).
v2.2  	4/21/2020
		-Integrated searching for products by category via menu-component(utilizing Angular Routing)
		-Only shop is updated via Angular Routing, not entire page.
		-Modified Spring Boot app to expose entity ids. (Allows for Angular to call on each product cateogry and display them)
		-Removed hard-coded menu links to use menu-component. (Uses productCategory service to read in the categories from Spring REST API)

v2.3	 4/21/2020
		-Added new Angular routing for search.
		-Updated Spring API to return products on a name search.
		-Added new component for searching by name.
v2.4     4/22/220
		-Added master detail view. (Allows for displaying of detail of each product a user clicks on)

v2.5     4/25/2020
		-Added pagination support using Spring Rest JSON and angular pagination (ng-bootstrap)
		-Added drop down list for allowing number of products per page for viewing to be user selected.
		-Added pagination for search results
	
v2.6     4/26/2020
		-Integerated shopping cart (Allows for putting items in the shopping cart)
		-Added add to cart function when clicking on the add to cart button
		-Created cart details page -- allowing for add or removing items.
		-Added checkout button and checkout form.
		-Updated add to cart feature on the master detail view.

v3(FINAL)      4/27/2020
		-Added cart details page and empty cart details page.
		-Added increment and decrement buttons for cart details page.
		-Added remove item.
```
## OLD FILES
	- 02-create-products   (located in --> 01-starterfiles DIRECTORY)
	
	