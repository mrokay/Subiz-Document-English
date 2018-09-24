# Customize chat button

### **1. What is a chat button?**

Chat button is the call-to-action image,  it’s easy to let users know you’re available to help and chat online on Subiz widget. When users click on the chat button, the chat widget will open and start a new conversation.

Every business can actively design their owner chat button images to convey their own messages and give users exciting experience when visiting websites.

### **2. How to customize chat button**

How to set up chat button: Login Subiz via [App.subiz.com&gt; Setting &gt; Account &gt; Widget &gt; Customize chat button](https://app.subiz.com/settings/widget-setting) 

![Customize bubble button](../../../.gitbook/assets/1.-edit.png)

You can select to use a chat button from the button library, or upload your own custom button.

###  **2.1. Use the button library**

You select a button from the library and Save changes to finalize.

![Button library](../../../.gitbook/assets/2.-library.png)

### **2.2. Upload your custom button**

 ****To use your own custom button, you need a button image of your desire. The standard size of the button image is 240 x 120 px, type image is PNG or GIF.

How to upload your own button as followings:

* Select Customize chat button
* Upload custom button
* Browse file or Drag file to upload  &gt; Click "**X**" to exit

![Upload your custom button](../../../.gitbook/assets/3.-upload.png)

{% hint style="info" %}
For some example buttons: [button 1](https://filev4.subiz.com/fiqcgvyhmftekbwjrbmy-button1_en.png) -[ button 2](https://filev4.subiz.com/fiqcgvynxpqgfcrbqgjb-button2_en.png) - [button 3](https://filev4.subiz.com/fiqcgvyqfhiokhwiqmnz-button3_en.png) - [button 4](https://filev4.subiz.com/fiqcgvysbxbykjcrorum-button4_en.png)
{% endhint %}

### **3. CSS code for button customization**

To modify the look of custom button as your desire, copy the CSS styles from below and feel free to use it on your own as well.

<table>
  <thead>
    <tr>
      <th style="text-align:left">Function of CSS</th>
      <th style="text-align:left">Widget type: Standard</th>
      <th style="text-align:left">Widget type: Full height</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">
        <p>Button position
          <br />to the foot of screen</p>
        <p>(Maximum 150px)</p>
      </td>
      <td style="text-align:left"><code>.widget-button<br />{bottom:0px;}</code>
      </td>
      <td style="text-align:left"><code>.widget-button<br />{bottom:0px;}</code>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">
        <p>Message preview position</p>
        <p>(Maximum 110 px)</p>
      </td>
      <td style="text-align:left">
        <p><code>.button-chat .bubble-chat {</code>
        </p>
        <p><code>bottom: 75px;</code>
        </p>
        <p><code>}</code>
        </p>
      </td>
      <td style="text-align:left">
        <p><code>.button-chat .bubble-chat {</code>
        </p>
        <p><code>bottom: 75px;</code>
        </p>
        <p><code>}</code>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">
        <p>Widget position</p>
        <p>(Maximum 140px)</p>
      </td>
      <td style="text-align:left"><code>.widget_mini .widget_body<br />{bottom:0;}</code>
      </td>
      <td style="text-align:left"><code>.widget_full .widget_body<br />{bottom:0;}</code>
      </td>
    </tr>
  </tbody>
</table>> [We are here for your help](https://subiz.com/vi/faqs.html). Let us know if you have questions or concern!

  
  
  




