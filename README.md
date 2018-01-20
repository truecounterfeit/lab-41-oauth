####  Documentation  
<!-- Write a description of the project in your README.md -->

* 8080
* run start

#### backend
* create an app on the google dev console
 * configure oauth credentials to suport a client app on `http://localhost:8080`
 * configure oauth credentials to suport a server redirect uri  to `http://localhost:3000/oauth/google/code`
* create a backend route `GET /oauth/google/code` for handling google oauth

#### frontend
* create an index.html with an anchor tag pointing to the google authoraztion page
* configure the query string will correct key value pairs
