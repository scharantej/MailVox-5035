## Flask Application Design

### HTML Files

- **index.html**:
  - This will be the main page of the application.
  - It will include a form to accept user input and submit it to a specific route.
- **results.html**:
  - This page will display the results generated by the application.
  - It will be rendered when the user submits the form on the index page.

### Routes

- **main_route**:
  - This will be the route that corresponds to the index.html file.
  - It will display the main page with the form.
- **results_route**:
  - This will be the route that corresponds to the results.html file.
  - It will take the user input from the form on the index page, process it, and generate the results. These results will be displayed on the results.html page.