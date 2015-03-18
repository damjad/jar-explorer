
##Introduction

This is a  desktop Swing application that ability to recursively scan a directory and index a large number of jar files
all at once. It then allows to explore individual jar files or search all jar files at the same time.
It provides a number of views for resources: class - specific, shows all class information:
interfaces, super class, methods, fields, as well as views for text, HTML, images.

## Installation

You need to have Java 1.4 or higher.
Download the file: [jarexplorer-0.7-BETA.jar](http://jar-explorer.googlecode.com/files/jarexplorer-0.7-BETA.jar)
and execute the following command:

    java -jar jarexplorer-0.7-BETA.jar

## Configuration

Almost nothing to configure. There is one property file:

.JarExplorer.properties
This file contains a property:
zip.extensions=jar,zip,war,ear,rar

You can add other file extensions here, as long as the files themselves are in zip format.

## Screen Shot

![jar-explorer.jpg](jar-explorer.jpg)
