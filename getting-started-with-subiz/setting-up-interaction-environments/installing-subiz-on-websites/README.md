# Installing Subiz on Websites

### What is Subiz Chat?

Subiz Chat is a channel for you to interact with visitors on your website.  After integrating Subiz widget into your web, you can interact, follow and convert visitors into customers.

### How to integrate Subiz on your website

To integrate Subiz widget into your website, follow these three steps:

**Step 1: Get Subiz’s embed code**

To integrate Subiz chat widget into website, you just need to copy the embed code \(mustn’t change any part of it\) and paste into pages you want to place the chat widget.

To get embed code, follow steps below:

1. Sign in to [app.subiz.com](https://app.subiz.com/)
2. Click **Settings &gt; Account &gt; Installation**

At Subiz Chat Widget &gt; Subiz Embed Code, click Copy code to copy the embed code quickly.

![](https://docv4.subiz.com/wp-content/uploads/2018/03/copy-code.png)

{% hint style="info" %}
Every single account has different embed code so when you change the account you have to re-install embed code.
{% endhint %}

**Step 2: Place embed code into website**

Subiz supports almost all platforms so the installation is very simple. Copy the code and Embed into every pages you want to place the chat widget. Subiz code must be pasted before &lt;/body**&gt;** tag.

**Step 3: Check Subiz’s widget on website**

After finishing integration, come back to your website and see if the chat widget displays at the bottom of the right corner or not.

If you still don’t see the chat widget, you can take some more steps to check it in Dashboard:

1. Sign in **app.subiz.com**
2. Click into **Settings &gt; Account &gt;** **Installation**
3. Paste your website’s URL and click **Check**

If not successfully, check the code again and contact Subiz support center.

![](https://docv4.subiz.com/wp-content/uploads/2018/03/check-code.png)

### Integrating Subiz on other Website platform

If your website is built on other platforms, find installation guide in the list below and enable the integration in your website’s control panel.

{% tabs %}
{% tab title="WordPress" %}
1. Open **WordPress Admin Panel** &gt; **Appearance** &gt; **Editor**
2. Go to **footer.php** file in the right column &gt; Open it
3. Paste Subiz widget code into **footer.php** \(Right before &lt;/body&gt; tag\)
{% endtab %}

{% tab title="Shopify" %}
1. From your Shopify, go to **Online Store** &gt; **Themes**.
2. Find the theme you want to edit and click the **Actions** button for the theme. Select **Edit code**
3. Find theme **.liquid** file on the side menu. Embed Subiz widget code before the &lt;/body&gt; tag. Click **Save**.
{% endtab %}

{% tab title="Wix" %}
1. From your Dashboard, go to Manage & Edit Site
2. Click **Edit Site** &gt; **Add button** &gt; **More** &gt; **HTML iframe**. Dragging the newly added **iframe** to the **footer** \(can adjust the position of the iframe\)
3. Click **Add code** and paste **embed code**. Click **Save**
{% endtab %}

{% tab title="Magento" %}
To embed Subiz code on your Magento, go to your Magento them files and check if the file indicated exists or not, so please refer two options below:

**Option 1**

1. Look for your Magento tempale in app/design/frontend/{template}/page/html/head.phtml. If this file doesn’t exist, then you will need to check if the app/design/frontend/{template}/default/page/html/head.phtml file exists.
2. Paste Subiz embed code right before the &lt;/head&gt; section of the file.

**Option 2**

You only need to do this option if the template files described in the option 1 don’t exist. This situation due to some custom Magento templates might not have a head.phtml file and the template would be using the base template file.

1. Copy the app/design/frontend/default/page/html/head.phtml file from your default base template to your custom template folder at app/design/frontend/{template}/page/html/head.phtml.
2. Open the file and paste Subiz chat code before the &lt;/head&gt;
{% endtab %}

{% tab title="Joomla" %}
1. Open Joomla Admin &gt; Template Manager &gt; Choose your **Template and** Filter by **site**
2. Choose your templte &gt; Open **Index.php** file
3. Paste Subiz embed code right before &lt;/body&gt; tag &gt; Finish
{% endtab %}
{% endtabs %}

If your website platform is not listed above, please contact us for better assistance.

