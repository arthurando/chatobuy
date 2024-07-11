---
description: >-
  When Your app is configured you can setup automation on Webhook Topics like
  below.
---

# Setup WooCoomerce Automations

* COD Order confirmation & Prepaid order notfication
* Track Order
* Abandoned Cart

#### How to setup COD Order Automation.

* Click on Automation.
* Click on Create Automation.
* Give a title, Select Channel & Choose WooCommerce Order Place Event.
* Click on Create.

<figure><img src=".gitbook/assets/woo_automation.png" alt=""><figcaption><p>COD Order Confirmation</p></figcaption></figure>

<figure><img src=".gitbook/assets/image (4) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>Choose Custom Condition</p></figcaption></figure>

* [ ] Choose Action Auto Reply Template Message.
* [ ] Choose your template for COD order confirmation.
* [ ] Choose your placeholders in Template message & Save.

<figure><img src=".gitbook/assets/chooseaction.png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/chooseplaceholder.png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/copycallbackid.png" alt=""><figcaption></figcaption></figure>

If your template have buttons like Confirm COD Order, Cancel COD order, Connect with Agent then you have to create a separate automation for that.

User below steps to update order notes in your WooCommerce.

* Create a new automation.
* Give name, choose channel & select trigger New incoming message received.
* Click on Create automation button.
* Choose custom condition "List/Button Callback ID Matches" & paste your callback id in the value.
