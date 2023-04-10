# Actions

There is a **predefined set of actions** based on Qlik stable API:

* “**Set variable**” action allows you not only to create and set variables with custom values or using expressions, but also to set variables based on a “current” dataset row dimensions and measure values
* “**Activate view**” action allows you to interactively visualize one from predefined sets of visualization templates. Users can manually activate views in accordance with user interactions (clicking and tapping) or conditionally - using expression;
* “**Go to sheet**”, “**Next sheet**”, “**Previous sheet**”, “**Go to story**”, “**Go to url**” allow business users in just one click to open the appropriate business data context – sheet, story or even another application;
* “**Select values**”, “**Select all**”, “**Select match**”, “**Select alternative**”, “**Select possible**”, “**Select excluded**”, “**Toggle select**”, “**Clear**”, “**Clear all**”, “**Clear other**”, “**Lock**”, “**Lock all**”, “**Unlock**”, “**Unlock all**”, “**Create bookmark**”, “**Apply bookmark**”, “**Remove bookmark**” set of actions allows you to extend standard based selections model with custom selections scenarios during user interaction with data visualizations;
* “**Reload**”, “**Partial reload**” actions allow you to load data on demand;
* “**Export data**” action allows you to export data not only from the current data view but also from any predefined master visualization item;
* “**Value color**” and “**Mini chart**” actions allow you to represent numbers in one of graphically predefined ways;
* “**Zoom in**” and “**Zoom out**” actions allow you to expand visualization in full screen mode and close it;
* “**Sort**” action allows you to apply or remove interactive sorting capability for each column separately (in case of table representations);
* “**Alternative dimensions/measures**” action allows you to apply or remove interactive dimensions and measures buttons separately for each data column labels;
* “**Searchable dimension**” action allows you to apply or remove search functionality for each individual dimension column;
* **"Show dialog"** allows you to use a custom popup dialog with a content formatted using HTML and embedding master visualizations support;
* **"Show tooltip"** allows you to create custom tooltips with possibility to use HTML;
* **"Show sidebar"** allows you to show a sidebar with some content;
* **"Show popover"** allows you to show a popup window with some content;
* and others.

{% hint style="info" %}
See the detailed description of the actions in the following sections.
{% endhint %}

Click <img src="../.gitbook/assets/image (66).png" alt="" data-size="original">toolbar  button to **open actions panel**.

![](../.gitbook/assets/2019-04-02\_15-40-33.gif)

There are object-level actions ("General" tab) and cell-level actions ("Cells" tab). When the user clicks on a visualization, the object-level action fires first, followed by the cell-level actions.

<figure><img src="../.gitbook/assets/ObjectLevelAction.png" alt=""><figcaption></figcaption></figure>

You can apply the set of actions to any cell or cells to make the visualization more interactive and functional.

To add an action, click <img src="../.gitbook/assets/image (113).png" alt="" data-size="original">button on "Actions" panel. You may apply as many actions as you want on any cell.

{% hint style="info" %}
Some actions are applicable on a cell with a bonded dimension, some - with a measure, and there are actions which can be applied on any cell.
{% endhint %}

Cells with the applied actions will have <img src="../.gitbook/assets/image (112).png" alt="" data-size="original">special icon in the top left corner when “Actions” panel will be shown.

You can drag an action to change the execution order. Put the cursor on the <img src="../.gitbook/assets/image (124).png" alt="" data-size="original"> drag bars and drag the action to rearrange the execution order.

![](../.gitbook/assets/2019-04-02\_17-34-28.gif)

To remove an action from the applied actions list, click <img src="../.gitbook/assets/image (125).png" alt="" data-size="original">.
