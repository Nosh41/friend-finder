# Friend Finder - Bootcam TEC DE MONTERREY

### Compatibility based application

* The application will take in results from users' surveys then compare their results against all other users who have completed it. The application will then display the name and picture of the user with the best match overall.

## Technical details

* The application uses Express to handle routing 
* The server.js file uses the npm packages: express, body-parser, path.

* The html-routes.js file should include two routes:
	* A GET Route to `/survey` which displays the survey page.
	* A USE route that leads to `home.html` which displays the home page. 

* The `api-routes.js` file includes two routes:
	* A GET route with the url `/api/friends`. This will be used to display a JSON of all possible friends
	* A POST route `/api/friends`. This will be used to handle incoming survey results. This route will also be used to handle the compatibility logic.