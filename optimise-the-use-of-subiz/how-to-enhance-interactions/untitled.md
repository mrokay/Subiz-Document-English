# Automation setting

With Automation, now you can automate interaction with your customers, attract visitors’ attention and pursue your customers through multiple channels. You no longer need to rely much on the availability of agents.

To create a new Automation, go to the Create New Automation section and perform the following steps:

### Enter a Name and Description for Automation

You can create Automation with one or more concurrent conditions.

![Create a new automation](../../.gitbook/assets/1%20%282%29.png)

### Select the condition for Automation

Select the condition to determine which Automation will target. To fill in the conditions, at first select the type of condition:

![Example: Conditional selection is the URL of the page](../../.gitbook/assets/dk-automation.png)

Then you enter the comparison and the value for that condition to create a complete condition.

![Select the comparison and value for the Automation condition](../../.gitbook/assets/dk-automation1.png)

Click **Add condition** when you want to add another condition. Select "Customer meets all conditions" or "Customer meets one of the conditions" to establish the relationship between the conditions: And/or.

![Add conditions for Automation](../../.gitbook/assets/them-dk-automation.png)

You should **refer to the list of conditions**, with instructions on how to use it and the following specific examples:

| **CONDITION** | **USAGE** | **EXAMPLES** |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **User** | ​ | ​ |
| Name | Execute automation with specific user’s name | Send a special greeting or promotional email to the user named DavidCondition: Name – contains – David |
| Email | Execute automation with specific user’s email | Send a special greeting or email to all users whose email address contains subiz.comCondition: Email – Contains – subiz.com |
| Phone | Execute automation with specific user’s phone number | Send greetings or emails to users whose phone number is unknownSend automatic SMS to users whose phone number is known \(only applicable when SMS channel is integrated into Subiz\) |
| Country | Execute automation based on user’s country nameUse the country name in English, only capital first letter of the word. Example: Vietnam, United States[See detail in the list of country code](https://countrycode.org/)​ | Send greetings to customers in Vietnam with automation message in Vietnamese.Condition: Country – is – Vietnam |
| Country Code | Execute automation based on user’s country codeLook up the country codes in [ISO Code](https://en.wikipedia.org/wiki/ISO_3166-2) \(2 characters\), Example: Viet Nam = VN, Australia = AU, China = CN… | Send greetings to customers in Vietnam with automation message in Vietnamese.Condition: Country code – is – VN |
| City | Execute automation based on user’s cityUse the city name in English, only capital first letter of the word. For example, Hanoi, Ho Chi Minh City, New York, Hong Kong…See list [city code of each country](https://countrycode.org/) \(Click into each country to look up city name\) | Send greetings to customers in Hanoi.Condition: City – is – Hanoi |
| **Event data** | ​ | ​ |
| Page title | Each page typically focuses on a specific topic, you can set up an automation with each page to support customers at right time | Send greetings to customers who are viewing pages about “camera”.Condition: Page Title – Contains-Camera |
| Page URL | Execute automation when customers visit a particular page URL | Send a message to the customers who are viewing the pricing pageCondition: Page URL – is – https://subiz.com/en/pricing.html |

### Automation run in which channels?

You can select channels to run Automation. Each channel will have corresponding actions.![](https://docv4.subiz.com/wp-content/uploads/2018/03/Ch%E1%BB%8Dn-k%C3%AAnh.png)

### The Action set for Automation

{% hint style="info" %}
Each Automation will take only one action.
{% endhint %}

{% tabs %}
{% tab title="Action on Subiz Chat" %}
With the Subiz Chat channel, you can take one of two actions:

* **Send message to user:** You can send an auto message as soon as customers enter your website, or send a specific message to specific customers.
* **Ask for email address**: It can be used when you are not online or cannot answer immediately. Customers will enter their email address so that you can contact later.

![Select the action to send the message to the customer](https://docv4.subiz.com/wp-content/uploads/2018/03/action-Subiz-chat.png)

Users will see auto messages/emails as a messages/ emails sent from that Agent.![](https://docv4.subiz.com/wp-content/uploads/2018/03/Content.png)
{% endtab %}

{% tab title="Action on Subiz Email" %}
With Email channel, you can take action **Send email to users**. 

{% hint style="info" %}
This action only can be taken with users whom you have already got their email.
{% endhint %}

Choose action **Send email to user** on Email channel
{% endtab %}
{% endtabs %}



How are messages/emails sent automatically?

You can choose an agent to send messages and emails.

![](https://docv4.subiz.com/wp-content/uploads/2018/03/agent.png)



### AUTOMATION SETTING {#automation-setting}

**Table of content**

* ​[Create new automation](https://docv4.subiz.com/automation-setting/#newautomation)​
* ​[Edit/ Delete automation](https://docv4.subiz.com/automation-setting/#editautomation)​
* ​[Active/ Inactive automation](https://docv4.subiz.com/automation-setting/#activeautomation)​

To set up Automation, go to **Setting&gt; Account&gt; Automation**.

#### 1. Create new automation {#1-create-new-automation}

Click **New Automation** to create new automation.![](https://docv4.subiz.com/wp-content/uploads/2018/03/new-automation.png)

With Standard package, you can activate up to 5 Automations. You just need to upgrade your account to increase the number of Automation.

Follow below steps to set up automation:

* **Enter Automation Name and Description**

Automation name and description help you identify and distinguish Automations.

For example:

Name Automation: Welcome to website

Description: Automatically send a message to visitors who view more than or equal to 1 page![](https://docv4.subiz.com/wp-content/uploads/2018/03/name-automation.png)

* **Enter condition**

Select condition to determine the target of Automation. You can select one or multiple conditions simultaneously.![](https://docv4.subiz.com/wp-content/uploads/2018/03/condition-1.png)

To enter conditions, firstly you select the type of condition:![](https://docv4.subiz.com/wp-content/uploads/2018/03/select-condition.png)

Then you enter the comparison and the value to create a complete condition.

For example:![](https://docv4.subiz.com/wp-content/uploads/2018/03/select-condition-2.png)

Click **Add more condition** if you want to add another condition. Select “**Audience who match all these conditions**” or “**Audience who match any of these conditions**” to set up the relationship between the conditions: **And / Or**.

For example:![](https://docv4.subiz.com/wp-content/uploads/2018/03/select-condition-3.png)

See more **List of automation condition**

* **Select Channel**

Then you select the channel in which Automation will run. In each channel, you can choose different actions.![](https://docv4.subiz.com/wp-content/uploads/2018/03/Ch%E1%BB%8Dn-k%C3%AAnh.png)

* **Select Action**

– On Subiz Chat channel, you can select action **Send message to user** or **Ask for email address**.

+ **Send message to user**![](https://docv4.subiz.com/wp-content/uploads/2018/03/send-message.png)

Select Agent to send message.![](https://docv4.subiz.com/wp-content/uploads/2018/03/agent.png)

Enter your message.![](https://docv4.subiz.com/wp-content/uploads/2018/03/Message.png)

Subiz supports text format tool for you to customize the message more vividly \(bold/italic / insert link / send image …\).

**+ Ask for email address**

Select the action Ask for email address and select Agent to send message.![](https://docv4.subiz.com/wp-content/uploads/2018/03/ask-info.png)

The message will appear as below:![](https://docv4.subiz.com/wp-content/uploads/2018/03/form-h%E1%BB%8Fi-th%C3%B4ng-tin.png)

– In Email channel, you can select action **Send email to user.**![](https://docv4.subiz.com/wp-content/uploads/2018/03/G%E1%BB%ADi-email.png)

Select Agent, enter email subject and email content:![](https://docv4.subiz.com/wp-content/uploads/2018/03/Nh%E1%BA%ADp-email-1.png)

Preview your email:![](https://docv4.subiz.com/wp-content/uploads/2018/03/Xem-tr%C6%B0%E1%BB%9Bc-email.png)

* **Save Automation**

After all, click **Create** to finish.

#### 2. Edit/ Delete Automation {#2-edit-delete-automation}

To delete or edit an Automation, go to Automation List and select the Delete / Edit button.![](https://docv4.subiz.com/wp-content/uploads/2018/03/edit-and-delete.png)

#### 3. Active/ Inactive Automation {#3-active-inactive-automation}

You can create multiple automations, but only active automations can work. You can adjust Active / Inactive status for each Automation. This allows you to use Automation flexibly, according to your demand and your package

Select Automation &gt; select edit icon&gt; Enable / Disable Automation status.![](https://docv4.subiz.com/wp-content/uploads/2018/03/status-1.png)

​

### LIST OF AUTOMATION CONDITIONS {#list-of-automation-conditions}



[PreviousUsing advanced Subiz](https://subiz.gitbook.io/subiz-document-english/optimise-the-use-of-subiz)[NextUntitled](https://subiz.gitbook.io/subiz-document-english/optimise-the-use-of-subiz/how-to-enhance-interactions/untitled)Was this page helpful?Let us know how we did[  
](https://subiz.gitbook.io/subiz-document-english/~/edit/primary/optimise-the-use-of-subiz/how-to-enhance-interactions)

