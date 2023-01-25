# Metamodel Settings page

You can navigate to the __metamodel settings page__ via the __datasources__ entry in the __side menu__ and clicking __metamodel__ for a datasource.

### Fetching metamodel for a datasource

Click __fetch__ to open the __fetch metamodel dialog__

[![fetch-dialog]][fetch-dialog]

[fetch-dialog]: fetch-dialog.png


!!! tip "tip: Set connection details before fetching metadata"

    To fetch the metamodel from an environment you first need to [define the environment] and [define the connection settings for this environment].  

  [define the environment]: ../environments/environments-page.md
  [define the connection settings for this environment]: ../connections/connections-page.md


### Metamodel Navigator

The metamodel is organized in columns as in MacOSX Finder. E.g. for an SQL  datasource select a table to show the table
details in a second column, the click a foreign key to see the foreign key details in te next column.


[![navigator]][navigator]

[navigator]: navigator.png

To refresh the metamodel, click the __reload__  button to open the __fetch metamodel dialog__ and select the environment to reload from.

