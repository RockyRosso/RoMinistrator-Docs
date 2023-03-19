# listen

An initializer for the component listener

**Parameters:**

`client`: client - The bot client

`option`: object { forever: boolean (optional), time: number (optional) }  - Options for how the listener should act.

**Returns:**

`ComponentListener`&#x20;



**Use case example**

{% code lineNumbers="true" %}
```javascript
async execute() {
    const listener = componentListener.listen(this.client, { time: 60000 });
}
```
{% endcode %}
