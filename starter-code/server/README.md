####  Documentation  
<!-- Write a description of the project in your README.md -->

* localhost 3000
* run start

# slugchat

## configuration
configure a .env file to include the following

``` bash
PORT=3000
NODE_ENV='dev'
SECRET='shark in the dark'
API_URL='http://localhost:3000'
CLIENT_URL='http://localhost:8080'
CORS_ORIGINS='http://localhost:8080'
MONGODB_URI='mongodb://localhost/slugchat-dev'
GOOGLE_CLIENT_SECRET= 665144491485-48b4b1h3lnvp2a96rt2bse0qqsn1nr6n.apps.googleusercontent.com
GOOGLE_CLIENT_ID= BI9B10gdqcr6vJVmSc0smopV
```
#### App
#backend
* create an app on the google dev console
 * configure oauth credentials to suport a client app on `http://localhost:8080`
 * configure oauth credentials to suport a server redirect uri  to `http://localhost:3000/oauth/google/code`
* create a backend route `GET /oauth/google/code` for handling google oauth

#frontend
* create an index.html with an anchor tag pointing to the google authoraztion page
* configure the query string will correct key value pairs
