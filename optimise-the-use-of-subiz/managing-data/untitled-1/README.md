# Synchronize users data with Subiz API

API \(_**application programming interface\)**_ is a set of clearly defined methods of communication between various software components. Subiz provides a Javascript API that synchronizes users data between the Subiz app and the website. You can update users information, retrieve users and clear users.

{% hint style="info" %}
Important notes:

* API snippets should be placed after the Subiz embed code in the website code page. No need to follow closely, just make sure the Subiz embed code is placed over the API snippets.
* To use Javascript API, only programmers can install according to instructions. If your business does not have its own programmer, hire a frelance programmer to help them.
{% endhint %}

### 1. User attributes

The four default user attributes set up on Subiz are about basic user information, such as: Full name, Email address, Phone number, Address.

Subiz lets you create and generate new attributes about your users, based on criteria that is specific to your business. You can user this data as qualification data to qualify leads and boost sales. You can also use this data to filter and send targeted Automation messages. 

To add a new attribute, you log in [App.subiz.com &gt; SETTING &gt; ACCOUNT &gt; User Attributes &gt; Select New Attribute](https://app.subiz.com/settings/user-attributes#)

![Create new attribute on Subiz](../../../.gitbook/assets/123.png)

### 2. API updates user attributes on Subiz

You can use the Javascript Subiz API to update automatically your default user attributes on Subiz or update your own custom user attributes.

Here is an example of Javascript API to update full-name attribute:

```text
<script>
subiz('updateUserAttributes', [{ key: 'fullname',   text : 'David’ }]);
</script>
```

Things must remember:

* Key is attribute key
* Data type: Text, Number, Boolean, List, Date Time. \([See detailed notes](https://help-en.subiz.com/optimise-the-use-of-subiz/managing-data/users-attributes)\)

 Here are just some examples of what our JavaScript API lets you do:

#### 2.1. Update a default attribute

{% tabs %}
{% tab title="Full name attribute" %}
`<script>  
subiz('updateUserAttributes', [{ key: 'fullname',   text : 'David’ }]);  
</script>`
{% endtab %}

{% tab title="Phone number attribute" %}
`<script>  
subiz('updateUserAttributes', [{ key: ’phones’,   text : '09123456789', '0987654321' }]);  
</script>`
{% endtab %}

{% tab title="Email address attribute" %}
`<script>  
subiz('updateUserAttributes', [{ key: 'emails’,   text :'example1@domain.com, example2@domain.com' }]);  
</script>`
{% endtab %}
{% endtabs %}

#### 2.2. Update simultaneously multiple default attributes

{% tabs %}
{% tab title="Update simultaneously multiple default attributes" %}
```text
<script>
subiz('updateUserAttributes', [{ key:'fullname',   text : 'David' },{ key:'phones',   text : '09123456789' } ]);
</script>
```
{% endtab %}
{% endtabs %}

#### 2.3. Update new custom attribute\(s\)

Below are two examples of such custom attributes as Language and Customer:

{% tabs %}
{% tab title="Language attribue" %}
`<script>  
subiz('updateUserAttributes', [{ key:'ngon_ngu',   list : [‘Vietnamese’, ‘English’] } ]);  
</script>`
{% endtab %}

{% tab title="Customer attribute" %}
`<script>  
subiz('updateUserAttributes', [{ key:'khach_hang',   boolean : true }]);  
</script>`
{% endtab %}
{% endtabs %}

### 3. API deletes all user data

API allows you to delete user data on Subiz. Deleted user data will be clear on client and on Subiz so that that Subiz agent cann't see these clients.

{% tabs %}
{% tab title="API deletes all user data" %}
`<script>  
subiz('forgetMe');  
</script>`
{% endtab %}
{% endtabs %}

### 4. API synchronizes user data from Subiz to website

API allows you to synchronizes user data from Subiz to website. 

{% tabs %}
{% tab title=" API synchronizes user data from Subiz to website" %}
`<script>  
subiz('getUserAttributes', (attributes) => {console.log('user attributes', attributes)});  
</script>`
{% endtab %}
{% endtabs %}

> Do you need help? Just click on [Subiz.com](https://subiz.com/en) and chat with us!

