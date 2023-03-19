# statusEmbed

Create an embed which will show users the status of a request

**Parameters:**

`description`: string - The description which would be displayed on the status embed

`success`: boolean - Was the request a success

**Returns:**

`object`&#x20;



**Use case example**

{% code lineNumbers="true" %}
```javascript
async execute() {
    this.statusEmbed('Your request was a success', true);
}
```
{% endcode %}
