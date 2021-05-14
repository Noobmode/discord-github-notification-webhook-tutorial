# discord-github-notification-webhook-tutorial
## Overview
Instructions and walk through for setting up a webhook in discord for github notifications

## Challenge
A notification webhook is needed in a discord space for keeping all channel members in the loop regarding changes to a target repository

## Solution
1. Create your desired Discord channel and Github repository
2. Open the repository and go to the settings page

![Repo settings](./images/1.png)

3. Select "Webhooks" from the left menu panel, click the "Add Webhook" button on the right side

![Webhook page](images/2.png)

4. You will need the "Payload URL" from Discord explained in the next steps, the "Content type" set to "application/json", and which events you wish to receive 

![Webhook Github settings](images/3.png)

5. To retrieve the "Payload URL", choose your desired "Channel" in Discord. Click the "Gear" to the right of the channel name to enter the "Settings" blade.

![Channel settings gear](images/4.png)

6. Select the "Integrations" option, on the "Integrations" blade click "Create Webhook"

![Discord Integrations blade](images/5.png)

7. Name the bot accordingly, hit "Copy Webhook URL", and "Save Changes". Notice the bottom left shows I have not saved in the screen shot.
   
![Discord Webhook bot settings](images/6.png)

8. Paste the copied URL from step 7 into the GitHub wekbhook page from Step 3. Check your settings. Hit "Add Webhook".
   
![Webhook Github settings filled](images/7.png)

9. You should now see in Github and Discord the Webhook and bot like the screen shots below

![Webhook Github list](images/8.png)
![Discord Webhook bot list](images/9.png)

10. Now when you meet the event requirements for the webhook, you should receive the notification in discord.

11. Enjoy your webhook!