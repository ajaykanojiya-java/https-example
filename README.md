# https-example
sharing project on github for https-example

Project example to use htts url.

To generate self signed certificate use below command in cmd
:/> keytool -genkey -alias http-example -storetype JKS -keyalg RSA -keysize 4096 -validity 365 -keystyore https-example.jks

#SSL (Secure Socket Layer) configuration.
#TLS (Transport Layer Security) Advanced version of SSL.

#TrustStor: to store public certificate. google.com certificate or load balancing certificate
#Keystore: to store private certificate i.e. internal server certificate
