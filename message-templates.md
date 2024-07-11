# Message Templates

Message Templates are used to initiate business side conversations after the 24-hour Customer Service Window. To learn more about message templates, refer to the following doc.

To create a Message Template for the Cloud API WhatsApp Channel, click **Manage Templates**.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FjwVmMOTzsO60dGjk3mAs%2FManage%20Templates%20Button.png?alt=media&#x26;token=c836cad7-2dc1-4dce-a8c0-b3f65a60f2d5" alt=""><figcaption><p>Accessing Cloud API Message Templates Options</p></figcaption></figure>

This will open the Message Templates window with an ACCOUNT\_UPDATE template created by Facebook by default.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FtwDNVNJfK1vFbPhr3y6q%2FMessage%20Template%20Window%20for%20Cloud%20API.png?alt=media&#x26;token=fa7306d9-9621-485d-bc03-99d29a9bb790" alt=""><figcaption><p>Message Template Window</p></figcaption></figure>

The options available are,

* **Create WhatsApp Template** - Using this, you can access the builder to create a WhatsApp Message Template.
* **Synchronize with Facebook** - Sync Rampwin Templates with Facebook.
* **Delete the Message Template** <img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2F3Of4IVOBkTD6Yfey20F7%2FDelete%20Button.png?alt=media&#x26;token=82c696d8-8f39-4ebd-82c3-f74f28e61d38" alt="" data-size="line">
* **Duplicate the Message Template**<img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FMFKb5CR3QvlaV10MWhF8%2FDuplicate%20Icon.png?alt=media&#x26;token=4dbc2f44-7395-4eb4-90a6-2f0014a7b5c0" alt="" data-size="line">

### Create a Template

To create a Message Template, click **Create WhatsApp Template**.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FDyWB5PVoaq3sTEG1jzM8%2FCreate%20WhatsApp%20Template%20Button.png?alt=media&#x26;token=dd3730eb-0ae9-4d62-8035-a29ed9b9a909" alt=""><figcaption></figcaption></figure>

A Create Message Template popup will come in which you get the options to,

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FGAITowgCZEPuZWnjLgRD%2FMessage%20Template%20Popup.png?alt=media&#x26;token=c407cf8e-9af6-47ca-a992-39f877cb0106" alt=""><figcaption></figcaption></figure>

* Define Template Name - **Name**
* Select Category - **Category** (One Time Password, Transactional and Marketing)
* Choose Language - **Language**
* Set Template Header - **Header** (None, Text, Image, Video and Document)
* Add Body Text - **Body**
* Set Footer - **Footer(Optional)**
* Add Button Options - **Button(Optional)**

Now, first, define the Template name, then select a category and after that, choose a language. Ensure you select the language in which you'll add the body text. Otherwise, it will be rejected. Also, keep the template name in the lowercase with an underscore if you're going to add space like the following,

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FQ6KryksE1fQYqhBev12p%2FAssigning%20Template%20Name%2C%20Category%20and%20Language.png?alt=media&#x26;token=fc9de18c-aab2-423a-a6e6-e22078bc61fa" alt=""><figcaption></figcaption></figure>

Then select your Header type from the available options,

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FbPaHz397YvR1faYA6ekK%2FInserting%20Header%20Text%20for%20Message%20Template.gif?alt=media&#x26;token=1690785b-d8c5-4c40-866c-2703a6a9e5af" alt=""><figcaption></figcaption></figure>

If you choose Text, add a variable that will be used as a placeholder for the template, which you'd replace with the correct information of the contact you'll send the template to. Plus, add the variable's example in the **Example Content for** the field.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FzDRTAXmG2dxlet7NFbnG%2FExample%20Content%20for%20Variable.png?alt=media&#x26;token=3504004a-f2b8-42fd-b801-84a5527f68d2" alt=""><figcaption></figcaption></figure>

For instance, if you'd replace the variable placeholder with the contact's name, you can enter example content as Name to help Facebook verify the use of the template and approve it.

{% hint style="info" %}
If you set Header Text as, "_Hi,\{{1\}} your order has been received_," and Example content for \{{1\}} as "_Name_," then while sending the template message to the contact, replace variable to contact's name. The template header text would be, "_Hi, **Alex** your order has been received._"
{% endhint %}

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FvzQEIQX6lyFi9zcbkYIx%2FHeader%20Types%20for%20Message%20Template.png?alt=media&#x26;token=cd9a5f06-289f-402c-a3ce-8f6a5bb1a85d" alt=""><figcaption></figcaption></figure>

