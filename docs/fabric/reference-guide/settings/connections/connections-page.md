# Connection Settings page

You can navigate to the __connection settings page__ via the __datasources__ entry in the __side menu__ and clicking __settings__ for a datasource.

The __connection settings page__ allows to enter the connection details of a datasource per environment.

[![connections]][connections]

[connections]: connections.png

### Connection settings dialog

When adding or editing a connection between a datasource and an environment the __connection settings dialog__ is shown.

The __connection parameters__ to be entered are depending on the datasource type (JDBC, ELASTICSEARCH ...) .

You can __test__ the connection before saving the settings.

[![add-connection]][add-connection]

[add-connection]: add-connection.png

!!! tip "tip: Testing JDBC connections"

    To test a JDBC connection you first need to [install the JDBC driver] for the database.  

[install the JDBC driver]: ../getting-started.md#jdbc-drivers
