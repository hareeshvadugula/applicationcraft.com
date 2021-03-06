---
old_url: context_menu.htm
title: "Context Menu"
active_menu_item: developers
class_name: developers
full_width: true
---


The Context Menu widget should be considered to be in a Beta state until mention of it is removed from the documentation and is accessible from the Mobile section of the Toolbox

The Context Menu widget can be used to show a simple pop up selection box in a similar way to the [Popup Dropdown](/developers/documentation/product-guide/widget-properties-events/mobile/popup-dropdown) . The widget is not visible in runtime so can be placed anywhere on your page. As the Parent widget is selected it will present the pop up selection. A single item can be selected and any widget can be set as the Parent widget (eg a label widget when clicked/touched)

<table>
<tr>
<td width="148">
<a id="general"> </a> <b>General</b>

</td>
<td width="15">
</td>
<td width="779">
</td>
</tr>
<tr>
<td width="148">
Widget Class

</td>
<td width="15">
</td>
<td width="779">
Internal class name of the widget.- WiziCore_UI_ContextMemuMobileWidget

</td>
</tr>
<tr>
<td width="148">
Name

</td>
<td width="15">
</td>
<td width="779">
This is the Widget name that is displayed when references are made to the Widget. You can choose any name that includes alphanumeric characters.

</td>
</tr>
<tr>
<td width="148">
Items

</td>
<td width="15">
</td>
<td width="779">
    This is where you can prefill your list/dropdown widgets either manually or by importing a CSV list stored as a resource. See <a href="/developers/documentation/product-guide/widget-properties-events/prefill">Prefill</a> or by code, see <a href="/developers/documentation/scripting-apis/client-scripting-overview/scripting-with-javascript/widget-reading-writing/widget-content-reading-and-writing/context-menu2">Context Menu</a>

</td>
</tr>
<tr>
<td width="148">
Parent Widget

</td>
<td width="15">
</td>
<td width="779">
Select the widget to invoke the Context Menu

</td>
</tr>
</table>
<table>
<tr>
<td width="148">
<a id="behavior"> </a> <b>Behavior</b>

</td>
<td width="15">
</td>
<td width="779">
</td>
</tr>
<tr>
<td width="148">
Enable

</td>
<td width="15">
</td>
<td width="779">
Set to false to leave the Widget visible but to prevent any user interaction.

</td>
</tr>
</table>
<table>
<tr>
<td width="148">
<a id="style"> </a> <b>Style</b>

</td>
<td width="15">
</td>
<td width="779">
</td>
</tr>
<tr>
<td width="148">
Mobile Theme

</td>
<td width="15">
</td>
<td width="779">
  Where you can set the Theme colors for the widget. See <a href="/developers/documentation/product-guide/mobile-apps-sites/mobile-themes">Mobile Themes</a>

</td>
</tr>
<tr>
<td width="148">
Custom CSS Classes

</td>
<td width="15">
</td>
<td width="779">
  Where you define your CSS Style to customise your widgets  See also <a href="/developers/documentation/product-guide/advanced-features/custom-css-classes/">Custom CSS Classes</a>

</td>
</tr>
<tr>
<td width="148">
Widget Style

</td>
<td width="15">
</td>
<td width="779">
  This refers to the <a href="/developers/documentation/product-guide/content-and-app-layout/introduction/themes-styles/themesmanage">Theme entry</a> that should be used to set the Widget's default appearance. Once a Theme Style has been selected, individual components such as Font and Colors can be Set to False if you want the Widget to appear hidden by default.

</td>
</tr>
</table>

<table>
<tr>
<td width="148">
  <strong>Supported Events:</strong>

</td>
<td width="15">
</td>
</tr>
<tr>
<td width="148">
  <a href="/developers/documentation/product-guide/widget-properties-events/events/event-reference-list/general-events">General Events</a>

</td>
<td width="15">
</td>
</tr>
<tr>
<td width="148">
On Click

</td>
<td width="15">
</td>
</tr>
<tr>
<td width="148">
On Pre Show

</td>
<td width="15">
</td>
</tr>
</table>

## See Also

 - [Popup Dropdown](/developers/documentation/product-guide/widget-properties-events/mobile/popup-dropdown)
 - [Popup Listbox](/developers/documentation/product-guide/widget-properties-events/mobile/popup-listbox)
 - [General Events](/developers/documentation/product-guide/widget-properties-events/events/event-reference-list/general-events)

