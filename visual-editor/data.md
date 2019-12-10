# Data

“Data” section of the toolbar contains the following buttons:

![](../.gitbook/assets/datapanel.png)

{% hint style="info" %}
Dimensions / Measures
{% endhint %}

* ![](../.gitbook/assets/image%20%2891%29.png)
  - **open data panel** contains dimensions and measures which can be bonded to cell using simple drag-and-drop:

![](../.gitbook/assets/image%20%2892%29.png)

Data panel will show all dimensions \(if any were used\) and measures which were added to Data section of the properties panel.


Each dimension and measure contain “Label” ![](../.gitbook/assets/image%20%2870%29.png) button, which will allow you to bind dimension/measure label within the template. Each measure, except the “Label” button, contains “Totals”   ![](../.gitbook/assets/image%20%2848%29.png) button. It allows you to bind the total calculated for appropriate measure within the template. It makes sense to use “Totals” when constructing table-like templates. 

To bind a measure/dimension with the appropriate cell, select a cell and click the appropriate measure/dimension. Or, if you prefer, drag data item \(dimension, measure, label or total\) onto the template and drop it on the appropriate cell. In such a way you will bind your data assets to the designed template.

![](../.gitbook/assets/2019-04-02_11-16-58.gif)



{% hint style="info" %}
Delete
{% endhint %}

*   ****![](../.gitbook/assets/image%20%2859%29.png)- **delete selected cell/cells binding** \(dimensions, measures, text, icons, images etc.\)

![](../.gitbook/assets/2019-04-02_11-21-12.gif)



{% hint style="info" %}
Actions
{% endhint %}

* ![](../.gitbook/assets/image%20%282%29.png) - 
  **open actions panel** allows you to apply actions on the selected cell

![](../.gitbook/assets/image%20%2813%29.png)

{% hint style="info" %}
See “Actions” section of the documentation for more details.
{% endhint %}

{% page-ref page="../actions/" %}



{% hint style="info" %}
[](#Tags)Tags
{% endhint %}

* ![](../.gitbook/assets/image%20%2852%29.png) - 
  **open “Tags” panel** allows you to make a markup of template to be able to build table-like views \(it makes sense to use only for table-like views with dimensions\)

![](../.gitbook/assets/image%20%2861%29.png)

For table-like templates you will have to select row numbers which correspond to the details rows, and then click on “Rows” tag ![](../.gitbook/assets/image%20%2893%29.png).

In such a way you will always have to tag details rows for table-like templates:

![](../.gitbook/assets/2019-04-02_10-53-45.gif)

If you need to change your markup, you can click on ![](../.gitbook/assets/image%20%2819%29.png) icon to remove the markup and tag your rows in a different way.

![](../.gitbook/assets/image%20%2877%29.png)

\*\*\*\*

{% hint style="info" %}
Text
{% endhint %}

* ![](../.gitbook/assets/image%20%28140%29.png) 
  - **insert any text into the selected cell**

![](../.gitbook/assets/2019-04-02_11-08-04.gif)



{% hint style="info" %}
Icons
{% endhint %}

* \*\*\*\*![](../.gitbook/assets/image%20%2858%29.png) ****- **insert an icon into the selected cell**

![](../.gitbook/assets/2019-04-02_11-05-29.gif)

It allows you to choose an icon, a position \(left, right or replace the content in a cell\), icon font and font size. 

In case of the "Replace" option it completely replaces the cell content. It makes sense to select such option on the cell with a linked measure. In such a way, icon will be displayed instead of the measure's value, but it will be possible, for example, to use the Value Color action that will change the icon color based on the measure's value. So, you will be able to get the result as it is shown on the image below, when the measure's values were replaced with the red or green "dot" icon.

![](../.gitbook/assets/iconsreplacesvalues.png)

{% hint style="info" %}
See Demo Apps for more details
{% endhint %}

{% page-ref page="../demo-apps.md" %}



{% hint style="info" %}
Images
{% endhint %}

* ![](../.gitbook/assets/image%20%28133%29.png)- **insert an image** in the selected cell from a content library

![](../.gitbook/assets/data1.png)

{% hint style="info" %}
See "Content libraries" in Qlik help for more details

[https://help.qlik.com/en-US/sense/Subsystems/ManagementConsole/Content/Sense\_QMC/content-libraries-overview.htm](https://help.qlik.com/en-US/sense/Subsystems/ManagementConsole/Content/Sense_QMC/content-libraries-overview.htm)
{% endhint %}

![](../.gitbook/assets/2019-04-02_11-31-16.gif)

Image ![](../.gitbook/assets/image%20%2878%29.png) button will allow you to select an image from one of the predefined content libraries.

Alternatively, if the selected cell contains data binding \(dimension/field with images links\), you might want to select “From a field” option.

![](../.gitbook/assets/2019-04-02_11-38-31.gif)


“Sizing” parameter allows you to choose one of the predefined values to size image accordingly inside the selected cell.

 Using “Position” parameter, you might position an image in accordance with your requirements inside the selected cell.

