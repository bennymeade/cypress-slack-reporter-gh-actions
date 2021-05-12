# cypress-slack-reporter-gh-actions

# Slack Webhook
Create a Slack Incoming Webhook

https://api.slack.com/messaging/webhooks#getting_started

# Add GH Secret
Select: GitHub > Settings > Secrets
Click: New repository secret
- Name: SLACK_WEBHOOK_URL
- Value: {taken from Slack Webhook}

![image](https://user-images.githubusercontent.com/1033474/117925005-ef372680-b2f6-11eb-81ac-5bae93c5d115.png)


# Run Workflow
Select: Actions > Cypress Slack notify > Run workflow > master
Click: Run workflow

![image](https://user-images.githubusercontent.com/1033474/117925042-fd854280-b2f6-11eb-844f-5b279a13a1ec.png)


# Running steps complete:
![image](https://user-images.githubusercontent.com/1033474/117925072-083fd780-b2f7-11eb-9c35-b813716f6d36.png)


# Slack notification:
![image](https://user-images.githubusercontent.com/1033474/117925121-15f55d00-b2f7-11eb-8267-036aaf675a05.png)
