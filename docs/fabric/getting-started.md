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

Application settings can be set in ```config/application.yaml```

After making changes the server needs to be restarted.

#### server port 

``` yaml
server:
  port : 8080
```

#### workspace

(meta)data is by default kept in the "workspace" directory

``` yaml
io.storydoc:
  workspaceFolder: workspace
```

make sure the directory exists and is accessible!

### jdbc drivers

by default no JDBC drivers are included

add a JDBC driver jar file for your database in the ```lib``` directory (subdir of the installation directory)  and restart

## Running the server

- on Windows: 
```
run.bat
```
- on Linux:
```
chmod u+x run.sh
./run.sh
```

