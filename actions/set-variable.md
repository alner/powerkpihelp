# Set Variable

The action will set a variable value based on the manually entered text/expression or selected dimension/measure.&#x20;

{% hint style="info" %}
Variable will be created during the action execution if it was not created before.
{% endhint %}



![](<../.gitbook/assets/image (114).png>)

In the “**Variable**” parameter you can specify a variable name by selecting a variable from the list by clicking the ![](<../.gitbook/assets/image (115).png>) button or entering it manually.

A Qlik expression can be used in the “Variable” parameter by prefixing a variable with an equals sign, e.g.:

```
=if(someCondition, 'var1', 'var2')
```

In the “**Value**” parameter you can manually enter a value or select a dimension/measure by clicking the![](<../.gitbook/assets/image (116).png>) special button. A Qlik expression can be used by prefixing a value with an equals sign.
