# Getting started

## Prerequisites

Running Fabric server requires __java 11__ runtime or higher

## Installation

### Downloading a release

download a release package from the [release page](https://github.com/storydoc-io/fabric/releases) 

### Installing

To install the package unzip into a folder of your choice.

## Configuration

### application settings

to change the settings open config/application.yaml

        server port  (default: 8080)


### workspace

(meta)data is by default kept in the "workspace" directory

this directory can be changed in run.sh or run.bat

### jdbc drivers

by default no JDBC drivers are included

add a JDBC driver jar in the "lib" directory (subdir of the installation directory)  and restart


