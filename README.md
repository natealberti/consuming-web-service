# consuming-web-service
Uses SOAP to retrieve data from a WSDL based web service


The purpose of this project was to get started learning about how to use SOAP, but I ran into a few problems. The goal was to to be able to query data about a country based on its name from an outside WSDL based web service. I had a problem with the POM file where it didn't recognize certain tags. Also after running mvn compile, JAXB did not generate the Java classes from WSDL like it was supposed to. As a result the java files had a lot of unresolved problems. The problem probably lies with some outdated info from the Spring Guide I worked from.
