# slackNotification
A script to git actions to when main branch receive push notify on slack channel by slack webhook

# how to use

### Step 1: Create a Slack Incoming Webhook
Go to your Slack workspace and create a new app:

Visit Slack API: Create a new app.
Select "From scratch," give the app a name, and choose a workspace.
Add an Incoming Webhook to your Slack app:

In the app settings, click on "Incoming Webhooks."
Click "Activate Incoming Webhooks."
Click "Add New Webhook to Workspace" and choose the channel where the bot should post the message.
Save the webhook URL (you'll need it in the GitHub Action).

### Step 2: Create a GitHub Action
In your GitHub repository, you'll create a GitHub Action that triggers when a push occurs to the main branch on ``.github/workflows ``.
