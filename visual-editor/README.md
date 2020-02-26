# Visual editor

Visual editor allows you to create and edit visualization templates, which can be added using properties panel of the component \(see section “Visualizations” of the documentation\).

{% page-ref page="../properties/visualizations.md" %}

Spreadsheet-like visual editor allows developers to visually design stunning-looking, responsive and interactive visualizations: from simple kpi to interactive fancy and stunning-looking "table-like" data views \(with the ability to build custom multiline detailed row templates\).

![](../.gitbook/assets/visualeditor1.png)

To create an appropriate visualization template, you should add columns/rows, merge cells in accordance with the requirements.  Quick add buttons allows to easily add columns / rows.

![](../.gitbook/assets/quickaddcellsbuttons.gif)

You should bind dimensions and measures with the template, and then apply various styles options – fonts, alignment, borders, colors, backgrounds.

The "Dimensions/Measures" panel automatically opens up when new visualization created. "Apply all" button allows developers to apply and use all dimensions and measures configured on the data sections of the property panel. It also applies predefined set of actions like "Sort", "Alternative dimensions/measures", "Searchable dimension", "Select dimension value", etc.

![](../.gitbook/assets/productivityenhancements.gif)

To bind a dimension or measure with the template just double click on a cell or use **Ctrl + Space** \(**⌘ + Space**\)  to open dimensions and measures popup menu and then select an appropriate item.

![](../.gitbook/assets/dimsmeasurespopup.gif)

Editor context menu can be used to increase a developer productivity. Toolbar panel can also be collapsed to increase the working area and expanded again if need it.

![](../.gitbook/assets/contextmenu.gif)

To preview visualization, click “Preview” tab at the top of the toolbar. 

To open up the PowerKPI editor a developer should click on a button ![](../.gitbook/assets/image%20%28151%29.png) in the top left corner of the component or, as another option, open Visualizations sections on the property panel and then expand an appropriate  visualization and click on the "Edit template" button.

![](../.gitbook/assets/neweditmode.gif)

In the top left corner of the toolbar panel there is a button which allows a quick and easy switch between visualization templates \(if several visualizations have been created in one component\).

![](../.gitbook/assets/image%20%28100%29.png)

“Custom objects” tab allows you to preview and apply a predefined visualization template.

![](../.gitbook/assets/image%20%2874%29.png)



Button ![](../.gitbook/assets/image%20%2890%29.png) on the toolbar panel allows you to open the context menu, which allows copying, exporting and importing designed templates as well as opening template settings panel.

![](../.gitbook/assets/image%20%28104%29.png)

Settings panel allows to apply “Fit to height” parameter, which will shrink or stretch visualization to fit the occupied area. It is recommended to set this option on visualization templates for dashboards.

“Background image” allows adding an image as a background for templates. 

“Thumbnail” allows setting a thumbnail for templates.

![](../.gitbook/assets/image%20%2831%29.png)

The toolbar also has buttons to “undo/redo” changes and a “Save” button, along with template and hypercube titles.

![](../.gitbook/assets/image%20%2842%29.png)

The visualization template is displayed in a spreadsheet-like view with cells below the toolbar.

![](../.gitbook/assets/image%20%2839%29.png)

To be able to merge cells, you should select cells from the top left cell to the bottom right cell holding the left mouse button.

![](../.gitbook/assets/image%20%28135%29.png)

To apply some operations on several cells, you should select them holding "Ctrl" key.

To select an entire column, you should click the column header \(the cell with the column number\). In such a way, by clicking the row number, you can also select the entire row. It is possible to select several columns/rows by selecting the corresponding column/row headers.

Main operations are grouped by sections on the toolbar:

![](../.gitbook/assets/visualeditortoolbar.png)

*  “**Cells**” operations allow you adding/removing cells, as well as changing cells settings;

{% page-ref page="cells.md" %}

*  “**Data**” section contains operations which will allow you to bind data items \(dimensions and measures\), apply actions, insert text, icons, images;

{% page-ref page="data.md" %}

*  “**Borders**” will allow you to set borders and border styles on cells;

{% page-ref page="borders.md" %}

*  “**Alignment**” will allow you to align data horizontally and/or vertically;

{% page-ref page="alignment.md" %}

*  “**Font**” will allow you to apply font, size and styles/text behavior options.

{% page-ref page="font.md" %}

