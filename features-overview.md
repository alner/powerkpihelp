# Features overview

PowerKPI component allows developers to visually design stunning-looking, responsive and interactive dashboards using **spreadsheet-like visual editor**: from simple kpi to interactive fancy and stunning-looking "table-like" data views \(with the ability to build custom multiline detailed row templates\).

See Demo Apps for more details.

{% page-ref page="demo-apps.md" %}

![Spreadsheet-like visual editor](.gitbook/assets/features1.png)

{% page-ref page="visual-editor/" %}

It allows developer to apply styles on a business visualization template using **fonts**, **backgrounds**, **images, borders, alignments, colors, icons**, etc. You can apply color on any cell, cell borders, and text using user-friendly color dialog.

![Colors](.gitbook/assets/features2.png)

Borders panel allows you not only to apply borders to cells, but also to set the style, thickness and color of lines.

![Borders](.gitbook/assets/features3.png)

If you need to get more expressive way of visualizing KPIs, just select and apply the appropriate font, set text color, vertical and/or horizontal alignment, make it responsive, multiline for a long text,

![Fonts](.gitbook/assets/features4.png)

or add images and icons to make your KPIs more readable.

![Image embedding](.gitbook/assets/features5.png)

PowerKPI is prepackaged with **set of fonts**, which can be used to format numbers and text. Also, there is a set of **icon fonts** included. You can even extend provided set of fonts with your own ones.

{% page-ref page="visual-editor/font.md" %}

![Icons fonts](.gitbook/assets/features7.png)

![](.gitbook/assets/features6.png)

Icons can be displayed based on expression entered in “Symbol” parameter of a dimension/measure:

![Showing icons using expression](.gitbook/assets/features8.png)

Data configuration using dimensions and measures doesn’t differ from making it with standard charts: use drag and drop or standard property panel. You can even add and use **alternative dimensions and measures**, which will be available for business users in your visualizations to choose during analysis.

![Alternative dimensions and measures](.gitbook/assets/features9.png)

Apart from all standard configuration capabilities, like sorting and add-ons, there is a possibility to add **unlimited number of visualizations templates and hypercubes** with its own set of dimensions and measures ****in one component in order to be able to make not only dimensions drills, but also to make “drill into kpi” feature.

{% page-ref page="properties/hypercubes.md" %}

{% page-ref page="properties/visualizations.md" %}

Using simple drag and drop \(or double click\) it is easy to bind dimensions and measures with appropriate cells of a visualization template.

![Dran and drop dimensions and measures](.gitbook/assets/features10.png)

It is easy to preview your template in edit mode.

![Visualization preview mode](.gitbook/assets/features11.png)

  
Sometimes you need not only to show KPIs based on current selections, but in many cases, it is necessary to activate another data view with an absolutely different set of dimensions and measures.

Just add unlimited number of data views bonded each with its own set of dimensions and measure, including alternative ones. You can then easily switch between visualization templates in design mode using property panel or special menu in top left corner.

![Unlimited number of visualization templates](.gitbook/assets/features12.png)

Visualization template can be activated based on user interactions using actions or conditionally, with help of expression, using visualization template name in “Show” property of property panel.

![Show visualization using expression](.gitbook/assets/features13.png)

 There is a **predefined set of actions** based on Qlik stable API:

*  “**Set variable**” action allows you not only to create and set variables with custom values or using expressions, but also set variables based on dimensions and measures values of a “current” dataset row
* “**Activate view**” action allows you to interactively visualize one from predefined sets of visualization templates. Users can activate views manually in accordance with user interactions \(clicking and tapping\) or conditionally - using expression
* “**Go to sheet**”, “**Next sheet**”, “**Previous sheet**”, “**Go to story**”, “**Go to url**” allows business users to open appropriate business data context in just one click – sheet, story or even another application
* “**Select values**”, “**Select all**”, “**Select match**”, “**Select alternative**”, “**Select possible**”, “**Select excluded**”,  “**Toggle select**”, “**Clear**”, “**Clear all**”, “**Clear other**”, “**Lock**”, “**Lock all**”, “**Unlock**”, “**Unlock all**”, “**Create bookmark**”, “**Apply bookmark**”, “**Remove bookmark**” set of actions allows you to extend standard based selections model with custom selections scenarios during user interaction with  data visualizations
* “**Reload**”, “**Partial reload**” actions allow you to load data on demand
* “**Export data**” allows you to export data not only from current data view but also from any predefined master visualization items
* “**Value color**” and “**Mini chart**” actions allow you to represent numbers in one of graphically predefined ways
* “**Zoom in**” and “**Zoom out**” actions allow you to expand visualization in full screen mode and close it
* “**Sort**” allows to you apply or remove interactive sorting capability for each column separately \(in case of table representations\)
* “**Alternative dimensions/measures**” action allows you to apply or remove interactive dimensions and measures buttons separately for each data column labels
* “**Searchable dimension**” allows you to apply or remove search functionality for each individual dimension column.

{% page-ref page="actions/" %}

You can apply a set of actions on any cell or cells to make the view more interactive. 

![](.gitbook/assets/features14.png)

See Actions section of this documentation for more details.

You can use master item library colors or conditionally control color with help of expressions \(background and text colors\), or even easier - apply “Value color” action.

![&quot;Value color&quot; action](.gitbook/assets/features15.png)



It is easy to add and customize histogram mini chart in your data view template using “Mini chart action”.

![&quot;Mini chart&quot; action](.gitbook/assets/features16.png)

Use one from a predefined set of minicharts to visually represent your KPIs. See “Mini chart” action of the documentation for more details.

![Mini chart customization](.gitbook/assets/features17.png)

Apart from advanced features, there are also standard Qlik Sense features available: **dimensions limits**, **null values and data handling**, **calculation conditions**, **background and text colors expressions**, **library color support**, **formatting**, **totals**, **sorting**, etc.

