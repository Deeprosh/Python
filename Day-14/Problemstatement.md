# `Automate JIRA Creation on a Github Event using Python`  
## Problem statement:  
### QE enigneer found a bug/issue in github if the issue is valid the development team will work if not they can close the ticket.If the issue is valid they need to login to JIRA and have to create a ticket. 
### Instead they will check with devops team to automate this jira ticket creation task whenever someone comments on github issue as jira is needed.  
### Inorder to create a bridge between JIRA and github to do this task we will ask the github to send us webhook by mentioning what we have done using python to automate the task by using EC2.
### So this EC2 gets the webhook gets the JSON format and redirects to jira as request ticket whenever someone comments on github issues saying JIRA.
