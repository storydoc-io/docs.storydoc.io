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

!!! tip

    restart the server after making changes to the ```application.yaml```file    

`server port` 

:   the default port is 8080
    
    ``` yaml
    server:
      port : 8080
    ```

`workspace`

:   (meta)data is by default kept in the ```workspace``` directory
        
    ``` yaml
    io.storydoc:
      workspaceFolder: workspace
    ```
    
    !!! tip 
    
        The default ```workspace``` directory is part of the installation. If you change the workspace directory, make sure the alternate workspace directory exists and is accessible.  


### jdbc drivers

by default no JDBC drivers are included

add a JDBC driver jar file for your database in the ```lib``` directory (subdir of the installation directory) 

!!! tip

    restart the server after adding a jar file in the ```lib``` directory    

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

