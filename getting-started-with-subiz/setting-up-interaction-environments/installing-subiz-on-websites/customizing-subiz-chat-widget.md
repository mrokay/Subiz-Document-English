# Creative on Subiz Chat widget

### **Customizing CSS for Subiz Chat widget**

Besides using the chat widget settings on the website that Subiz has provided. You can easily customize other components on the chat widget by using CSS code.

CSS stands for “Cascading Style Sheet”. It describes how HTML elements are to be displayed on screen, paper, or in other media. With using CSS, you can customize every single elements in chat widget to make it more attractive or unique.

#### How to add customized CSS?

Firstly, log in app.subiz.com, come to **Setting &gt; Account &gt; Message &gt; Widget &gt; Customize CSS**![](https://docv4.subiz.com/wp-content/uploads/2018/05/Customize-CSS.png)

Next, **Copy and Paste** the corresponding CSS to customize the component you want, then return to the chat widget settings screen and save the changes.

Here are some examples of possible customizations and instructions on how to achieve them:

#### Changing the chat widget width

| 123 | .widget\_mini .widget\_body{ width:600px;} |
| --- |


Change value **600**px to decide the width of chat widget.![](https://docv4.subiz.com/wp-content/uploads/2018/05/css-width.png)

### ​ {#undefined}

#### Changing the chat widget height

| 1234 | .widget\_mini .widget\_body{ height: 800px !important; max-height: 900px !important;} |
| --- |


Change value **800**px to decide the height of chat widget.![](https://docv4.subiz.com/wp-content/uploads/2018/05/css-height.png)

#### Customizing font size

| 123 | .message-content{ font-size:20px;} |
| --- |


Change value **20**px to decide the font size of chat widget.![](https://docv4.subiz.com/wp-content/uploads/2018/05/css-font-size-en.png)

### ​ {#undefined-1}

#### Customizing colors of the whole chat widget

When you choose to customize color of the whole chat widget, you would not be able to custom the colors of each component of header, message box, new conversation

You can customize your widget with solid color or gradient colors:

* Solid color

| 12 | .color-theme-default{background-color:\#000000;} |
| --- |


You can change value **\#00000** to suit your website

* Color gradient

| 12 | .color-theme-default{background-image: linear-gradient\(to right top, \#056587, \#0085a3, \#00a6ac, \#00c59f, \#0be17f\);} |
| --- |


You can change value **\#056587, \#0085a3, \#00a6ac, \#00c59f, \#0be17f** to suit your website![](https://docv4.subiz.com/wp-content/uploads/2018/05/css-total-colors.png)

#### Customize the color of each component on the chat widget

**1. Customize the color of the chat widget’s header**

You can customize your widget with solid color or gradient colors:

* Solid color

| 1 | .widget-header {background-color:\#00000;} |
| --- |


You can change value **\#00000** to suit your website

* Color gradient

| 12 | .widget-header{background-image: linear-gradient\(to right top, \#056587, \#0085a3, \#00a6ac, \#00c59f, \#0be17f\);} |
| --- |


You can change value **\#056587, \#0085a3, \#00a6ac, \#00c59f, \#0be17f** to suit your website![](https://docv4.subiz.com/wp-content/uploads/2018/05/css-color-header.png)

**2. Customize the color of the chat widget’s message box**

You can customize your widget with solid color or gradient colors:

* Solid color

| 1 | .message-body {background-color:\#00000;} |
| --- |


You can change value **\#00000** to suit your website

* Color gradient

| 12 | .message-body{background-image: linear-gradient\(to right top, \#056587, \#0085a3, \#00a6ac, \#00c59f, \#0be17f\);} |
| --- |


You can change value **\#056587, \#0085a3, \#00a6ac, \#00c59f, \#0be17f** to suit your website![](https://docv4.subiz.com/wp-content/uploads/2018/05/color-message-box.png)

**3. Customize the color of the chat widget’s new conversation**

You can customize your widget with solid color or gradient colors:

* Solid color

| 1 | .add-new-conversation {background-color:\#00000;} |
| --- |


You can change value **\#00000** to suit your website

* Color gradient

| 12 | .add-new-conversation{background-image: linear-gradient\(to right top, \#056587, \#0085a3, \#00a6ac, \#00c59f, \#0be17f\);} |
| --- |


You can change value **\#056587, \#0085a3, \#00a6ac, \#00c59f, \#0be17f** to suit your website![](https://docv4.subiz.com/wp-content/uploads/2018/05/color-new-conversation.png)

### CUSTOMIZE LANGUAGE WITH P.O FILE

Currently, Subiz supports 2 languages: Vietnamese and English. On Subiz widget, you can customize the widget title and team introduction according to each language.

Besides, you can use another language other than these supported languages. Supposed that you want to replace English with German, or you want to edit language in other section of the widget, you can customize the language by .po file following the steps below:

**Step 1:** Download custom language file

Go to [Widget setting](https://app.subiz.com/settings/widget-setting) &gt; **Language**. Select 1 language and click **Customize language**.

![](https://lh5.googleusercontent.com/JU30A_g8_YfpvatmHwuq73h39AedE8WOQco8xtLPg8xDfUIqmY5Kzh5t5_XrZ9VdETmo-ltihq_mLAt5kbtaLNzs_OlZEgKrY6EgBoozEa0v6yp8KeZD5dYL5rij-iiNrNPpIlfe)

Click to download custom language file.

![](https://docv4.subiz.com/wp-content/uploads/2018/04/step1.png)

**Step 2:** Edit .po file

* Go to [https://localise.biz/free/poeditor](https://localise.biz/free/poeditor), upload the .po file you have downloaded.

![](https://docv4.subiz.com/wp-content/uploads/2018/04/drop-a-file.png)

* Translate from source text. For example, in German: Email and Name = Email und Name.

![](https://docv4.subiz.com/wp-content/uploads/2018/04/edit-file.png)

* Click **Save** to finish editing.

![](https://docv4.subiz.com/wp-content/uploads/2018/04/save-button.png)

* Click to save file to your computer.

![](https://docv4.subiz.com/wp-content/uploads/2018/04/save-file.png)

**Step 3:** Upload .po file to Subiz

Go back to [Widget setting](https://app.subiz.com/settings/widget-setting) &gt; Language &gt; Customize language. Upload file, then new language will overlap the chosen language.

![](https://docv4.subiz.com/wp-content/uploads/2018/04/step-3.png)

After uploading successfully, back to widget setting and Save.

![](https://docv4.subiz.com/wp-content/uploads/2018/04/step-3.2.png)

##   {#integrate-email-with-subiz-account}

