# Automation Workflows

### Overview

Using Automation Workflows, you can run automated Actions on Chatobuy based on **Trigger** and **Trigger Condition(s)**. For creating and running an automation workflow, it's necessary to select the Trigger (you can use only one trigger for single automation) and based on that; you need to choose condition(s) and define its values.

To access Automation Workflows, you can go to the **Automation** → **Automation** from your Dashboard.

<figure><img src=".gitbook/assets/image (2) (1) (1).png" alt=""><figcaption></figcaption></figure>

Or, you can go to **→ Automation**.

### Creating a Workflow

To create an automation workflow, you need to click the **Create Automation Workflow** button.

<figure><img src=".gitbook/assets/screenshot-nimbusweb.me-2024.05.21-10_35_16.png" alt=""><figcaption></figcaption></figure>

This will open the Create Automation Workflow modal with the options as -

* Automation Name
* Channel / Service Integration (trigger dependent)
* Trigger Event
* Actions

<figure><img src=".gitbook/assets/image (3) (1) (1).png" alt=""><figcaption></figcaption></figure>

Learn more about workflow options at -

{% content-ref url="trigger.md" %}
[trigger.md](trigger.md)
{% endcontent-ref %}

{% content-ref url="trigger-conditions.md" %}
[trigger-conditions.md](trigger-conditions.md)
{% endcontent-ref %}

{% content-ref url="actions-steps.md" %}
[actions-steps.md](actions-steps.md)
{% endcontent-ref %}

#### Select Trigger

In the Create Automation Workflow modal, first, you need to define a name for the automation. Then, select a Channel from the available options.

<figure><img src=".gitbook/assets/screenshot-nimbusweb.me-2024.05.21-10_46_09.png" alt=""><figcaption></figcaption></figure>

After selecting the Channel, you need to select either a Trigger or Service Integration,

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2F4O1V919w1eWsNN38A1K9%2FSelecting%20a%20Channel%20for%20the%20Automation%20Workflow%20Trigger.jpg?alt=media&#x26;token=5f3e0f2d-2486-4e05-b83e-53e2b407681c" alt=""><figcaption></figcaption></figure>

#### Select Trigger Condition

Based on your selected [Trigger](https://github.com/rampwin/rampwin-gitbook-docs/blob/main/broken-reference/README.md), you get the Trigger Conditions. Simply select the required condition.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FH8JvP8PloCZPagsYpwBS%2FSelect%20Trigger%20Condition.png?alt=media&#x26;token=a00f6292-0b61-4436-8eb4-002be3446f25" alt=""><figcaption></figcaption></figure>

Then, provide the text or keywords for the Match String or Text keywords field - except in the case of Received outside business hours, New Catalog Order Received, and Very first message or message after 24 hours of the last message.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FWMjBvDT1paM3vkTo1w0F%2FMatch%20string%20or%20text%20keywords.png?alt=media&#x26;token=39081b5b-270c-4fcc-8a49-940401c274e1" alt=""><figcaption></figcaption></figure>

Then check **Is Case Sensitive** if you want the Text or Keywords to exactly match.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FpR880X4lmtHv7WKVNVQz%2FIs%20Case%20Sensitive.png?alt=media&#x26;token=0db44791-bef3-4a21-aa8f-e6ec35e642aa" alt=""><figcaption></figcaption></figure>

If you want to use multiple conditions, click **Add More Condition**.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2F5LzY2HljEarh0zycvDTo%2FAdding%20More%20Conditions.png?alt=media&#x26;token=6fee2f24-05c5-4d16-80ce-347d100254d6" alt=""><figcaption></figcaption></figure>

Once you've added the Trigger Condition(s), you can proceed to add the Workflow Steps.

#### Add Steps

To add Workflow Steps, click the **Add Workflow Step** to access Action types.

<figure><img src=".gitbook/assets/screenshot-nimbusweb.me-2024.05.21-12_09_34.png" alt=""><figcaption></figcaption></figure>

This will open the Workflow Steps modal with all the step types.

<figure><img src=".gitbook/assets/Recording 2024-05-21 121602.gif" alt=""><figcaption></figcaption></figure>

There are a total of 24 Workflow Steps you can select to assign them to an automation trigger. Simply select your Steps from the given list and configure them accordingly. To learn how each step works and what's the best way to configure them, visit [Steps](https://github.com/rampwin/rampwin-gitbook-docs/blob/main/broken-reference/README.md) documentation.

Once, you've saved the Step, it will appear in the Create Automation Workflow modal as the following.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FHraDR4wW02wyGBdFeHHp%2FSaved%20Workflow%20Step.jpg?alt=media&#x26;token=3161cc7f-9289-40c5-a280-2e14b53e0be8" alt=""><figcaption></figcaption></figure>

To add more steps, you can simply click the Add Workflow Step button. Once you've added all the required steps, you can click Save to create your Automation Workflow.

<figure><img src=".gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>

It will appear in the Automation Workflows library.

<figure><img src=".gitbook/assets/screenshot-nimbusweb.me-2024.05.21-12_25_49.png" alt=""><figcaption></figcaption></figure>

### Editing a Workflow

To edit an Automation Workflow, click the Pen icon.

<figure><img src=".gitbook/assets/screenshot-nimbusweb.me-2024.05.21-12_28_42.png" alt=""><figcaption></figcaption></figure>

This will open the Update Automation Workflow modal. Here, you can only make changes to the Channel, Trigger Condition, and Steps.

<figure><img src=".gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure>

You can add more conditions by clicking the Add More Condition button. Or you can change the current with another.

For Step(s) you can edit it by clicking the Pen icon on the right side. When you edit the step, you can change the value for the selected Step type. Or you can choose another Step by simply clicking the Action Type field.

<figure><img src=".gitbook/assets/image (33).png" alt=""><figcaption></figcaption></figure>

Once the Step, click Update to make changes.

<figure><img src=".gitbook/assets/screenshot-nimbusweb.me-2024.05.21-12_28_42 (1).png" alt=""><figcaption></figcaption></figure>

If you want to delete a step, simply click the Trash icon.

<figure><img src=".gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>

After making all the changes, to save the edited Automation Workflow, you need to click the **Update** button and Save.

### Deleting a Workflow

To delete an Automation Workflow, simply click the Trash icon next to the edit button.

<figure><img src=".gitbook/assets/screenshot-nimbusweb.me-2024.05.21-12_28_42 (2).png" alt=""><figcaption></figcaption></figure>

This will remove the workflow completely.
