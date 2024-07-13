# Automation Workflows

### Overview

Using Automation Workflows, you can run automated Actions on Chatobuy based on **Trigger** and **Trigger Condition(s)**. For creating and running an automation workflow, it's necessary to select the Trigger (you can use only one trigger for single automation) and based on that; you need to choose condition(s) and define its values.

To access Automation Workflows, you can go to the **Automation** → **Automation** from your Dashboard.

<figure><img src=".gitbook/assets/automation.PNG" alt=""><figcaption></figcaption></figure>

Or, you can go to **→ Automation**.

### Creating a Workflow

To create an automation workflow, you need to click the **Create Automation Workflow** button.

This will open the Create Automation Workflow modal with the options as -

* Automation Name
* Channel / Service Integration (trigger dependent)
* Trigger Event
* Actions

<figure><img src=".gitbook/assets/createanautomation.PNG" alt=""><figcaption></figcaption></figure>

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

After selecting the Channel, you need to select either a Trigger or Service Integration,

#### Select Trigger Condition

Based on your selected [Trigger](trigger.md), you get the [Trigger Conditions.](trigger-conditions.md) Simply select the required condition.

<figure><img src=".gitbook/assets/createanautomation.PNG" alt=""><figcaption></figcaption></figure>

Then, provide the text or keywords for the Match String or Text keywords field - except in the case of Received outside business hours, New Catalog Order Received, and Very first message or message after 24 hours of the last message.

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FhElFPtMZjXYjDDMBT5q2%2Fuploads%2FWMjBvDT1paM3vkTo1w0F%2FMatch%20string%20or%20text%20keywords.png?alt=media&#x26;token=39081b5b-270c-4fcc-8a49-940401c274e1" alt=""><figcaption></figcaption></figure>

Then check **Is Case Sensitive** if you want the Text or Keywords to exactly match.

If you want to use multiple conditions, click **Add More Condition**.

Once you've added the Trigger Condition(s), you can proceed to add the Workflow Steps.

#### Add Steps

To add Workflow Steps, click the **Add Workflow Step** to access Action types.

This will open the Workflow Steps modal with all the step types.

<figure><img src=".gitbook/assets/Recording 2024-05-21 121602.gif" alt=""><figcaption></figcaption></figure>

There are a total of 24 Workflow Steps you can select to assign them to an automation trigger. Simply select your Steps from the given list and configure them accordingly. To learn how each step works and what's the best way to configure them, visit [Steps](https://github.com/rampwin/rampwin-gitbook-docs/blob/main/broken-reference/README.md) documentation.

Once, you've saved the Step, it will appear in the Create Automation Workflow modal as the following.

To add more steps, you can simply click the Add Workflow Step button. Once you've added all the required steps, you can click Save to create your Automation Workflow.

It will appear in the Automation Workflows library.

### Editing a Workflow

To edit an Automation Workflow, click the Pen icon.

This will open the Update Automation Workflow modal. Here, you can only make changes to the Channel, Trigger Condition, and Steps.

You can add more conditions by clicking the Add More Condition button. Or you can change the current with another.

For Step(s) you can edit it by clicking the Pen icon on the right side. When you edit the step, you can change the value for the selected Step type. Or you can choose another Step by simply clicking the Action Type field.

Once the Step, click Update to make changes.

If you want to delete a step, simply click the Trash icon.

After making all the changes, to save the edited Automation Workflow, you need to click the **Update** button and Save.

### Deleting a Workflow

To delete an Automation Workflow, simply click the Trash icon next to the edit button.

This will remove the workflow completely.
