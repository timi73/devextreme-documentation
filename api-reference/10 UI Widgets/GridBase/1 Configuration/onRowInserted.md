---
EventForAction: ..\4 Events\rowInserted.md
default: null
type: function(e)
---
---
##### shortDescription
A handler for the **rowInserted** event. Executed after a new row has been inserted into the data source.

##### param(e): Object
Information about the event.

##### field(e.component): Object
The [widget's instance](/api-reference/10%20UI%20Widgets/Component/3%20Methods/instance().md '{basewidgetpath}/Methods/#instance').

##### field(e.element): jQuery
The widget's container.

##### field(e.model): Object
The model data. Available only if you use Knockout.

##### field(e.data): Object
The data of the row.

##### field(e.key): any
The key of the row. If a field providing keys is not specified in the data source, the whole data object is considered the key.

##### field(e.error): JavaScript Error object
The standard [Error](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Error) object defining an error that may occur during insertion.

---
[note] In batch [editing mode](/api-reference/10%20UI%20Widgets/GridBase/1%20Configuration/editing/mode.md '{basewidgetpath}/Configuration/editing/#mode'), if several rows have been inserted, this handler will be executed for each row individually.