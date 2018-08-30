# Discord Dungeons API Documents

Privacy Policy
The Discord Dungeons API Privacy Policy can be found at [https://api.discorddungeons.me/Privacy](https://api.discorddungeons.me/Privacy)

{% api-method method="get" host="https://api.discorddungeons.me" path="/v3/bulk/:user,:user,:user" %}
{% api-method-summary %}
Bulk user
{% endapi-method-summary %}

{% api-method-description %}
Get more than one user at a time
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="user" type="string" required=true %}
The ID of the user(s) to get
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-headers %}
{% api-method-parameter name="Authentication" type="string" required=true %}
Your API Key
{% endapi-method-parameter %}
{% endapi-method-headers %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Bulk users gotten
{% endapi-method-response-example-description %}

```javascript
[[User Object](), [User Object]()]
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

