# Setup
### Create *certs* directory:
```shell
mkdir certs
```
### Generating SSL certificate:
```shell
openssl req -newkey rsa:2048 -nodes -keyout certs/key.pem -x509 -days 3650 -out certs/cert.pem
```
# References:

- https://medium.com/scalac/user-authentication-with-keycloak-part-1-35295107acd
- https://www.youtube.com/watch?v=mdZauKsMDiI