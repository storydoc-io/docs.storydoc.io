# Settings page

On the settings page you can 
- maintain a list of ___datasources___ and ___environments___
- add connection details per environment for a datasource
- manage metadata for each datasource

## Environments

### Environments tab

On the ___environments tab___ you can maintain a list of environments.

An environment names an instance of the system used for a specific purpose, e.g. DEV, QA, Production

[![settings-page-environments]][settings-page-environments]

[settings-page-environments]: settings-page-environments.png

### Environment dialog 

An environment has a key and a label.

[![settings-page-add-environment]][settings-page-add-environment]

[settings-page-add-environment]: settings-page-add-environment.png


## Datasources

### Datasources tab

A datasource identifies a database of the system, independent of an environment. It is a logical identifier for a database component of the system. 

[![settings-page-datasources]][settings-page-datasources]

[settings-page-datasources]: settings-page-datasources.png

### Datasource dialog

A datasource has a key, label and database type 

[![settings-page-add-datasource]][settings-page-add-datasource]

[settings-page-add-datasource]: settings-page-add-datasource.png


### Connection settings tab

When a datasource is selected, the ___database details panel___ for this datasource is displayed.

The ___connection settings tab___ allows to enter the connection details of a datasource per environment.

[![settings-page-connection-settings-tab]][settings-page-connection-settings-tab]

[settings-page-connection-settings-tab]: settings-page-connection-settings-tab.png

### Connection settings dialog

The connection details to be entered are depending on the database type.

You can ___test___ the connection before saving the settings.

[![settings-page-add-connection-settings]][settings-page-add-connection-settings]

[settings-page-add-connection-settings]: settings-page-add-connection-settings.png
