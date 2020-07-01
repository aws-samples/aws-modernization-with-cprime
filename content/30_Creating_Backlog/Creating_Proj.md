---
title: "Create a Project"
chapter: false
weight: 31
---

Before creating a project, you’ll need to decide what kind of project to create.  Jira is quite flexible in the kinds of projects that can be managed.  A basic Jira project can be a simple set of tasks that are worked on and completed.  But Jira can also be used for projects with complex workflows and multiple distinct types of activities.  

In this workshop, you will create a project that uses the Agile methodology—specifically, a Scrum project—which shows off some neat features of Jira.  If you are not familiar with Scrum, that’s okay.  

If you haven’t already done so, log into Jira.  Along the top menu bar, click on the **“Projects”** menu bar, and select **“Create Project”**.

![Create_proj_menu](/images/30_Creating_Backlog/Create_proj_menu.png)

A **“Create Project”** dialog will pop up.  Select the **“Scrum software development”** project type.  

![Create_proj_dialog](/images/30_Creating_Backlog/Create_proj_dialog.png)

Click **“Next”**.

The dialog now shows the issue types and workflow for the project.  This is informational, and we’ll come back to explaining these later in the workshop.  

![Create_proj_dialog_flow](/images/30_Creating_Backlog/Create_proj_dialog_flow.png)

Click **“Select”** to proceed.

The next page is a form to enter the project details:

- **Name** – A short name for the project.  You can enter a name of your choice, but the examples in this workshop will use the name **“Courtyard Improvement”**.  
- **Key** – A unique key for the project.  When you enter the name, Jira will automatically generate a suggested key, but you can optionally change it.    
- **Project Lead** – The person who will lead the project.  In some project configurations, this person could have extra permissions.  Jira will automatically set you (the logged in user) as the lead, but you can select a different user if you want.  Start typing the name “J” and see that Jira auto suggests a user.  Select the suggested user **“Jordan”**.

![Create_proj_dialog_form](/images/30_Creating_Backlog/Create_proj_dialog_form.png)

Once you have filled in the project details, click **“Submit”**.

Congratulations!  You now have a project, albeit an empty one.
