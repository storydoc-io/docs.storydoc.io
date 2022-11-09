# Console

## Connecting

Open a connection by selecting a datasource and an environment from the console menu and clicking the connect icon.

[![console-connect]][console-connect]

[console-connect]: console-connect.png

Once the connection is open the menu will show the active datasource and environment. 

## Disconnecting

You can close the connection by hovering the mouse over the active connection and clicking the close icon.

[![console-disconnect]][console-disconnect]

[console-disconnect]: console-disconnect.png


## Running a query

Run a query by filling in the fields of the __query input panel__ and click the __run__ button

[![console-run-query]][console-run-query]

[console-run-query]: console-run-query.png

## Using the history panel

The __history panel__ shows a list of queries that have successfully run in the current session.

A history item has actions to 

  - convert the item [into a snippet](#convert-to-snippet)
  - re-run the item
  - delete it from the history

[![console-history]][console-history]

[console-history]: console-history.png

## Convert to snippet

A snippet is persistent across sessions and can be used to keep frequently used queries. 

When you click the __To Snippet__ action on a history item, the __create snippet dialog__ is shown

You can name the snippet and make some modifications to the query, e.g. parametrize it by replacing some of the parameters with a placeholder.  

[![console-snippet-dialog]][console-snippet-dialog]

[console-snippet-dialog]: console-snippet-dialog.png


## Using the snippet panel

The __snippets panel__ contains a list of frequently used queries. The list is not session specific, i.e. persistent across sessions.

Select a snippet to copy it into the __query input panel__  

[![console-snippets]][console-snippets]

[console-snippets]: console-snippets.png

