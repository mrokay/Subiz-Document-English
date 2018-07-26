# Rule setting

**Rules are used to automatically assign incoming messages to specific agent\(s\) or team.** You need to set up rules right after creating account so that you can get conversations from your customers.

To set up a new rule, [log into your account](https://app.subiz.com/login) and go to [**Setting&gt; Account&gt; Message&gt; Rule**](https://app.subiz.com/settings/rule-setting) **&gt;** Select **New rule.**

![Add a new Rule](https://docv4.subiz.com/wp-content/uploads/2018/03/New-rule-1.png)

Then start to set up a new rule.

### **Step 1: Enter rule name and description**

* **Rule Name:** Enter rule name so that you can easily manage in the rule list
* **Description**: Describe the condition and purpose of the rule

![Import the file and description of the rule](../../../.gitbook/assets/image%20%2816%29.png)

### **Step 2: Select conditions for the rule**

* Click **Add more condition** to combine multiple conditions in a rule.
* Select **And / Or** to determine the relationship between the conditions.

![ Select conditions for the rule](https://docv4.subiz.com/wp-content/uploads/2018/03/condition.png)

You can set one or more conditions based on **List of rule condition**.

| **CONDITION** | **USAGE** | **EXAMPLE** |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Any condition | By selecting this condition, **all conversations** will always be assigned to agents set up in the rule. | ​ |
| **Date Time** | ​ | ​ |
| Hour of day | When you want to assign conversations to agents based on time \(hour\) of the day. Hour of day from 0 to 23. | Day shift for Agent A - Night shift for Agent B. |
| Day of week | When you want to assign conversations to agents based on days in week.Note: days of week are recorded as numbers from 2-8. Monday = 2, Tuesday = 3…, Sunday = 8. | Monday, Wednesday and Friday for Agent A -  Tuesday and Thursday for Agent B. First 3 days of week for Agent C - Last 3 days of week for Agent D. |
| **Conversation** | ​ | ​ |
| Page URL | Each URL typically focuses on a specific product or service, Subiz can identify which URL customers are viewing and assign the conversation to each Agent. | Customers are viewing product 1, assign to sale 1. Customers are viewing product 2, assign to sale 2. Customers are viewing warranty page, assign the conversation to agent group Customer Care. Customers are viewing pricing page, assign the conversation to agent group Sales. |
| Page title | Purpose of page title are almost the same as page URL. You can use it to assign conversations from specific pages to suitable agents. | Page title contains keyword “camera”, assign to Agent A. Page title contains keyword “laptop”, assign to Agent B. |
| Message Content | When the first message of customer contains a certain content, you can assign the conversation to suitable agents. | Message content contains “price”, assign to Agent A. |
| Browser language | Look up codes of browser language in [ISO Language Code](http://www.lingoes.net/en/translator/langcode.htm), for example, vi-VN, en-US. Assign the conversation to agents who can use the language that customers use in their browser. | Customers use English as their browser language, assign conversation to Agents who major in English. Customers use French as their browser language, assign conversation to Agents who major in French. |
| **User** | ​ | ​ |
| Name | Identify name of customers and assign conversation to a specific agent. | Assign conversations of customers whose name contain “Mr” to Agent A. |
| Email | Identify email of customers and assign conversation to a specific agent. | Assign conversation of customers whose email address is unknown \(email is empty\) to Agent B. |
| Phone | Identify phone number of customers and assign conversation to a specific agent. Phone numbers are a set of numbers, not contain special characters | Assign conversations of customers whose phone number begin with +84 to Agent C |

{% hint style="info" %}
A rule works only when the conversation and the user who starts it meet the conditions \(a conversation is only assigned according to one rule\).
{% endhint %}

### **Step 3: Set up how to assign conversations to agents**

Select Agent\(s\) who will receive and take over conversations that meet the conditions set above.

![Assign conversations to agents](../../../.gitbook/assets/tao-rule-moi.png)

**1. Assign to Agent\(s\) or a group:**

Any agent in the assigned group can participate in conversations simultaneously.

Select one of the methods below:

* _**Assign to all available agents:**_ assign conversations to all active agents
* _**Assign to specific agent\(s\):**_ assign conversations to one or several agents. Click \(+\), \(-\) to select/deselect Agent. As the example below, 2 Agent has been selected.

![Select Agent to assign the conversation](https://docv4.subiz.com/wp-content/uploads/2018/03/rule-example-1.png)

* _**Assign to group\(s\):**_ assign conversations to a group which is created before. As the example below, conversations are assigned to group Sale.

![Select Agent&apos;s group to assign the conversation](https://docv4.subiz.com/wp-content/uploads/2018/03/rule-example-2.png)

* _**Assign to agent\(s\) who has last activity with user:**_ assign conversation to agent\(s\) who have the latest conversation with user

**2. Round robin conversation assignment**

Conversations will be assigned one by one to selected agents.

For example, you select 3 agents in the agent list, when there are 6 conversations, each Agent will receive 2 conversations in turn.

![Round robin conversation assignment](https://docv4.subiz.com/wp-content/uploads/2018/03/rule-example-3.png)



