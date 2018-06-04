# Distributing conversations



After integrating one or more channels into your Subiz account, all conversations will be automatically assigned to Agent owner \(the account which took registration\).

This is the default rule that Subiz has set up for all account.  
![](https://docv4.subiz.com/wp-content/uploads/2018/04/Rule-Default-1.png)

You can see settings of this default rule.  
![](https://docv4.subiz.com/wp-content/uploads/2018/04/Rule-Default-2.png)

You can edit the conditions and Agents to assign in this default rule to create a new rule, for example, add more agents in assign list… See detailed instructions for [creating a new rule.](https://docv4.subiz.com/create-a-new-rule/) ​

### LIST OF RULE CONDITION {#list-of-rule-condition}

Rule conditions are set to assign conversations to agents. Rules only work when conditions are set up correctly.

| **CONDITION** | **USAGE** | **EXAMPLE** |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Any condition |  By selecting this condition, **all conversations** will always be assigned to agents set up in the rule. | ​ |
| **Date Time** | ​ | ​ |
| Hour of day | When you want to assign conversations to agents based on time \(hour\) of the day.Hour of day from 0 to 23 | Day shift for Agent ANight shift for Agent B |
| Day of week | When you want to assign conversations to agents based on days in week.Note: days of week are recorded as numbers from 2-8. Monday = 2, Tuesday = 3…, Sunday = 8 | Monday, Wednesday and Friday for Agent ATuesday and Thursday for Agent BFirst 3 days of week for Agent CLast 3 days of week for Agent D |
| **Conversation** | ​ | ​ |
| Page URL | Each URL typically focuses on a specific product or service, Subiz can identify which URL customers are viewing and assign the conversation to each Agent. | Customers are viewing product 1, assign to sale 1Customers are viewing product 2, assign to sale 2Customers are viewing warranty page, assign the conversation to agent group Customer Care.Customers are viewing pricing page, assign the conversation to agent group Sales. |
| Page title | Purpose of page title are almost the same as page url. You can use it to assign conversations from specific pages to suitable agents. | Page title contains keyword “camera”, assign to Agent APage title contains keyword “laptop”, assign to Agent B |
| Message Content | When the first message of customer contains a certain content, you can assign the conversation to suitable agents. | Message content contains “price”, assign to Agent A. |
| Browser language | Look up codes of browser language in [ISO Language Code](http://www.lingoes.net/en/translator/langcode.htm), for example, vi-VN, en-US.Assign the conversation to agents who can use the language that customers use in their browser. | Customers use English as their browser language, assign conversation to Agents who major in English.Customers use French as their browser language, assign conversation to Agents who major in French. |
| **User** | ​ | ​ |
| Name | Identify name of customers and assign conversation to a specific agent | Assign conversations of customers whose name contain “Mr” to Agent A |
| Email | Identify email of customers and assign conversation to a specific agent | Assign conversation of customers whose email address is unknown \(email is empty\) to Agent B |
| Phone | Identify phone number of customers and assign conversation to a specific agentPhone numbers are a set of numbers, not contain special characters | Assign conversations of customers whose phone number begin with +84 to Agent C |

### RULE LIBRARY {#rule-library}

Rule library includes 4 rules which are set up for customers to use this feature easily.

To use this library, follow below steps:

* Sign in your account
* Go to **Setting&gt; Account&gt; Message&gt; Rule**
* Select Rule Library
* Edit the rule and select **Create rule**

![](https://docv4.subiz.com/wp-content/uploads/2018/03/rule-library.png)

Currently, Subiz has 4 rules available in the library:

* **Assign all Agents**: assign all conversations to all active Agents \(recommended if you have only 1 Agent\)
* **Return users:** apply for users who have total session greater than 2.
* **English language support:** apply for conversations in which message language is English
* **Pricing:** apply for conversations in which message content contains pricing.

