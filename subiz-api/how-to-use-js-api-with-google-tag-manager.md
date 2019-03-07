---
description: >-
  There are some example we would like to show the way how to associate Google
  Tag Manager and Subiz Javascript to control the Subiz widget.
---

# How to use Js API with Google Tag Manager

### The Subiz widget opens when visitors scroll down

In this example, the scenario is when the visitor access a landing pages, after they scrolls down to 60% of the screen when, the widget chat will show up. 

**Step 1:** Login your Google Tag Manager account, select the website and your workspace. Next, create a new tag with the tag type "Custom HTML" and use the JavaScript API Open Subiz Widget. 

![Create a new tag with Custom HTML and use the JavaScript API Open Subiz Widget](../.gitbook/assets/1%20%283%29.png)

**Step 2:** You create a Trigger for the tag as above.

Click create a new Trigger, select the Scroll Depth. On the screen, select "Vertical Scroll Depths" \(in case the mouse scrolls vertically, if you want to scroll horizontally, select "Horizontal Scroll Depths"\).

In the "Percentages" box, select the percentage that you want when the visitor scrolls to that interval, the Subiz widget will open. In this example, I choose 60%.

In the "This trigger fires on" section, you can select All page - This means it works on every page; or Some Pages - specify a specific page.   
I choose "Some Pages" and under I will choose the url containing the word "LandingPage". That means, it only works on URLs that contain "landingPage". 

![](../.gitbook/assets/2%20%285%29.png)

  
Then you **SAVE&gt; SUBMIT&gt; PUBLISH**. Use Previews to check if necessary. The Subiz widget will open automatically when the customer scrolls 60% of the screen.

In this example, you can replace the Scroll Depth trigger by: 

* Timer Clock: For example, with the script, visitors on page 3 seconds, the chat widget opens or after the guest clicks the form Register on the web for 2 seconds, the chat widget opens …
* Events Click on an element: For example, with the script when the visitor clicks the register button, the chat window opens; Customers click the purchase button or request support …
* Events Submit form Error / Success: To appear at the right time when customers need or provide VIP services for important customers.

### How to use Google Tag Manager to customize the Widget 

In this example, I will use Google Tag Manager to hide the Subiz chat button when I access via mobile.

**Step 1: Use Google Tag Manager to identify the device as Mobile.**  
Login Google Tag, go to the Variable section and create new Variable with the type of Custom Javascript. Use the function below to identify Mobile devices. 

```coffeescript
function() {
 if( /Android|webOS|iPhone|iPad|iPod|BlackBerry|IEMobile|Opera Mini/i.test(navigator.userAgent) ) 
 {
  return 'true';
 } 
 else 
 {
  return 'false';
 }
}
```

![Create new Variable  identify Mobile devices. ](../.gitbook/assets/3%20%283%29.png)

**Step 2:** Create Tag to call Subiz API Javascript to change CSS.Create a new tag of type Custom HTML and enter the following code to hide the Subiz widget on mobile: 

```c
<script type="text/javascript">
    window.subiz('changeCss', '.widget_mobile .button-chat {display: none;}')
</script>
```

![](../.gitbook/assets/5%20%283%29.png)

  
**Step 3:** Create a trigger for the tag as below: At the trigger page, create a new trigger with the Page View type. Use Variables "is Mobile" to identify Page View with Mobile. You set it as below: 

![Use Variables &quot;is Mobile&quot; to set up triggers.](../.gitbook/assets/4%20%283%29.png)

Now you can **SAVE&gt; SUBMIT&gt; PUBLISH** on the website. Use the Preview function to check the how it work.

Through this example, you can replace your own hidden creation with other buttons to be more attractive on mobile devices. Or you can set up every day, Subiz widget has a different appearance.



