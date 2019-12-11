---
default: 'native', 'rollers' (android_below_version_4, desktop, windows), 'calendar' (generic_desktop, no-phone_windows)
acceptValues: 'calendar' | 'list' | 'native' | 'rollers'
type: String
---
---
##### shortDescription
Specifies the type of the date/time picker.

---
This option accepts the following values.

- "native"  
 The picker type depends on the current platform or web browser.

- "calendar"  
 The date box uses the **Calendar** widget to pick data. This value applies only when the [type](/api-reference/10%20UI%20Widgets/dxDateBox/1%20Configuration/type.md '/Documentation/ApiReference/UI_Widgets/dxDateBox/Configuration/#type') option is set to "date" or "datetime".

- "rollers"  
 The widget uses rollers to pick the date and time.

- "list"  
 The widget uses the list of time values to pick the time. This value applies only when the [type](/api-reference/10%20UI%20Widgets/dxDateBox/1%20Configuration/type.md '/Documentation/ApiReference/UI_Widgets/dxDateBox/Configuration/#type') option is set to "time".

When using the widget as an [ASP.NET MVC Control](/concepts/35%20ASP.NET%20MVC%20Controls/20%20Fundamentals '/Documentation/Guide/ASP.NET_MVC_Controls/Fundamentals/'), specify this option using the `DateBoxPickerType` enum. This enum accepts the following values: `Native`, `Calendar`, `Rollers` and `List`.