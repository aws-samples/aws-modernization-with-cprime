---
title: "Create a Bug"
chapter: false
weight: 82
---

Work is humming along on your project.  For the “Gnome” story, Kai is in the process of placing the gnome Slevenbirt in the garden.  But then Kai notices something unusual.  There are bushes obscuring the location for the gnome.  The gnome won’t be able to keep watch over the garden with bushes in the way.  

Trimming the bushes is not part of the story, and taking time to properly prune the bushes would add a delay to completing the story.  What should you do?

{{% notice note %}}
**Bug versus Defect Subtask**  
</br>
When a problem is found during implementation or validation of a story, additional work to remediate the problem is often required.  That remediation can be done either as part of the story or as work done later.  
</br>
If the problem is critical to completion of the story, then a new sub-task should be added to the story.  This can be referred to as a “defect subtask” for the story.  
</br>
If the problem is not critical to completion of the story—that is, the story could reasonably be considered completed even in the presence of the found problem—then the remediation should be done later.  In this case, a bug is added to the project backlog to be worked on in a future sprint. 
{{% /notice %}}

In the case of bushes obscuring the gnome in your garden, you decide that pruning the bushes is not fundamentally part of placing the gnome in the garden.  As a result, you decide to create a bug for the project backlog.  Let’s do that now.  

Click the **Create** button at the top of Jira.  In this case, we will want **Issue Type** to be **"Bug"**.

![Bug_dialog_top](/images/80_Collaboration/Bug_dialog_top.png)

Fill out the relevant information for the bug:

- **Summary** – Enter the problem statement: “The gnome should be clearly visible from all parts of the garden”.  
- **Reporter** – Leave this as yourself.  
- **Description** – A good bug description includes the following information:  
  - A reproducible scenario under which the problem can be observed: “Stand near the fern flower patch in the garden and look toward gnome.”  
  - The expected result: “The gnome should be completely visible.”
  - The actual result: “The gnome is obscured behind bush growth.”
- **Epic** – Be sure to select the “Garden Refresh” epic.

![Bug_dialog_completed](/images/80_Collaboration/Bug_dialog_completed.png)

Click **Create** to create the bug.  The bug should show up on the project backlog. _(Click **Backlog** in the left navigation area if the backlog is not currently showing.)_

![Proj_page_bug_backlog](/images/80_Collaboration/Proj_page_bug_backlog.png)

The bug is now a candidate work item for the next or future sprint.  Just like a story, your team will estimate its effort in story points.
