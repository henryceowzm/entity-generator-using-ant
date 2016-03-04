entity-generator-using-ant
========================

This tool provides a command line way of generating java entity class which is built upon hibernate tools. ([hibernate-tools](https://github.com/hibernate/hibernate-tools)).

# Getting Started

## Prerequisites

The project requires at least JDK 7, mysql, Ant, and Maven 3.0.

## Installation

Installation with Maven:
This will comple all dependencies to the lib folder.
```
git clone https://github.com/henryceowzm/entity-generator-using-ant.git
cd entity-generator-using-ant
mvn compile
```

## Build to generate java source code

```
ant 
```

## Prameters to tweak in build.xml
sourceGenerationBaseDir defaults to src/main/java

sourceGenerationPackage defaults to entity

Files will be generated under sourceGenerationBaseDir/sourceGenerationPackage with package being sourceGenerationPackage

## Format generated java source code

```
ant format
```

## Useful links
1. [hibernate tools documentation](http://docs.jboss.org/tools/latest/en/hibernatetools/html/ant.html#d0e4028)
1. [create config file for the formatter](http://www.peterfriese.de/formatting-your-code-using-the-eclipse-code-formatter/)

# License

'entity-generator-using-ant' is distributed under the terms of the [Apache Software Foundation license, version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html).
