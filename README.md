# TrueVault Polaris CMP custom template for Google Tag Manager

## Setting Up Consent Management in Google Tag Manager

If your business uses Google Tag Manager on its website, it takes just a few minutes to integrate TrueVault’s consent management platform (CMP) and configure the consent requirements for your tags.

### Step 1: Add TrueVault Polaris CMP to Tag Manager

To add the TrueVault Polaris CMP to your site, follow these steps in Tag Manager.

1. In the left navigation bar, select Templates
2. In the Tag Templates window, click Search Gallery
3. A window will pop up on the right side. Search for TrueVault Polaris CMP
4. Click Add to Workspace
5. In the left navigation bar, select Tags
6. Click New, then Tag Configuration
7. In the right window, Search for TrueVault Polaris CMP
8. Here you’ll see the default settings for the CMP, in which only “Functional Storage” is selected. This means that tags marked as “functional storage” will load on their own without any consent required. We recommend leaving these defaults unchanged.
9. Next, click Triggering
10. On the Choose a Trigger screen, select Consent Initialization - All Pages
11. Click Save

### Step 2: Categorize Your Tags

Now that you’ve added the Polaris CMP, you can assign a consent category to each tag your site uses. 

1. Select Tags from the left navigation bar
2. Click on the tag you want to configure
3. Click Tag Configuration, then Advanced Settings
4. Expand the Consent Settings menu
5. Select Require additional consent for tag to fire, then Add required consent
6. Choose which consent category applies to that particular tag
7. Publish the container when you are ready for the changes to go live on your website

*Note: Some Google products, such as Google Ads, already have built-in consent settings. In these cases, you will not need to manually categorize the tag.*

### Step 3 Alternative: Make Bulk Edits with Consent Overview

Google Tag Manager has introduced a feature called Consent Overview that allows users to quickly check the consent settings of all their tags at once, as well as make bulk edits to consent settings so that you don’t have to click into each tag individually. For sites with dozens of tags operating, using this feature can save a lot of time.

**How to Enable Consent Overview**

1. Select the **Admin tab** from the top navigation
2. Click **Container Settings**
3. Select **Enable Consent Overview**
4. Save your settings

With Consent Overview enabled, you can return to **Workspace→Tags**. Along the top of the Tags menu, you should now see a shield icon. Click this shield icon to access Consent Overview.

**How to Make Bulk Edits to Consent Settings**

1. In the list of tags, check the box to the left of each tag you would like to edit
2. When one or more boxes are checked the **Edit Consent Settings** icon (a shield with a cog) will appear; click this icon
3. Under **Additional consent settings**, select the appropriate consent setting
4. Click **Save**
5. Publish the container when you are ready for the changes to go live on your website

### Not Sure Which Category to Choose?

If you’re not sure which consent category to assign to a particular tag, just remember to keep in mind your website visitors’ expectations. Cookie-consent rules are meant to give consumers meaningful control over online tracking technology, so do your best to align the consent categories with what a website visitor would reasonably expect. E.g., if a consumer wants to turn off advertising cookies in the consent pop-up, it only works if all of your advertising tags are in the right category.

Also bear in mind that tags that as Security or Functionality will be considered “essential,” meaning that they will not require consent in order to function. Before assigning a tag to one of these categories, ask yourself: Is it strictly necessary for the secure functioning of the site, or is it something that consumers should have some control over?

Here’s a brief explanation of each category that roughly corresponds to what website visitors will see in your consent pop-up:

**Analytics** -  Tags that tell you how visitors use your sites and apps.

**Personalization** -  Used to enhance functionality and personalize content for visitors. 

**Advertising** -  These are used to customize marketing content that consumers see on websites, apps and social media, and to measure their interactions with that content. 

**Security** - Used to prevent cyberattacks, detect fraud, and other security-related functions.

**Functionality** - Tags that handle user logins, site errors, payment processing, etc. These are tags that are necessary for your site to function.