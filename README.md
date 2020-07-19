# https-example
sharing project on github for https-example

Project example to use htts url.

To generate self signed certificate use below command in cmd
:/> keytool -genkey -alias http-example -storetype JKS -keyalg RSA -keysize 4096 -validity 365 -keystyore https-example.jks

#SSL (Secure Socket Layer) configuration.
#TLS (Transport Layer Security) Advanced version of SSL.

#TrustStor: to store public certificate. google.com certificate or load balancing certificate
#Keystore: to store private certificate i.e. internal server certificate

Configured webhook to jenkins so that any commit happened to this repo, jenkins will start the build....

resolved issue by providing public domain with the help of ngrok proxy agent software
 Enter command >ngrok http 8080, it will generate http://{hexa-numbers}.ngrok.io copy the generated public address and put in your github repository webhook 
 http://{hexa-numbers}.ngrok.io/github-webhook/.
