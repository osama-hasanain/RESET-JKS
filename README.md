# RESET-JKS
reset upload keystore file after loss and update on google play

1- cd C:\Program Files\Java\jre-1.8\bin


2- paste new jks & .pem


3- keytool -export -rfc -keystore [JKS_NAME.jks] -alias [JKS_KEY_ALIAS] -file [PEM_NAME.pem]


ex: keytool -export -rfc -keystore key0.jks -alias key0 -file upload.pem 

4- link Google Support Form :
	https://support.google.com/googleplay/android-developer/contact/key
