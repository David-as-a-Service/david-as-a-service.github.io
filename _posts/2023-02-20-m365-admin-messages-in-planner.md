---
layout: post
title:  "Keep on top of M365 admin messages with Planner sync"
date:   2023-03-20 10:00:00 -0000
categories: it-ops
---


Microsoft likes to post quite a few product updates each week in the M365 admin centre. Use Planner to help keep on top of things.
Any IT leader knows that updates to the Microsoft 365 suite are non-stop, with new features, bug fixes, changes and service retirements steadily trickling through. 

How many of us are just about managing to keep on top of the stream of messages using the Admin Message Center? It can be tricky and time comsuming, and in larger teams people may be duplicating effort by individually checking these messages. Helpfully there is an integration with Planner, which will sync new messages to a Planner board of your choice.

I use this setup to help keep up with all the changes:

4 buckets:
- To do – new messages arrive here
- Done – completed or messages that don’t require action
- Needs action – we need to do something 
- FYI – good to know for the team, will be left in FYI for a while

Assign tasks to team members responsible for that product area
Use other Planner features like urgency and labels where helpful
Run a semi-frequent review meeting with the team
As with items in the message center, each task created will include the affected product, title, date, type of notification (stay informed, prepare for change…), tags, and description. Messages with due dates will also apply the due date to the task. 

## Set up Planner sync
1. Go to Planner and setup a new Plan for the messages to sync to. You’ll need at least one bucket, which will be chosen as the destination bucket
2. Go to the M365 Admin Message Center: https://admin.microsoft.com/Adminportal/Home#/MessageCenter
3. At the top of the message list, click **Planner syncing**
4. On the pop-out panel click Set up syncing
5. On the Plan page search for the new plan you created by name in step one and choose it
6. Select Use an existing bucket and then use the dropdown to select the bucket, then click **Next**
On the Messages page, select all the categories and product notifications you want to sync, then click **Next**
7. On the Import page decide if you want to import historical messages, click **Next**
8. Confirm the details and click **Finish**

After completing setup you will be asked if you want to use Power Automate to do future syncing to the board for you – I’d recommend setting this up too by setting the time and frequency of the sync you’d like, and then clicking Create flow with Power Automate.