# JWT sample client #

This is a barebones index.html page for testing a JSON Web Token in association with the **nodejs-jwt-authentication-sample** server.

Clone or fork the nodejs-jwt-authentication-sample server from [here](https://github.com/auth0-blog/nodejs-jwt-authentication-sample), then launch it. Open the `index.html` page in your browser.

Click on the buttons to obtain a JSON Web Token and then retrieve random Chuck Norris jokes through a route that is requires JWT authorization.

Reload the page and request a random quote *before* obtaining the JWT, to see how the request is blocked.