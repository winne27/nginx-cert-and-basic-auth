#Nginx client cert auth with fallback basic auth

This is an example of an nginx configuration with:

* forward http to https
* protect access to a subdirectory
* authenticate by client certificate
* fallback to basic auth (user and password) when certificate is not available

For creating client cert see [mini tutorial from mtigas](https://gist.github.com/mtigas/952344)
