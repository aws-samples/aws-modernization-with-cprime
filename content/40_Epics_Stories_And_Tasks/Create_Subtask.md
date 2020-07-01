---
title: "Add Subtasks"
chapter: false
weight: 44
---

At this point, you have a story in Jira that defines the requirements for what the team is to deliver when implementing the story.  How the team is to go about implementing the story is yet to be defined.  

For the team to work on a story, the story is decomposed into a set of sub-tasks, which specify the activities the team members need to perform to implement and validate the story.  Sub-tasks are the units of work that will tracked as a story goes through implementation.  

The point in a story lifecycle when it is decomposed into sub-tasks is dependent on the team.  Some teams create subtasks when defining a story, other teams wait until a story is actually included in a sprint. For this workshop, we will do sub-task decomposition now.  

For the **“Gnome”** story, your team has identified three sub-tasks required to implement the story:  

- Remove broken urn from garden

- Retrieve gnome from Old Gnome Home

- Place gnome where urn used to be

Let’s create the sub-tasks in Jira.  

On the project backlog view, click on the story in the backlog list to show the story details on the right of the page.  At the top of the story details panel, is the unique key for the story, which is a clickable link to open the full story details page.

![Story_details_link](/images/40_Epics_Stories_And_Tasks/Story_details_link.png)

On the full story details page, click on the **“More”** button, and then select **“Create sub-task”**.

![Story_more_menu](/images/40_Epics_Stories_And_Tasks/Story_more_menu.png)

You will now see the **“Create Subtask”** dialog.  Confirm that the selected issue type is “Sub-task.  Then fill in the relevant information in the form:  

- **Summary** – Enter the name of the sub-task from the team’s sub-task decomposition above.  
- **Reporter** – Leave as yourself.  
- **Description** – Write a short description on what the task entails.  

![Subtask_dialog](/images/40_Epics_Stories_And_Tasks/Subtask_dialog.png)

Make sure the checkbox **“Create another”** is ticked at the bottom of the dialog.  Click **“Create”** to create the sub-task.  A new empty sub-task dialog will appear with a message that the prior sub-task was created.  Create the second and third sub-tasks for the story.  (Untick **“Create another”** before clicking **“Create”** for the third sub-task.  But if you forget, you can just cancel out of creating a fourth sub-task.)

You should now see the three subtasks on the story details page.

![Story_with_subtasks](/images/40_Epics_Stories_And_Tasks/Story_with_subtasks.png)

{{% notice tip %}}
On the story page, the sub-tasks can be re-ordered if necessary by dragging and dropping the subtasks into the desired order.
{{% /notice %}}  
