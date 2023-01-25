# Settings page

On the settings page you can 

- maintain a list of ___datasources___ and ___environments___
- add connection details per environment for a datasource
- manage metadata for each datasource

## Environments

### Environments tab

On the __environments tab__ you can maintain a list of environments.

An environment names an instance of the system used for a specific purpose, e.g. DEV, QA, Production

[![settings-page-environments]][settings-page-environments]

[settings-page-environments]: settings-page-environments.png

### Environment dialog 

When adding or editing an environment the __environment dialog__ is shown.

Here you can set the key and a label for the environment.

[![settings-page-add-environment]][settings-page-add-environment]

[settings-page-add-environment]: settings-page-add-environment.png


## Datasources

### Datasources tab

On the __datasources tab__ you can maintain a list of datasources.

A datasource identifies a database of the system, independent of an environment. It is a logical identifier for a database component of the system. 

[![settings-page-datasources]][settings-page-datasources]

[settings-page-datasources]: settings-page-datasources.png

### Datasource dialog

When adding or editing a datasource the __datasource dialog__ is shown.

Here you can set the key, a label and the datasource type (JDBC, ELASTICSEARCH ...) for the datasource.

[![settings-page-add-datasource]][settings-page-add-datasource]

[settings-page-add-datasource]: settings-page-add-datasource.png


### Connection settings tab

When a datasource is selected, the __datasource details panel__ for this datasource is shown under the datasource list.

The __connection settings tab__ allows to enter the connection details of a datasource per environment.

[![settings-page-connection-settings-tab]][settings-page-connection-settings-tab]

[settings-page-connection-settings-tab]: settings-page-connection-settings-tab.png

### Connection settings dialog

When adding or editing a connection between a datasource and an environment the __connection settings dialog__ is shown.

The __connection parameters__ to be entered are depending on the datasource type (JDBC, ELASTICSEARCH ...) .

You can __test__ the connection before saving the settings.

[![settings-page-add-connection-settings]][settings-page-add-connection-settings]

[settings-page-add-connection-settings]: settings-page-add-connection-settings.png

!!! tip "tip: Testing JDBC connections"

    To test a JDBC connection you first need to [install the JDBC driver] for the database.  

  [install the JDBC driver]: ../getting-started.md#jdbc-drivers

### Metadata settings page

You can navigate to the __metadata settings page__ for a datasource by clicking the __metadata button__ on the __datasource overview page__ .

[![settings-datasource-metamodel]][settings-datasource-metamodel]

[settings-datasource-metamodel]: settings-datasource-metamodel.png

The metadata is organized in columns as in MacOSX Finder. E.g. for an SQL  datasource select a table to show the table 
details in a second column, the click a foreign key to see the foreign key details in te next column.

To refresh the metadata, click the __reload__  button and select the environment to load the metadata from.
