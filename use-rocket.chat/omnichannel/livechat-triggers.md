# Livechat Triggers

Omnichannel Live Chat Triggers are events you can set up. When these events occur, they make the Live Chat widget take action or open automatically.

To access this menu, go to **Administration > Omnichannel > Live Chat Triggers**. Here, you can **View**, **Create New**, **Edit** or **Delete** existing Live Chat Triggers.

## Create New Omnichannel Live Chat Trigger

To create a new Omnichannel Live Chat Trigger:

* Click +**New** on the top right of the screen
* A page for the department details is seen. Fill in these details and click **Save**

### Omnichannel LiveChat Trigger Information

* **Enable**: Enables the Live Chat Trigger
* **Run only once for each visitor**: Enable to let the trigger only run once for each visitor. If false, you get a recurring pop-open. (e.g., If your user goes to a different website and comes back to the same website, it pops open).
* **Name**: Name your new trigger.
* **Description**: Allows you set the description of the trigger.
* **Condition**: Allows you set the condition for which the action will be triggered. Depending on what condition to track, you can set additional properties for validation.
  * **Visitor Page URL**: It allows you to enter a regex to describe the website page you want the action to occur. For example, if you own a website called _xyz.com_ and you only want the live chat widget action to occur on one specific page _(xyz.com/contact)_, not on any other pages, select **Visitor Page URL** and define the regex in the **Action** field. For this example, the regex should look like `.*/contact`.
  * **Visitor Time on Site**: The action occurs after the specified time in seconds once the customer visits your website.
  * **Chat Open by Visitor**: The action occurs when the customer/visitor opens a new chat.
  * **After Guest Registration**: The action occurs after a guest submits the LiveChat registration form.
* **Action**: Define the action you want the Live Chat widget to perform. For now, there is only one option of sending a message to the visitor. You can also select if you want to impersonate the next available agent in the queue or use a bot/custom agent.

## Edit Omnichannel Live Chat Trigger

To edit an O**mnichannel Live Chat Trigger**:

* Click on the Trigger from the list of Triggers
* A section is opened with all the current details of that Trigger, which can be modified and saved.

## Delete Omnichannel Live Chat Trigger

To delete an **Omnichannel Live Chat Trigger**, click on the **delete icon** by the right of the Trigger from the Triggers.
