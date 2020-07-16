# Font

“Font” section of the toolbar contains the following buttons:

![](../.gitbook/assets/fonttools.png)

* ![](../.gitbook/assets/image%20%2834%29.png) - make text bold
* ![](../.gitbook/assets/image%20%2888%29.png) - make text italic
* ![](../.gitbook/assets/image%20%28101%29.png) - make text underlined
* ![](../.gitbook/assets/image%20%281%29.png) - select font size

![](../.gitbook/assets/fontsize.png)

It allows you to select or enter the text size. There are several ways to specify the font size, including keywords or numerical values for pixels or ems.

{% hint style="info" %}
See [https://developer.mozilla.org/en-US/docs/Web/CSS/font-size](https://developer.mozilla.org/en-US/docs/Web/CSS/font-size) for more details
{% endhint %}

* ![](../.gitbook/assets/image%20%2866%29.png) - make text multiline
* ![](../.gitbook/assets/image%20%2889%29.png) - make text responsive and, thus, the text will always fit the cell size \(this option should always be used for responsive visualization templates\)

{% hint style="info" %}
If you make the text responsive and specify the font size at same time, it will be responsive but not more than the specified size.
{% endhint %}

* ![](../.gitbook/assets/fonttag.png) - allows to set a font tag which defines global font size context. It will apply the same font size using same font in the PowerKPI objects if they have same size on a sheet as well as  the same cells size in the visualization templates. This button will be shown if the responsive option set by using the ![](../.gitbook/assets/image%20%2889%29.png)toolbar button.

![](../.gitbook/assets/fonttags.gif)

![Same font size when font tags have been applied on the Margin YTD and Orders YTD KPIs](../.gitbook/assets/samefontsize.png)

![Different font size without font tags](../.gitbook/assets/differentfontsize.png)

* ![](../.gitbook/assets/image%20%2872%29.png) - clear applied font styles
* ![](../.gitbook/assets/image%20%28132%29.png) - set font color
* ![](../.gitbook/assets/image%20%28149%29.png) - select and apply font on the selected cell/cells

![](../.gitbook/assets/fonts.png)

Fonts with special icon ![](../.gitbook/assets/image%20%2884%29.png) to the right from the font name specify that the font comes as an external font included with PowerKPI component, and thus, it will be loaded and used automatically.

Fonts without ![](../.gitbook/assets/image%20%2884%29.png) icon should be available \(installed\) on the user computer. If the specified font isn’t be available on the client side, the default web browser font will be used instead.

![](../.gitbook/assets/2019-04-02_14-22-27.gif)



