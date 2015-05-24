# primitive-hamcrest
Basic hamcrest matchers with Java Primitives in mind.

## Installation Instructions

* Install the mvn package to your local repository.  
```
    git clone https://github.com/inf295uci-2015/primitive-hamcrest.git  
    cd primitive-hamcrest  
    mvn test # just to make sure that everything works  
    mvn install # installs this to your local repository  
```
* Include the following dependency in your pom.xml
```
    <dependency>
      <groupId>org.spideruci.hamcrest</groupId>
      <artifactId>primitive-hamcrest</artifactId>
      <version>0.0.1-SNAPSHOT</version>
    </dependency>
```

## Features

Currently the library supports veryifying if a primitive array contains all of the given primitive elements for the following primitive types:

    - [x] int array
    - [x] float array
    - [ ] byte array
    - [ ] boolean array
    - [ ] short array
    - [ ] double array
    - [ ] long array
