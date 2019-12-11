---
EventForAction: ..\4 Events\titleRendered.md
default: null
type: function(e)
---
---
##### shortDescription
A handler for the [titleRendered](/api-reference/10%20UI%20Widgets/dxTabPanel/4%20Events/titleRendered.md '/Documentation/ApiReference/UI_Widgets/dxTabPanel/Events/#titleRendered') event.

##### param(e): Object
Provides function parameters.

##### field(e.component): Object
Provides access to the widget's instance.

##### field(e.element): jQuery
An HTML element of the widget.

##### field(e.model): Object
Provides access to the data that is available for binding against the element. Available only in the Knockout approach.

##### field(e.itemData): object
The data that is bound to the item whose title should be rendered.

##### field(e.itemElement): jQuery
An HTML element of the item.

---
Assign a function to perform a custom action after a collection item title is rendered.