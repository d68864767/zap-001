# Email Digest of Daily Tasks Guide

This guide will walk you through the steps to create a Zap that compiles a list of your tasks for the day from your task management tool and sends you an email digest.

## Prerequisites

Before you start, make sure you have:

- A physical button that integrates with Zapier (like Flic or a similar IoT button).
- A Zapier account to create and manage your Zaps.
- An account with your chosen task management tool (like Trello or Asana).
- An email account that Zapier can send emails to.

## Step-by-step Guide

1. **Set up your trigger**: Log in to your Zapier account and click on 'Make a Zap'. Choose your IoT button as the trigger app and select the 'Button Pressed' trigger event. Follow the prompts to connect your button to Zapier.

2. **Set up your action**: Choose your task management tool as the action app. Select the 'Get Tasks' action event (or similar, depending on the tool). Follow the prompts to connect your task management account to Zapier and set up the action details, such as which board or project to get tasks from.

3. **Set up your second action**: Choose 'Email by Zapier' as your second action app. Select the 'Send Outbound Email' action event. In the 'To' field, enter the email address where you want to receive the digest. In the 'Subject' field, enter something like 'Your Daily Task Digest'. In the 'Body' field, use the 'Add a Field' button to insert the list of tasks from your first action.

4. **Test your Zap**: Click on 'Test & Continue' to make sure everything is working. If the test is successful, you should receive an email with your tasks.

5. **Turn on your Zap**: If everything is working as expected, click on 'Turn on Zap'. Now, whenever you press your button, you should receive an email digest of your tasks for the day.

Remember, you can always go back and edit your Zap if you want to change something. Enjoy your new automated task digest!
