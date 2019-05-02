# Go to URL

The action will navigate a user to a given URL.

![](../.gitbook/assets/image%20%289%29.png)

A URL should contain a schema \(http://, https://\) to be able to open absolute URLs. If the schema isn’t specified, it will try to open a relative path.

Optional “Name” parameter can be used to specify the name of the browsing context \(window, [&lt;iframe&gt;](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/iframe) or tab\) into which to load the specified resource.

{% hint style="info" %}
See [https://developer.mozilla.org/en-US/docs/Web/API/Window/open](https://developer.mozilla.org/en-US/docs/Web/API/Window/open) for more details.
{% endhint %}

Qlik expressions can be used in both parameters by prefixing each of them with an equals sign.

