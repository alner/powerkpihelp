# Appearance

![](<../.gitbook/assets/image (24).png>)

It allows you to set title, subtitle and footnote.

![General](<../.gitbook/assets/image (25).png>)

“Alternate states” subsection can be used to apply an alternate state for an object. See Qlik Sense documentation for more details.

![Alternative states](<../.gitbook/assets/image (26).png>)

“Settings” subsection allows you to disable and hide “Export”, “Export data”, “View data” context menu options.&#x20;



<figure><img src="../.gitbook/assets/AppearSettings.png" alt=""><figcaption><p>Custom settings</p></figcaption></figure>



![Visualization context menu](<../.gitbook/assets/image (28).png>)

It also allows you to replace url in a browser adding a hashtag link of the active visualization using History API. Such option can be activated by setting "Replace "URL".

![Replace "URL"](<../.gitbook/assets/image (29).png>)



With custom themes developers can style Power KPI visualizations by applying custom classes using the "**CSS classes**" parameter.

<figure><img src="../.gitbook/assets/CssClasses.png" alt=""><figcaption></figcaption></figure>

For example, by defining the following classes inside a custom theme, you can achieve the following effects:

```css
.qv-object-powerkpi .powerkpi-theme {
  background: linear-gradient(#f2f2f2, white) !important;
  border: solid 1px #f2f2f2;
  border-radius: 5px;
}

.qv-object-powerkpi .powerkpi-theme:hover  {
  background: linear-gradient(#CFF0F8, white) !important;
  border: solid 1px #3b93bd;
}
```

<figure><img src="../.gitbook/assets/CssClasses.gif" alt=""><figcaption></figcaption></figure>
