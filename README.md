Archetype Simple Webapp

Summary

This is a simple web application which has a servlet and a jsp, which displays a message from the same servlet. This project has been tested in Tomcat 8.

Installation

 git clone https://github.com/jairdaniel/archetype-simple-webapp-1.git
 cd archetype-simple-webapp-1
 mvn clean install

Create a project

 mvn archetype:generate \
        -DarchetypeGroupId=my.jair.tests \
        -DarchetypeArtifactId=webapp-archetype \
        -DarchetypeVersion=1.0.0-SNAPSHOT \
        -DgroupId=my.groupid \
        -DartifactId=my-artifactId \
        -Dversion=version
