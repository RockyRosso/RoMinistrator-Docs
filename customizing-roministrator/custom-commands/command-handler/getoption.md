# getOption

Get an option from the interaction data

**Parameters:**

`option_type`: number - The type of option which you're trying to call

`option_name`: string - The name of the option which you're trying to call

`sub_cmd`: object(optional) - The sub command which the option is located

**Returns:**

`object`



**Use case example**

{% code lineNumbers="true" %}
```javascript
async execute() {
    this.getOption(this.options.string, 'name');
}
```
{% endcode %}

