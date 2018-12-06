
# TeamWebhook
## Using Laravel Notification subsystem to send messages to Microsoft Teams through the Legacy actionable message card reference.

This code is to provide a template to easily send message cards to Microsoft Teams.

Based on current documentation, Microsoft Teams uses legacy API card reference found at: https://docs.microsoft.com/en-us/outlook/actionable-messages/message-card-reference, while Outlook uses the newer Adaptive Card Format. Future releases of Teams is expected to use newer format.

Laravel Notifications framework and explanation for 5.7 can be found: https://laravel.com/docs/5.7/notifications

The included channel, message, and notification code is provided as a template to understand how to submit messages to your Microsoft Team implementation.
