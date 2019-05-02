# Add-ons

It allows you to suppress zero values and add calculation condition:

* **Include zero values**: When unselected, measures that have the value ‘0’ are not included in the presentation. If there is more than one measure value, all the measure values must have the value ‘0’ to be excluded from the presentation.
* **Calculation condition**: Specify an expression in this text field to set a condition that needs to be fulfilled \(true\) for the object to be displayed. The value may be entered as a calculated formula. For example: count\(distinct Team\)&lt;3. If the condition is not fulfilled, the message or the expression entered in Displayed message is displayed.

  A calculation condition is useful when a chart or a table is very big and makes the visualization slow to respond. A calculation condition can then help so that, for example, an object is not shown until the user has filtered the data to a more manageable level by applying selections.

![](../.gitbook/assets/image%20%28129%29.png)

See Qlik Sense documentation for more details.

