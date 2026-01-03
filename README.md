# Oauth2 Simple Demo

Uses authorization code grant flow to request a token from Auth0 using a client ID and 
secret on the server-side. Must specify issuer URI, credentials, and scopes in 
application.properties.

Application must also be setup on Auth0 as a Regular Web Application prior to authenticating.

In this scenario, this webapp is the client application and Auth0 is the authorization server and the resource server.