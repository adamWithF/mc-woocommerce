# MailChimp for Woocommerce Integration

In this article, you’ll learn how to connect MailChimp for WooCommerce.

#Before You Start#

**Here are some things to know before you begin this process.**

- We recommend you use this plugin in a staging environment before installing on production servers.
- This process requires an API Key from your MailChimp account. If you aren’t sure how to generate a MailChimp API Key, read [About API Keys.](http://kb.mailchimp.com/integrations/api-integrations/about-api-keys)
- This plugin supports MailChimp’s [Abandoned Cart Automation](http://kb.mailchimp.com/automation/create-an-abandoned-cart-workflow) feature.
- WooCommerce customers who haven't signed up for marketing emails will appear in the Transactional portion of your list, and cannot be exported. See [View or Export a List.](http://kb.mailchimp.com/lists/managing-subscribers/view-or-export-a-list)
- To switch lists or accounts, you must deactivate and delete the plugin, then re-install it.
- In e-commerce reports and on subscriber profile pages, product variants will display as the parent product. 


#Task Roadmap#
**Here’s a brief overview of this multi-step process.**

- Install the plugin on your WordPress Admin site.
- Connect the plugin with your MailChimp API Key, and configure your list settings to complete the data sync process.

#Install the Plugin#
**To install the plugin, follow these steps.**

1) Log in to your WordPress admin panel. 
2) In the left navigation panel, click **Plugins**, and choose **Add New**.

![Add new] (https://cloud.githubusercontent.com/assets/6547700/18677991/a7622bcc-7f28-11e6-8e8c-9bbdfa9861c7.png)

3) Click **Upload Plugin**.

![Upload] (https://cloud.githubusercontent.com/assets/6547700/18677997/a76dab82-7f28-11e6-98e4-4309739cd840.png)

4) Click **Choose File** to select the ZIP file for the plugin, then click **Install Now**.

![Install Now](https://cloud.githubusercontent.com/assets/6547700/18677988/a760949c-7f28-11e6-9e13-13c23d044ad4.png)

5) Click **Activate Plugin**.

![Activate plugin](https://cloud.githubusercontent.com/assets/6547700/18677990/a760d7c2-7f28-11e6-8741-12c1efa7a991.png)

After you activate the plugin, you’ll be taken to the **Settings** page, where you will add your API key and configure your list settings.

#Configure and Sync#
**To configure your MailChimp settings for WooCommerce customers and sync them to MailChimp, follow these steps.**

1) On the **Connect** tab, paste your MailChimp API key into the field, choose whether or not you want to send debugging logs to MailChimp, and click **Save all changes**. 

 ![API key] (https://cloud.githubusercontent.com/assets/19805049/18877771/3fca90e8-849c-11e6-9e3a-161a7b3936dd.png)

2) Navigate to the **Store Settings** tab.

![Store Settings](https://cloud.githubusercontent.com/assets/6547700/18677998/a76e5640-7f28-11e6-9fd3-d66949fa1413.png)

3) Enter the contact and location details for your WooCommerce Store, and click **Save all changes**.

![Save all changes] (https://cloud.githubusercontent.com/assets/6547700/18677996/a76d126c-7f28-11e6-9150-4b289d20f057.png)

4) Navigate to the **List Settings** tab. 

![List Settings tab] (https://cloud.githubusercontent.com/assets/19805049/18878446/961221d0-849e-11e6-99bb-175c22bf921e.png)

5) Choose the list you want to sync, decide whether or not you want to auto-subscribe existing customers, set the subscribe message you want customers to see at checkout, and click **Save all changes**.

![Save all changes](https://cloud.githubusercontent.com/assets/19805049/18877772/3fd24162-849c-11e6-8442-79ec4550b8ac.png)

All set! When you click **Save all changes**, we’ll start syncing your WooCommerce customers to MailChimp. To view progress, check the **Sync Status** tab. 

If you have no lists in your MailChimp account, you will be given the option to create a new list on the **List Defaults** tab. To create a new list, set your list defaults, and click **Save all Changes** when you’re done. We’ll create a MailChimp list for you, and begin the data sync.

![List Defaults tab](https://cloud.githubusercontent.com/assets/19805049/18956260/cffd3926-8628-11e6-9c68-9fe3c964c75c.png)

#Next Steps#
After you connect, you can do a lot with the the data you collect, like build segments, send Automation workflows, track purchases, and view results.

Find out everything MailChimp has to offer in our article, [How to Use MailChimp for E-Commerce](http://kb.mailchimp.com/integrations/e-commerce/how-to-use-mailchimp-for-e-commerce).

#Deactivate or Delete the Plugin#
When you deactivate MailChimp for WooCommerce, it stops the sync but doesn’t remove the plugin. You can always re-activate the sync, which will backfill data at a later point in time.
To deactivate MailChimp for WooCommerce, follow these steps.

1) Log in to your WordPress admin panel. 

2) In the left navigation panel, click **Plugins**, and choose **Installed Plugins**.

![Installed Plugins](https://cloud.githubusercontent.com/assets/6547700/18677993/a76542ee-7f28-11e6-99dd-cfd6c1f5c24a.png)

3) Click the box next to the MailChimp for WooCommerce plugin, and click **Deactivate**.	

![Deactivate](https://cloud.githubusercontent.com/assets/6547700/18677992/a762b844-7f28-11e6-9679-8d6c6a1d731d.png)

After you deactivate the plugin, you will have the option to **Delete** it. If you delete the plugin, you will retain customers’ email addresses in your list, but remove all associated e-commerce data. 
