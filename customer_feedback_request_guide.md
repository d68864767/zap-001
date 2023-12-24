# Customer Feedback Request Guide

This guide provides detailed instructions on how to set up a Zap for sending automated feedback request emails to customers after an interaction. This Zap can be triggered with a button click.

## Prerequisites

Before you start, make sure you have the following:

- A physical button that integrates with Zapier (like Flic or a similar IoT button).
- A Zapier account to create and manage your Zaps.
- An email service that integrates with Zapier (like Gmail, Outlook, etc.).
- A customer relationship management (CRM) system that integrates with Zapier (like Salesforce, HubSpot, etc.).

## Steps

1. **Set up the trigger**: Log in to your Zapier account and click on 'Make a Zap'. Choose your IoT button as the trigger app and select 'Button Pressed' as the trigger event. Follow the prompts to connect your button to Zapier.

2. **Set up the action**: Choose your email service as the action app. Select 'Send Email' as the action event. Follow the prompts to connect your email service to Zapier.

3. **Configure the email**: In the 'Set up action' step, configure the email to be sent. You can use dynamic content from the trigger to personalize the email. For example, you can use the customer's name and the product they purchased in the email subject or body.

4. **Set up the CRM integration**: Add another action step and choose your CRM as the action app. Select an appropriate action event (like 'Create/Update Contact') and configure it to update the customer's record with the feedback request.

5. **Test and turn on your Zap**: Finally, test your Zap to make sure it works as expected. If everything is fine, turn on your Zap. Now, whenever you press the button, it will trigger this Zap and send a feedback request email to the customer.

Remember, you can customize this Zap to suit your needs. For example, you can add more action steps to update other systems or send notifications.

## Troubleshooting

If you encounter any issues while setting up or using this Zap, check the following:

- Make sure all your apps are correctly connected to Zapier.
- Check the trigger and action configurations to ensure they are correct.
- If the Zap is not triggering, check the button's connection and make sure it's working properly.

If you still need help, feel free to ask for more detailed instructions or assistance.
