# Data

“Data” section of the toolbar contains the following buttons:

![](../.gitbook/assets/DataPanel.png)

{% hint style="info" %}
Dimensions / Measures
{% endhint %}

* ![](<../.gitbook/assets/image (61).png>)**open data panel** contains dimensions and measures which can be bonded to cell using simple drag-and-drop:

![](<../.gitbook/assets/image (62).png>)

Data panel will show all dimensions (if any were used) and measures which were added to Data section of the properties panel.

Each dimension and measure contain “Label” ![](<../.gitbook/assets/image (63).png>) button, which will allow you to bind dimension/measure label within the template. Each measure, except the “Label” button, contains “Totals” ![](<../.gitbook/assets/image (64).png>) button. It allows you to bind the total calculated for appropriate measure within the template. It makes sense to use “Totals” when constructing table-like templates.

To bind a measure/dimension with the appropriate cell, select a cell and click the appropriate measure/dimension. Or, if you prefer, drag data item (dimension, measure, label or total) onto the template and drop it on the appropriate cell. In such a way you will bind your data assets to the designed template.

![](../.gitbook/assets/2019-04-02\_11-16-58.gif)

{% hint style="info" %}
Delete
{% endhint %}

* ![](<../.gitbook/assets/image (65).png>)**delete selected cell/cells binding** (dimensions, measures, text, icons, images etc.)

![](../.gitbook/assets/2019-04-02\_11-21-12.gif)

{% hint style="info" %}
Actions
{% endhint %}

* ![](<../.gitbook/assets/image (66).png>) **open actions panel** allows you to apply actions on the selected cell

![](<../.gitbook/assets/image (67).png>)

{% hint style="info" %}
See “Actions” section of the documentation for more details.
{% endhint %}

{% content-ref url="../actions/" %}
[actions](../actions/)
{% endcontent-ref %}

{% hint style="info" %}
Tags
{% endhint %}

* ![](<../.gitbook/assets/image (75).png>) **open “Tags” panel** allows you to make a markup of template to be able to build table-like views (it makes sense to use only for table-like views with dimensions)

![](<../.gitbook/assets/image (68).png>)

For table-like templates you will have to select row numbers which correspond to the details rows, and then click on “Rows” tag ![](<../.gitbook/assets/image (69).png>).

In such a way you will always have to tag details rows for table-like templates:

![](../.gitbook/assets/2019-04-02\_10-53-45.gif)

If you need to change your markup, you can click on ![](<../.gitbook/assets/image (71).png>) icon to remove the markup and tag your rows in a different way.

![](<../.gitbook/assets/image (70).png>)

{% hint style="info" %}
Text
{% endhint %}

* ![](<../.gitbook/assets/image (72).png>) **insert any text into the selected cell**

![](../.gitbook/assets/2019-04-02\_11-08-04.gif)

{% hint style="info" %}
Icons
{% endhint %}

* ![](<../.gitbook/assets/image (73).png>) **insert an icon into the selected cell**

![](../.gitbook/assets/2019-04-02\_11-05-29.gif)

It allows you to choose an icon, position (left, right or replace the content in a cell), icon font and font size.

In case of the "Replace" option it completely replaces the cell content. It makes sense to select such option on the cell with linked measure. In such a way, icon will be displayed instead of the measure's value, but it will be possible, for example, to use the Value Color action that will change the icon color based on the measure's value. So, you will be able to get the result as it is shown on the image below, when the measure's values were replaced with the red or green "dot" icon.

![](../.gitbook/assets/IconsReplacesValues.png)

{% hint style="info" %}
See Demo Apps for more details
{% endhint %}

{% content-ref url="../demo-apps.md" %}
[demo-apps.md](../demo-apps.md)
{% endcontent-ref %}

{% hint style="info" %}
Images
{% endhint %}

* ![](<../.gitbook/assets/image (74).png>)**insert an image** in the selected cell from the content library

![](../.gitbook/assets/Data1.png)

{% hint style="info" %}
See "Content libraries" in Qlik help for more details

[https://help.qlik.com/en-US/sense/Subsystems/ManagementConsole/Content/Sense\_QMC/content-libraries-overview.htm](https://help.qlik.com/en-US/sense/Subsystems/ManagementConsole/Content/Sense\_QMC/content-libraries-overview.htm)
{% endhint %}

![](../.gitbook/assets/2019-04-02\_11-31-16.gif)

Image ![](<../.gitbook/assets/image (76).png>) button will allow you to select an image from one of the predefined content libraries.

It is also possible to embed an image in a visualization template using BASE64 encoding.

![](../.gitbook/assets/Base64.gif)

Alternatively, if the selected cell contains data binding (dimension/field with images links), you might want to select “From a field” option.

![](../.gitbook/assets/2019-04-02\_11-38-31.gif)

“Sizing” parameter allows you to choose one of the predefined values to size image accordingly inside the selected cell.

Using “Position” parameter, you might position an image in accordance with your requirements inside the selected cell.

{% hint style="info" %}
Master items
{% endhint %}

To embed a master visualization in a cell click on a toolbar button  <img src="../.gitbook/assets/MasterItemsToolbar.png" alt="" data-size="line"> and select a master visualization in the popup menu.&#x20;

![](../.gitbook/assets/MasterObject.gif)

It also possible to use the context menu for the selected cell (select a cell and click on the right mouse key), which allows to change the interaction and selection options for the master object, or delete **** the **** embedded master object.

![](../.gitbook/assets/MasterItemsInContextMenu.png)
