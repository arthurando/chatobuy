---
description: >-
  Connect Chatobuy to cloud-hosted version of the WhatsApp Business Platform,
  and chat with customers over WhatsApp.
---

# Cloud API

### Overview

Cloud API from Meta is an official API to allow developers and businesses to use WhatsApp Business APIs for sending and receiving messages over WhatsApp without hosting their own servers. Using this, you can manage up to 80 messages (combined both sent and received) per second, including text and media.

This guide will help you connect Chatobuy Channel to Cloud API and initiate the conversation, send notifications, purchase updates, and more.

{% hint style="warning" %}
To follow this guide, ensure you have an active Meta Developer account.
{% endhint %}

### 1) Create a WhatsApp Application

To create a WhatsApp application, first, go to Meta for Developers ([https://developers.facebook.com](https://developers.facebook.com/)), then head over to My Apps.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FuogAQ8SX4RZwrC3ibLHd%2FAccessing%20My%20Apps%20at%20Meta%20for%20Developers.jpg?alt=media&#x26;token=b693b382-24ee-4fa6-9b17-8ccaa707ab4e" alt=""><figcaption><p>Meta for Developers</p></figcaption></figure>

Then, on the apps page, click **Create App**.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FlCfTuNvcnGjiFtCgwP74%2FCreate%20App%20Button%20at%20Meta%20for%20Developers.jpg?alt=media&#x26;token=50fc7026-6df6-42ec-8bef-e900d41a4a75" alt=""><figcaption><p>Create App</p></figcaption></figure>

Then choose other option and click on next.

<figure><img src=".gitbook/assets/image (8) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

This will open a new page, where you've to select your app type.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FcP7l9WquFU0qldUn5fXO%2FSelecting%20WhatsApp%20App%20Type.jpg?alt=media&#x26;token=0c67ac41-6a4d-4571-a44a-14f099310766" alt=""><figcaption><p>Selecting WhatsApp Application Type</p></figcaption></figure>

Select **Business** and then click _Next_. On the next page, you need to enter details for the application. Make sure you add the correct information to avoid suspension or blocking of the app.

The details it needs are,

* Display name - It's the name that'll help recognise your app in the app library.
* App contact email - The email which will Meta use to notify about different events related to your app.
* Business Account - The manager who'll have complete control over the app.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FQqEkVZ2yvKfcvqvBIE6c%2FCloud%20API%20WhatsApp%20App%20details.jpg?alt=media&#x26;token=46f969c2-648c-434a-9351-dc41432ed7b3" alt=""><figcaption><p>App Details Page</p></figcaption></figure>

Enter the details as applied, then select your Business Manager and click _Create app_.

{% hint style="info" %}
An email will be sent to the email address you've added. Make sure you verify the account using the link mentioned in it.
{% endhint %}

### 2) Add Products to Your App

As soon as you click the Create app button, it will redirect you to the following page. Here, you can see different options that you can utilise for your app.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FB6rjHVWNGMs6bpkhwmdb%2FApp%20Screen%20with%20product%20options.jpg?alt=media&#x26;token=4afdabc4-0e42-4c68-a79f-173f3119b2c0" alt=""><figcaption><p>Add Products to Your App Screen</p></figcaption></figure>

Now, on this page, you've to scroll down a bit and click **Set up** for WhatsApp.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2F23xa8QSpbgjixcJKY6Y9%2FSet%20up%20WhatsApp%20application.jpg?alt=media&#x26;token=3ba4a306-f77f-47f8-a259-ed10bd2ab39f" alt=""><figcaption><p>WhatsApp to Set Up as Application</p></figcaption></figure>

A new page will come up asking you to confirm details for WhatsApp Business Platform API. Check your details and then click **Continue**.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FM6TCjeOAuPDdLO8pGmsg%2FContinue%20with%20WhatsApp%20Business%20Api%20Platform.jpg?alt=media&#x26;token=7af32f34-1d50-4410-a239-dda6b21caca4" alt=""><figcaption><p>Continue With WhatsApp Business Platform API</p></figcaption></figure>

As you continue, the Getting started page will open with a temporary access token, test number and more.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FGyjQOp1aHMSd5Y4VzWvw%2FGetting%20started%20page%20with%20temp%20access%20token%20and%20more.jpg?alt=media&#x26;token=5f73a444-9f7b-4ba1-b66c-2c140c1d08f8" alt=""><figcaption></figcaption></figure>

Here, scroll down and click on **Add Phone Number**. This will bring a popup to fill in your business information.

You need to fill,

* Legal Business Name
* Business Email
* Country
* And Business Website

After entering the details, click _Next_, and it will bring fields to create a WhatsApp Business profile.

The details now it needs are,

* WhatsApp Business Profile display name
* Timezone
* Category
* And Business description

Simply enter the details and click _Next_. This time it will bring the field to enter your phone number.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FqBHCVB2e13TUXN4K7UN2%2FAdd%20a%20phone%20number%20to%20WhatsApp.jpg?alt=media&#x26;token=ae29421c-3f81-41d2-9aab-4431589baf9d" alt=""><figcaption><p>Adding Phone Number for WhatsApp</p></figcaption></figure>

First, select your country code, then enter the number. After that, choose how you want to verify it, and then click _Next_.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FAc6XrigrAoe6tgc1qLOD%2FVerifying%20WhatsApp%20Number.jpg?alt=media&#x26;token=9416d190-5f79-4b4d-82fd-f6f54c688365" alt=""><figcaption><p>Verifying the Number</p></figcaption></figure>

Enter the code you've received and then click **Next**. Once the number is verified, you must check whether you're WhatsApp Business profile is created or not. To do that, go to the _Send and receive messages_ section on this page.

Then, select **Test Number** in the _From_ field. Or you can continue with the default.

In the **To** field, enter the number you want to send the test message.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FDaPnucb5iu1InehmsWEO%2FSending%20a%20Test%20Message.jpg?alt=media&#x26;token=983fa6a2-0ee2-4db8-9299-7771457681a2" alt=""><figcaption><p>Sending a Test Message</p></figcaption></figure>

Once both numbers are added, click **Send message**.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FneIiEUwmONoPyp9LNpy9%2FWhatsApp%20Business%20Profile%20Test%20message.jpg?alt=media&#x26;token=57542452-ed3f-4c48-9ddd-39ef6b4981c9" alt=""><figcaption><p>Test Message</p></figcaption></figure>

If the number you've added for the WhatsApp Business Profile is working, the recipient will get the test message like the above. It means, your number is verified and you can continue with the setup.

### 3) WhatsApp Business Profile Verification

Before you further proceed with steps to create a Chatobuy Channel connected to Cloud API, it's must you verify the business profile first. And to do so, you've to visit [https://developers.facebook.com/](https://developers.facebook.com/), select My Apps, and then click on the Business name.

On the Business Settings page, scroll down the left tab and select Business Info.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2F7ESJqVoOZJhnhPAGtHvL%2FAccessing%20Business%20Info.jpg?alt=media&#x26;token=308af17d-bb57-408c-8c28-dea302cae33a" alt=""><figcaption><p>Accessing Business Info</p></figcaption></figure>

Then, on the Business information page, add information in the Business details section.

Once added the required information, you can continue with the next step.

### 4) Create a Chatobuy Cloud API Channel

You've created a WhatsApp Business Profile, now you can connect Chatobuy to it. In order to do so, log in to your Chatobuy account, then go to Channels, and click **Configure** for Cloud API.

Or you could click _Create Channel_ if there are channels already in the list.

As soon as you click the Next button, a popup will appear with several fields. In those fields, you've to set Channel Title, System User Access Token and Business Manager ID.

For Title, you can set anything that will help you recognise the channel. For System User Access Token, you've to access your WhatsApp Application to generate it using the _Webhook URL_ and _Verify Token_ mentioned in the above channel details.

#### Edit Webhook Callback URL and Verify Token

First, go to [https://developers.facebook.com/apps/](https://developers.facebook.com/apps/), then select the app.

This will open the app dashboard like the following. There, click on WhatsApp and select Configuration.

Then, on the Configuration page, click **Edit** in the Webhook section.

This will open the following Webhook's callback URL popup.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FNZwkGhSUz43PoClFC2mn%2FWebhook%20Callback%20URL%20Popup.jpg?alt=media&#x26;token=fc33680b-62e4-4d87-b8ae-d8ee80efe31d" alt=""><figcaption></figcaption></figure>

Here, you need to paste the values available in the Channel Details at Chatobuy.

First copy the Webhook URL, then Verify Token and paste them into the Webhook's callback URL. You've to copy and paste the values individually.

Once added both the values click on **Verify and save**. After saving the webhook URL, click **manage** to select webhook fields.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FZg7nTTyLKmi1XPjIiPf6%2FSubscribing%20to%20all%20Webhook%20Fields.jpg?alt=media&#x26;token=a952e38e-6127-486e-83ae-9a9abfe32de6" alt=""><figcaption><p>Subscribing to Webhook Fields</p></figcaption></figure>

You'll see multiple webhook fields. _Subscribe_ to all and then click **Done**. After this, you'll see your subscribed webhook fields in the configuration section.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FdvbsMleSWNYx1kt7VaQH%2FSubscribed%20Webhook%20field.jpg?alt=media&#x26;token=dd36e4c6-cde6-461f-a615-adc506f6b063" alt=""><figcaption><p>Subscribed Webhook Fields</p></figcaption></figure>

Now, you can generate the System User Access Token

#### Generating System User Access Token

To generate the System User Access Token for Cloud API Channel at Chatobuy, you need to go to [https://business.facebook.com/settings/](https://business.facebook.com/settings/), there select the Business account manager you've used to create the WhatsApp application.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FlBUtlcDeHlaR8fo8PMoP%2FSelecting%20Business%20Account%20Manager%20to%20Generate%20Access%20Token.jpg?alt=media&#x26;token=4fe42e76-c9c1-4a72-b2a0-629b9f1afa5d" alt=""><figcaption><p>Selecting Business Account Manager</p></figcaption></figure>

Based on your selection, it will open the Meta Business Settings. There, you'll have to go to the Users → System Users → click **Add**.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FHVQrNqbQgnjxSvxRnEM8%2FAdding%20System%20User.jpg?alt=media&#x26;token=bd8cd177-c721-4a2f-ad86-f668dbd69cec" alt=""><figcaption><p>Adding a System User</p></figcaption></figure>

It will open a terms modal, simply click **I Accept**, then **Done** and on the next window, enter details as,

* System Username - The name you want to assign to this user.
* System User Role - Admin.

Once given the username and assigned the Admin role, click **Create System User**. This will take a few moments to create the system user. Once the user has been created it will ask you to accept the terms.

So, click **I Accept** then **Done**, and you'll have your System User page as the following.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FQpQeE6LFGRGfw9tjLdiO%2FAdd%20Assets.jpg?alt=media&#x26;token=0e9e79d2-205f-4304-966c-bfd7b4499bb6" alt=""><figcaption><p>Adding Assets</p></figcaption></figure>

Here, click **Add Assets**.

An assigning assets popup will come for the System User in which you have to select **Apps** → **select the App** → **Toggle everything to YES** → then click **Save Changes** → **Done**.

Once you finish assigning the asset, you can see the app in the System User Account.

Now to generate the System User Access Token, click **Generate New Token**.

Then select the App,

And once you select it, you'll find different permissions from which you have to select,

* business\_management
* whatsapp\_business\_\_messaging\_
* whatsapp\_business\_management

After selecting the permissions, click **Generate Token**. This will bring the access token which you have to copy and save on your cloud storage or local system. Once copied, click OK.

Now, head back to Chatobuy, and paste the access token in the System User Access Token Field.

Then, visit the System User again, and copy the business id from the URL.

Head back to Chatobuy again and paste the Id in the Business Manager ID field. Then, click **Fetch Numbers**.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2Fdm7NRNTMjfmLgt6NLxz6%2FAdding%20Business%20Manager%20ID%20and%20Fetching%20Number.jpg?alt=media&#x26;token=b10d2924-b451-4f49-943c-0af0f59bcdc3" alt=""><figcaption><p>Adding Business Manager ID and Fetching Phone Numbers</p></figcaption></figure>

This will showcase the WhatsApp Business Accounts and the Phone Numbers Associated with them.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FQptGrPF9YbwCb0kD382u%2FFinal%20Step%20Cloud%20API.jpg?alt=media&#x26;token=9649bac4-05dc-46d5-b5e0-7f90c757e6c9" alt=""><figcaption><p>WhatsApp Business Account and Phone Number</p></figcaption></figure>

Confirm the details or select a different account and number, then click **Finish**. That's it; you've successfully created a Chatobuy Channel and connected it to Cloud API.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2F5naEMJBVIC6e9undBOfB%2FWhatsApp%20Cloud%20API%20in%20RUM%20Work%20Channels.jpg?alt=media&#x26;token=82c61297-1042-40a5-a13f-33eef33ff1a3" alt=""><figcaption></figcaption></figure>

{% hint style="success" %}
Now, you can chat with customers over WhatsApp using the Chatobuy Channel. However, you'll only be able to send and receive up to 1,000 free messages monthly. To increase the limit, you've to add a payment method.
{% endhint %}

### Channel Configuration

The additional options available for the Channel enable you to utilise it at its best.

<figure><img src=".gitbook/assets/channelconfigure.PNG" alt=""><figcaption></figcaption></figure>

* **Details** - Using this access additional options to create Message Templates, [**Buttons/Options/Product Messages**](cloud-api.md#button-options-product-messages), Store Settings, and more.
* [**Manage Templates**](cloud-api.md#set-up-message-template) - Directly access the controls to manage or create message templates.
* [**Store Settings**](cloud-api.md#store-settings) - Configure payment partners and links for the channel.
* [**Manage Profile**](cloud-api.md#manage-profile) - Make changes to the WhatsApp Business Profile.
* [**Edit**](cloud-api.md#more-options) - Access controls to edit channel; copy its id and more.

### Set Up Message Template

Refer to the following docs.

### Button/Options/Product Messages

Refer to the following docs

### Store Settings

Please, explore the following doc to learn more about Chatobuy WhatsApp Channel Store Settings.

### Manage Profile

Using the Manager Profile option of your Cloud API WhatsApp Channel, you can change your business details for WhatsApp.

Click on the Manage Profile, and it opens the Profile settings like the following,

Here, you can change your Profile Picture, Address, Description, Email, Website and Business Vertical from the available options,

* Automotive Beauty
* Spa and Salon
* Clothing and Apparel
* Education
* Entertainment
* Event Planning and Service
* Finance and Banking
* Food and Grocery
* Public Service
* Hotel and Lodging
* Medical and Health
* Non-profit Professional Services
* Shopping and Retail
* Travel and Transportation
* Restaurant
* Other

Once done, click **Save Changes**.

### More Options

In addition to the Manage Templates, Store Settings, and Manage Profile, there are a few more options you can utilise.

<figure><img src="https://1685557723-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FPwUAKMB3e4WVQQkcLJNq%2FMaytapi%20Channel%20More%20Options.png?alt=media&#x26;token=7dd19682-7980-44c1-8f20-54570afbaa3e" alt=""><figcaption></figcaption></figure>

* **Edit** - It provides you with the option to change Channel Name; Add Webhook URL and Disconnection Alert Emails.
* **Delete** - Simply delete the channel.
* **Mark as Default** - You'll see this particular channel as the primary channel in the Chat.
* **Copy Channel ID** - Copy Channel ID without opening the Phone Settings.
