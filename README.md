# maven-apache-felix-tutorial
Mavenized version of the apache-felix-tutorial at http://felix.apache.org/documentation/tutorials-examples-and-presentations/apache-felix-osgi-tutorial.html

Just run
 mvn clean deploy

and find compiled the bundles in 
 local-maven-repo/org/vaadin/example/osgi

Then run Felix and on the command line play with

start <bundlename>
  to start a bundle
lb
  to list the bundles and their numeric IDs
stop <bundle ID>
  to stop a bundle

help
  to learn more about Felix' commands

