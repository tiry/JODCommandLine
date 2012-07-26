
Simple command line utility that embeds :

 - nuxeo-platform-convert (espcially the OOoManager)
 - JODConverter

The goal is to be able to easily test OpenOffice/LibreOffice integration in different environements.

The command line allows simple operations :
 - start OpenOffice manager
 - stop OpenOffice manager
 - get status and configuration of the manager and associated process
 - change configuration
 - run a simple doc2pdf conversion


Building :

    mvn clean install

Running :

    java -jar target/JODCommandLine-5.6-SNAPSHOT-with-deps.jar

