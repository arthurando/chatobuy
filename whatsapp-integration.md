---
description: >-
  Chatobuy Channels let you connect with WhatsApp Business API and exchange
  messages with customers on WhatsApp. The integration is simple and quick but
  requires WhatsApp approval.
---

# WhatsApp Integration

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FXNQPWgqXHhEJmQzx4PDl%2FWhatsApp%20Business%20API.png?alt=media&#x26;token=942eab7e-1369-4720-92ee-427217a6d873" alt=""><figcaption></figcaption></figure>

WhatsApp is among the most popular messaging platforms/applications, with over 2 billion active users. It also offers a business application version that allows businesses to answer customer queries. And with the help of WhatsApp Business API, you can integrate that into Chatobuy and send, receive, and track WhatsApp messages effortlessly while managing other chat platforms simultaneously.

However, before integrating the WhatsApp Business API to Chatobuy, there are a few things you need to do:

* First, Create a WhatsApp Business API using the partners supported at Chatobuy.
* Once created the API, generate the User Token for the specific WhatsApp Channel you've created the API with.

{% hint style="info" %}
For instance, if you've created the WhatsApp Business API with [360Dialog](https://github.com/rampwin/rampwin-gitbook-docs/blob/main/broken-reference/README.md), then use the 360Dialog Channel to integrate WhatsApp Business API to Chatobuy. It will enable you to have personalized interactions with different customers through automated replies and more.
{% endhint %}

### Supported WhatsApp Providers

At RUM Work, you can utilize 4 channels at the moment to integrate WhatsApp Business API.

<table><thead><tr><th width="132">Provider</th><th width="107">Type</th><th width="133">Monthly Fee</th><th width="118">Messaging Pricing</th><th width="118">Messaging Limit</th><th width="209">Sign Up Link</th></tr></thead><tbody><tr><td><a href="https://github.com/rampwin/rampwin-gitbook-docs/blob/main/broken-reference/README.md">360dialog</a></td><td>Official</td><td>$25/number</td><td>Managed by Facebook</td><td>1K in 24HR Window</td><td><a href="https://hub.360dialog.com/lp/whatsapp/XuWWScPA">https://hub.360dialog.com/lp/whatsapp/XuWWScPA</a></td></tr><tr><td><a href="https://github.com/rampwin/rampwin-gitbook-docs/blob/main/broken-reference/README.md">Emma</a></td><td>Official</td><td>Custom</td><td>Custom</td><td>1K in 24HR Window</td><td>Reach out to us at hello@rumwork.io</td></tr><tr><td><a href="https://github.com/rampwin/rampwin-gitbook-docs/blob/main/broken-reference/README.md">Cloud API</a></td><td>Official</td><td>0</td><td>Managed by Facebook</td><td>1k in 24HR Winddow</td><td>-</td></tr><tr><td><a href="https://github.com/rampwin/rampwin-gitbook-docs/blob/main/broken-reference/README.md">Maytapi</a></td><td>Unofficial</td><td>$30</td><td>0</td><td>Max Fixed 6000 Messages/Day. Incoming Unlimited</td><td><a href="https://maytapi.com/">https://maytapi.com/</a></td></tr></tbody></table>

### WhatsApp Messaging Window

{% hint style="warning" %}
WhatsApp Business Platform has a Customer Service Window (24-hour) in which businesses can send both simple messages and [pre-approved templates](https://github.com/rampwin/rampwin-gitbook-docs/blob/main/broken-reference/README.md). Outside the customer service window, the business would require a message template.
{% endhint %}

The WhatsApp Business Platform works around two different categories of conversation:

1. **User-initiated** - When the user or customer sends the message to the business. The business can respond to the message with a simple message or message template within 24 hours. Once the window has expired, the business can only respond with a message template which will be counted as a **Business-initiated** conversation.
2. **Business-initiated** - When the business reaches out to the customer outside the 24-hour customer service window, its falls under the Business-initiated conversation. For a business-initiated conversation, a message template is required.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2Famd3K2ea0SkpCz4S5hxw%2FWhatsApp%20Business%20Platform%20Conversation%20Types.png?alt=media&#x26;token=73e6e906-0623-4e72-bbfd-9e67447e588d" alt=""><figcaption><p>WhatsApp Business Platforms Conversation Types</p></figcaption></figure>

### Official and Unofficial WhatsApp Business API

**Official WhatsApp Business API** is a valid and approved API from WhatsApp itself. And using the WhatsApp partners, you can avail of an official WABA account without following multiple steps. The official partners supported at Chatobuy are,

* Emma.
* and 360dialog.

Cloud API is the official API platform from WhatsApp that involves multiple steps to register your number and access WhatsApp Business API. However, you can save time using the partners and get your WABA account quickly.

**Unofficial WhatsApp Business API** is not a partner provider of WhatsApp Business API. They use their own platform and APIs to help you connect your WhatsApp account.

The unofficial WhatsApp Business API provider supported at RUM Work is,

* Maytapi.

### Official WhatsApp Business API Prerequisites

Before you connect Chatobuy Channel to Official WhatsApp Business API using our partners, ensure,

* You have a valid mobile number.
* An existing Meta Business Account (optional as you can create a new while during the process.)
* The mobile number is not already used for WhatsApp(Personal and Business).
* If you want to use the same WhatsApp Number you've previously used for Business, follow this guide to learn how to delete the WhatsApp account.

Once you meet the above requirements, you can create and connect the Chatobuy Channel.
