# Openshift Neo4j 2 Cartridge
This cartridge provides [Neo4j](http://www.neo4j.org/) on openshift Platform.

**Neo4j** is an open-source graph database supported by Neo Technology. It stores data in nodes connected by directed, typed relationships with properties on both, also known as a Property Graph. This database uses the most generic data structure, capable of elegantly representing any kind of data in a highly accessible way.

Main Neo4j features includes improved reliability with full ACID transactions, high scalability and availability, fast data processing, etc.

Neo4j 2 version provides the following enhancements:
* Java 7 support (instead of Java 6)
* marking nodes as members of a named group
* integrated browser as a fluid developer workbench
* cypher advancement (new clauses and functions, improved syntax)


### How to add a cartridge to Openshift ?

Under openshift console, select the application and click on  the "see the list of cartridges you can add" link at the bottom of the page.
Scroll down to the "Install your own cartridge" and type the following url:



https://raw.githubusercontent.com/danielnatali/openshift-neo4j-cartridge/master/metadata/manifest.yml

After a while, you should get your gear with Neo4j!