If you choose Header type as Image, Video, or Document, you need to upload a sample file to help Facebook verify the use. It should be a sample file, not an original Image, Video, or Document detailing your contact.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FKoWPqZZNuIE5QSqwNrmB%2FUploaded%20Image%20File%20and%20Sample%20Preview%20of%20the%20Message%20Template.png?alt=media&#x26;token=989a158d-4927-43b5-8b35-c29928e6e572" alt=""><figcaption></figcaption></figure>

Once the file is uploaded, you can see it in the preview tab. After setting the Text, or uploading a file representing the Header, enter the text for your Body.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2Fcf7mpldrVnz0txpnmDQ1%2FBody%20Text%20With%20Variable.png?alt=media&#x26;token=b4e83662-da35-4704-b5dc-9eee38e7b142" alt=""><figcaption></figcaption></figure>

Ensure you add one variable at least in the Body. When you send the template message, these can be replaced by the correct information.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FqJSc0xphxXjzjJZJu732%2FFooter%20Field%20in%20the%20Message%20Template.png?alt=media&#x26;token=54cac61f-d1fd-47f6-9580-8e64ba72c76a" alt=""><figcaption></figcaption></figure>

If you'd like to add a Footer to the template, you can do that in the Footer Field, which is optional.

### Button(s)

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FWYwq902WfQbwLaqrTS4c%2FButton%20Options.png?alt=media&#x26;token=ba2ef08d-f246-417e-8abc-e1c503fdaaa0" alt=""><figcaption></figcaption></figure>

After the footer, you get the option to add buttons to your message template. The template support adding two types of buttons: **Call to Action** and **Quick Reply**.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2Fm3hgTbEo1vSVIfFyAcPB%2FCTA%20Button%20Options%20in%20the%20Message%20Template.png?alt=media&#x26;token=821c7567-2660-42a3-b66b-69979f20d7aa" alt=""><figcaption></figcaption></figure>

The Call to Action button lets you further add 2 buttons: **Call Phone Number** and **Visit Website**

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FuS80oAT4KoV4YaVxbBl7%2FQuick%20Reply%20Button%20in%20Message%20Template.png?alt=media&#x26;token=d8bf6fc7-fd24-4575-b651-dad59a689edf" alt=""><figcaption></figcaption></figure>

And the Quick Replay button lets you add 3 buttons for the selected purpose.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FVgBTSkAAPgBV6Osp5Rg5%2FSubmit%20for%20Approval%20Message%20Template.png?alt=media&#x26;token=e1ad260b-bb05-4020-91c9-d37a0af48a90" alt=""><figcaption></figcaption></figure>

After adding all the details to the template, check its Preview, and if everything's fine, click **Submit For Approval**.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FjgiSMnj3xTj3RcniYjwC%2FTemplates%20Library.png?alt=media&#x26;token=343e6084-950a-4a81-abe0-5a6916257cb2" alt=""><figcaption></figcaption></figure>

As soon as the template gets approved, you'll find it in the templates library like the above.

### Using a Message Template

There are 2 ways to use a message template,

1. Using [Chat](https://github.com/rampwin/rampwin-gitbook-docs/blob/main/broken-reference/README.md)
2. And using [Drip Campaign](https://github.com/rampwin/rampwin-gitbook-docs/blob/main/broken-reference/README.md)

While using the template through one of the above methods, ensure you replace the variable with the correct information.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FXrQ2gi1j3p2azxzZE56i%2F%C2%A0Replacing%20Variable%20with%20Attribute%20Placeholder.gif?alt=media&#x26;token=9c92fb4a-084f-40ca-a12b-1e274cb92653" alt=""><figcaption></figcaption></figure>

Simply select the Attribute Placeholder to replace the variable. And once you send the template, the message will pick the correct information, and it will look like the following.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2Fh2koIE7uJCfPtdZZ2XN2%2FTemplate%20Message%20With%20Variable%20Explanation.png?alt=media&#x26;token=4d293717-496a-4832-8a6a-61c7207bfdf3" alt=""><figcaption></figcaption></figure>

That's it; you've successfully created a Message Template and learned how to use it.
