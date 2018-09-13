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
* Data type: Text, Number, Boolean, List, Date Time. \(See detailed notes\)

 Here are just some examples of what our JavaScript API lets you do:

#### 2.1. Update a default attribute

| Full name atrribute |  |
| :--- | :--- |
|  |  |

#### 2.2. Updates simultaneously multiple default attriubutes 



#### 2.3. Update new custom attribute\(s\)



### 3. API deletes all user data





### 4. API synchronizes user data from Subiz to website

