---
type: eventType
---
---
##### shortDescription
Fires before the lookup list is refreshed as a result of the "pull down to refresh" gesture.

##### param(e): object
Provides function parameters.

##### field(e.component): object
Provides access to the widget's instance.

##### field(e.element): jQuery
An HTML element of the widget.

##### field(e.model): object
Provides access to the data that is available for binding against the element. Available only in the Knockout approach.

---
Instead, you can use the [onPullRefresh](/api-reference/10%20UI%20Widgets/dxLookup/1%20Configuration/onPullRefresh.md '/Documentation/ApiReference/UI_Widgets/dxLookup/Configuration/#onPullRefresh') option to handle the event.

[note]The "pull down to refresh" gesture is not supported by desktop browsers and Windows Phone devices. You can use it only in [mobile themes](/concepts/60%20Themes/10%20Predefined%20Themes '/Documentation/Guide/Themes/Predefined_Themes/') except the Windows Phone theme.

#####See Also#####
#include common-link-handleevents