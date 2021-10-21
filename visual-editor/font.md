# Font

“Font” section of the toolbar contains the following buttons:

![](../.gitbook/assets/FontTools.png)

* ![](<../.gitbook/assets/image (100).png>) - make text bold
* ![](<../.gitbook/assets/image (101).png>) - make text italic
* ![](<../.gitbook/assets/image (102).png>) - make text underlined
* ![](<../.gitbook/assets/image (103).png>) - select font size

![](../.gitbook/assets/FontSize.png)

It allows you to select or enter the text size. There are several ways to specify the font size, including keywords or numerical values for pixels or ems.

{% hint style="info" %}
See [https://developer.mozilla.org/en-US/docs/Web/CSS/font-size](https://developer.mozilla.org/en-US/docs/Web/CSS/font-size) for more details
{% endhint %}

* ![](<../.gitbook/assets/image (104).png>) - make text multiline
* ![](<../.gitbook/assets/image (105).png>) - make text responsive and, thus, the text will always fit the cell size (this option should always be used for responsive visualization templates)

{% hint style="info" %}
If you make the text responsive and specify the font size at same time, it will be responsive but not more than the specified size.
{% endhint %}

* ![](../.gitbook/assets/FontTag.png) - allows to set a font tag which defines global font size context. It will apply the same font size using same font in the PowerKPI objects if they have same size on a sheet as well as  the same cells size in the visualization templates. This button will be shown if the responsive option is set by using the ![](<../.gitbook/assets/image (105).png>)toolbar button.

![](../.gitbook/assets/FontTags.gif)

![Same font size when font tags have been applied on the Margin YTD and Orders YTD KPIs](<../.gitbook/assets/SameFontSize (1).png>)

![Different font size without font tags](../.gitbook/assets/DifferentFontSize.png)

* ![](<../.gitbook/assets/image (106).png>) - clear applied font styles
* ![](<../.gitbook/assets/image (107).png>) - set font color
* ![](<../.gitbook/assets/image (108).png>) - select and apply font on the selected cell/cells

![](../.gitbook/assets/Fonts.png)

Fonts with special icon ![](<../.gitbook/assets/image (110).png>) to the right from the font name specify that the font comes as an external font included with PowerKPI component, and thus, it will be loaded and used automatically.

Fonts without ![](<../.gitbook/assets/image (110).png>) icon should be available (installed) on the user computer. If the specified font isn’t available on the client side, the default web browser font will be used instead.

![](../.gitbook/assets/2019-04-02\_14-22-27.gif)

