
# TeamWebhook
## Using Laravel Notification subsystem to send messages to Microsoft Teams through the Legacy actionable message card reference.

This code is to provide a template to easily send message cards to Microsoft Teams.

Based on current documentation, Microsoft Teams uses legacy API card reference found at: https://docs.microsoft.com/en-us/outlook/actionable-messages/message-card-reference, while Outlook uses the newer Adaptive Card Format. Future releases of Teams is expected to use newer format.

Laravel Notifications framework and explanation for 5.7 can be found: https://laravel.com/docs/5.7/notifications

The included channel, message, and notification code is provided as a template to understand how to submit messages to your Microsoft Team implementation.

Here is a sample card:
![card](https://user-images.githubusercontent.com/45673576/49627259-81f36e80-f9a3-11e8-8893-f7316cbc6297.PNG)

## Setting up a webhook in Microsoft Teams

https://docs.microsoft.com/en-us/outlook/actionable-messages/send-via-connectors

While the above link doesn't necessarily direct you to Microsoft Teams, it is as close to some instructions as I have found. It is rather intuitive. Within Teams, go to the channel/team, click on the ellipsis/More Options, select Connectors. Search for Webhook and follow instructions.

## Work in progress
As it stands, this example shows how to create a card, and add activity details. There are some options for the color of the card enumerated as Success, Error, Info, and Warning. In the near future, adding facts, and maybe some additional buttons for actions will come.
