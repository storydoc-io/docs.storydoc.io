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

To change the settings open config/application.yaml

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

add a JDBC driver jar in the "lib" directory (subdir of the installation directory)  and restart


