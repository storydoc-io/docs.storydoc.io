# Settings page

On the settings page you can 
* maintain a list of ___datasources___ and ___environments___
* add connection details per environment for a datasource
* manage metadata for each datasource

## Environments

### Environments tab

On the environments tab you can maintain a list environments

An environment names an instance of the system used for a specific purpose, e.g. DEV, QA, Production

[![settings-page-environments]][settings-page-environments]

[settings-page-environments]: settings-page-environments.png

An environment has a key and a label.

[![settings-page-add-environment]][settings-page-add-environment]

[settings-page-add-environment]: settings-page-add-environment.png


## Datasources

### Managing datasources

A datasource identifies a database of the system, independent of an environment. It is a logical identifier for the database. 

[![settings-page-datasources]][settings-page-datasources]

[settings-page-datasources]: settings-page-datasources.png

A datasource has a key, label and database type 

[![settings-page-add-datasource]][settings-page-add-datasource]

[settings-page-add-datasource]: settings-page-add-datasource.png


### Managing connections of a datasource to different environments

When a datasource is selected, a list of ___connection settings___ per environment is displayed.

The connection details to be entered are depending on the database type.

You can ___test___ the connection before saving the settings.

[![settings-page-add-connection-settings]][settings-page-add-connection-settings]

[settings-page-add-connection-settings]: settings-page-add-connection-settings.png
