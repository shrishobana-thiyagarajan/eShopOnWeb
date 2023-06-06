# eShopOnWeb
Agile Planning and Portfolio Management with Azure Boards 

 

Lab overview - AZ400_M01_L01 

 

In this lab, you’ll learn about the agile planning and portfolio management tools and processes provided by Azure Boards and how they can help you quickly plan, manage, and track work across your entire team. You’ll explore the product backlog, sprint backlog, and task boards that can track the flow of work during an iteration. We’ll also look at the enhanced tools in this release to scale for larger teams and organizations. 

 

Objectives 

After you complete this lab, you will be able to: 

Manage teams, areas, and iterations. 

Manage work items. 

Manage sprints and capacity. 

Customize Kanban boards. 

Define dashboards. 

Customize team process. 

 

Instructions 

Exercise 0: Configure the lab prerequisites 

 

In this exercise, you will set up the prerequisites for the lab, which consist of a new Azure DevOps project with a repository based on the eShopOnWeb. 

Task 1: (skip if already done) Create and configure the team project 

In this task, you will create an eShopOnWeb Azure DevOps project to be used by several labs. 

On your lab computer, in a browser window open your Azure DevOps organization. Click on New Project. Give your project the name eShopOnWeb. Define Private as Visibility option. 

Click Advanced and specify Scrum as Work Item Process. Click on Create. 

 

Exercise 1: Manage Agile project 

 

In this exercise, you will use Azure Boards to perform a number of common agile planning and portfolio management tasks, including management of teams, areas, iterations, work items, sprints and capacity, customizing Kanban boards, defining dashboards, and customizing team processes. 

 

Task 1: Manage teams, areas, and iterations 

 

Verify that the web browser displays your Azure DevOps organization with the EShopOnWeb project you generated in the previous exercise. 

your-Azure-DevOps-account-name>/EShopOnWeb 

  Click the cogwheel icon labeled Project settings located in the lower left corner of the page to open the Project settings page. 

In the General section, select the Teams tab. There is already a default team in this project, EShopOnWeb Team but you’ll create a new one for this lab. Click New Team. 

On the Create a new team pane, in the Team name textbox, type EShop-Web, leave other settings with their default values, and click Create. 

In the list of Teams, select the newly created team to view its details. 

Click Iterations and Area Paths link at the top of the EShop-Web page to start defining the schedule and scope of the team. 

At the top of the Boards pane, select the Iterations tab and then click + Select iteration(s). 

Select EShopOnWeb\Sprint 1 and click Save and close. Note that this first sprint will show up in the list of iterations, but the Dates are not set yet. 

Select Sprint 1 and click the ellipsis (…). From the context menu, select Edit. 

Repeat the previous step to add Sprint 2 and Sprint 3. You could say that we are currently in the 2nd week of the first sprint. 

Back on the Boards pane, at the top of the pane, select the Areas tab. You will find there an automatically generated area with the name matching the name of the team. 

Click the ellipsis symbol (…) next to the default area entry and, in the dropdown list, select Include sub areas. 

Task 2: Manage work items 

 

In the vertical navigational pane of the Azure DevOps portal, select the Boards icon and, select Work Items. 

On the Work Items window, click on + New Work Item > Epic. 

In the Enter title textbox, type Product training. 

In the upper left corner, select the Unassigned entry and, in the dropdown list, select your user account in order to assign the new work item to yourself. 

Next to the Area entry, select the eShopOnWeb entry and, in the dropdown list, select EShop-WEB. This will set the Area to eShopOnWeb\EShop-WEB. 

Next to the Iteration entry, select the eShopOnWeb entry and, in the dropdown list, select Sprint 2. This will set the Iteration to eShopOnWeb\Sprint 2. 

Click Save to finalize your changes. Do not close it. 

In the Related work section on the lower right-side, select the Add link entry and, in the dropdown list, select New item. 

On the Add link panel, in the Link Type dropdown list, select Child. Next, in the Work item type dropdown list, select Feature, in the Title textbox, type Training dashboard and click OK. 

On the Training dashboard panel, click Save & Close. 

In the vertical navigation pane of the Azure DevOps portal, in the list of the Boards items, select Boards. 

On the Boards panel, select the EShop-WEB boards entry. This will open the board for that particular team. 

On the Boards panel, in the upper right corner, select the Backlog items entry and, in the dropdown list, select Features. 

Hover with the mouse pointer over the rectangle representing the Training dashboard feature. This will reveal the ellipsis symbol (…) in its upper right corner. 

Click the ellipsis (…) icon and, in the dropdown list, select Add Product Backlog Item. 

In the textbox of the new product backlog item, type As a customer, I want to view new tutorials and press the Enter key to save the entry. 

Repeat the previous step to add two more PBIs designed to enable the customer to see their recently viewed tutorials and to request new tutorials named, respectively, As a customer, I want to see tutorials I recently viewed and As a customer, I want to request new tutorials. 

Repeat the previous step to add two more PBIs designed to enable the customer to see their recently viewed tutorials and to request new tutorials named, respectively, As a customer, I want to see tutorials I recently viewed and As a customer, I want to request new tutorials. 

On the Board tab of the EShop-WEB panel, drag the first work item named As a customer, I want to view new tutorials from the New to Approved stage. 

Hover with the mouse pointer over the rectangle representing the work item you moved to the Approved stage. This will reveal the down facing caret symbol. 

Click the down facing caret symbol to expand the work item card, select the Unassigned entry, and in the list of user accounts, select your account to assign the moved PBI to yourself. 

On the Board tab of the EShop-WEB panel, drag the second work item named As a customer, I want to see tutorials I recently viewed from the New to the Committed stage. 

On the Board tab of the EShop-WEB panel, drag the third work item named As a customer, I want to request new tutorials from the New to the Done stage. 

On the Board tab of the EShop-WEB panel, at the top of the pane, click View as Backlog to display the tabular form. 

On the Backlog tab of the EShop-WEB panel, in the upper left corner of the pane, click the second plus sign from the top, the one next to the first work item. This will display the NEW TASK panel. 

At the top of the NEW TASK panel, in the Enter title textbox, type Add page for most recent tutorials. 

On the NEW TASK panel, in the Remaining Work textbox, type 5. 

On the NEW TASK panel, in the Activity dropdown list, select Development. 

On the NEW TASK panel, click Save & Close. 

Repeat the last five steps to add another task named Optimize data query for most recent tutorials. Set its Remaining Work to 3 and its Activity to Design. Click Save & Close once completed. 

Task 3: Manage sprints and capacity 

 

1. In the vertical navigational pane of the Azure DevOps portal, select the Boards icon and, in the list of the Boards items, select Sprints. 

2. On the Taskboard tab of the Sprints view, in the toolbar, on the right hand side, select the View options symbol (directly to the left of the funnel icon) and, in the View options dropdown list, select the Work details entry. 

3. In the rectangle representing the Add page for most recent tutorials, click the Unassigned entry and, in the list of user accounts, select your account to assign the task to yourself. 

4. Select the Capacity tab of the Sprints view. 

5. On the Capacity tab of the Sprints view, directly under the Activity label, in the Unassigned dropdown list, select Development and, in the Capacity per day textbox, type 1. 

6. On the Capacity tab of the Sprints view, directly next to the entry representing your user account, in the Days off column, click the 0 days entry. This will display a panel where you can set your days off. 

7. In the displayed panel, use the calendar view to set your vacation to span five work days during the current sprint (within the next three weeks) and, once completed, click OK. 

8. Back on the Capacity tab of the Sprints view, click Save. 

9. Select the Taskboard tab of the Sprints view. 

10. On the Taskboard tab of the Sprints view, in the square box representing the Add page for most recent tutorials, set the estimated number of hours to 14, to match your total capacity for this sprint, which you identified in the previous step. 
11. On the Taskboard tab of the Sprints view, in the toolbar, on the right hand side, select the View options symbol (directly to the left of the funnel icon) and, in the View options dropdown list, select the People entry. 

12. Click the Configure team settings cogwheel icon (directly to the right of the funnel icon). 

13. On the Settings panel, select the Styles tab, click + Styling rule, under the Rule name label, in the Name textbox, type Development, and, in the Card color dropdown list, select the green rectangle. 

14. In the Rule criteria section, in the Field dropdown list, select Activity, in the Operator dropdown list, select =, and, in the Value dropdown list, select Development. 

 
15. On the Settings panel, select the Backlogs tab. 

16. On the Settings panel, select the Working days tab. 

17. On the Settings panel, select the Working with bugs tab. 

18. On the Settings panel, click Save and close to save the styling rule. 

 

Task 4: Customize Kanban boards 

 

In the vertical navigational pane of the Azure DevOps portal, in the list of the Boards items, select Boards. 

On the Boards panel, click the Configure team settings cogwheel icon (directly to the right of the funnel icon). 

On the Settings panel, select the Tag colors tab, click + Tag color, in the Tag textbox, type data and leave the default color in place. 

On the Settings panel, select the Annotations tab. 

On the Settings panel, select the Tests tab. 

On the Settings panel, click Save and close to save the styling rule. 

On the Board tab of the EShop-WEB panel, right-click the Work Item representing the As a customer, I want to view new tutorials backlog item and select Open. 

On the As a customer, I want to view new tutorials panel, at the top of the panel, to the right of the 0 comments entry, click Add tag. 

In the resulting textbox, type data and press the Enter key. 

Repeat the previous step to add the ux tag. 

On the As a customer, I want to view new tutorials panel, click Save & Close. 

On the Boards panel, click the Configure team settings cogwheel icon (directly to the right of the funnel icon). 

On the Settings panel, select the Columns tab. 

Click + Column, under the Column name label, in the Name textbox, type QA Approved and, in the WIP limit textbox, type 1. 

On the Settings panel, on the Columns tab, drag and drop the newly created tab between Committed and Done. 

On the Settings panel, click Save and close. 

Refresh the Boards portal, so the QA Approved4 column is visible in the Kanban board view now. 

Drag the As a customer, I want to see tutorials I recently viewed work item from the Committed stage into the QA Approved stage. 

Drag the As a customer, I want to view new tutorials work item from the Approved stage into the QA Approved stage. 

Move the As a customer, I want to see tutorials I recently viewed backlog item back to Committed. 

On the Boards panel, click the Configure team settings cogwheel icon (directly to the right of the funnel icon). 

On the Settings panel, return to the Columns tab and select the QA Approved tab. 

On the QA Approved tab, enable the Split column into doing and done checkbox to create two separate columns. 

On the QA Approved tab, at the bottom of the panel, in the Definition of done textbox, type Passes **all** tests. 

On the Settings panel, click Save and close. 

On the Boards panel, click the Configure team settings cogwheel icon (directly to the right of the funnel icon). 

On the Settings panel, select the Swimlanes tab. 

On the Swimlanes tab, click + Swimlane, directly under the Swimlane name label, in the Name textbox, type Expedite. 

On the Settings panel, click Save and close. 

Back on the Board tab of the Boards panel, drag and drop the Committed work item onto the QA Approved | Doing stage of the Expedite swimlane so that it gets recognized as having priority when QA bandwidth becomes available. 

 

Task 5: Customize team process 

 

 

On the Azure DevOps page, click the Azure DevOps logo in the top left corner to navigate to the account root page. 

In the left bottom corner of the page, click Organization settings. 

In the Organization Settings vertical menu, in the Boards section, select Process. 

On the All processes pane, to the right of the Scrum entry, select the ellipsis symbol (…) and, in the dropdown menu, select Create inherited process. 

In the Create inherited process from Scrum panel, in the Process name (required) textbox, type Customized Scrum and click Create process. 

Back on the All processes pane, click the Customized Scrum entry. 

On the All processes > Customized Scrum pane, select Product Backlog Item. 

On the All processes > Customized Scrum > Product Backlog Item pane, click New field. 

On the Add a field to Product Backlog Item panel, on the Definition tab, in the Create a field section, in the Name textbox, type EShop Ticket ID. 

On the Add a field to Product Backlog Item panel, click Layout. 

On the Add a field to Product Backlog Item panel, on the Layout tab, in the Label textbox, type Ticket ID, select the Create a new group option, in the Group textbox, type EShopOnWeb, and click Add field. 

Return to the All processes root using the breadcrumb path at the top of the All processes > Customized Scrum > Product Backlog Item pane. 

On the All processes pane, select the Scrum entry. 

On the All processes > Scrum pane, select the Projects tab. 

In the list of projects, in the row containing the eShopOnWeb entry, select the ellipsis symbol (…) and then select Change process. 

On the Change the project process pane, in the Select a target process dropdown list, select the Customized Scrum process, click Save and then click Close. 

Click the Azure DevOps logo in the top left corner to return to the account root page. 

On the Projects tab, select the entry representing the eShopOnWeb project. 

In the vertical menu on the left side of the eShopOnWeb page, select Boards and ensure that the Work Items pane is displayed. 

In the list of work items, click the first backlog item. 

Verify that you now have the Ticket ID field under the PartsUnlimited group, which was defined during the process customization. You can treat this like any other text field. 

 

Exercise 2 (optional) : Define dashboards 

 

In the vertical navigational pane of the Azure DevOps portal, select the Overview icon and, in the list of the Overview items, select Dashboards. 

If necessary, on the Dashboards pane, in the upper left corner, in the eShopOnWeb Team section, select eShopOnWeb Team - Overview and review the existing dashboard. 

On the Dashboards pane, select the drop-down menu next to the eShopOnWeb Team - Overview title, and select + New dashboard. 

On the Create a dashboard pane, in the Name textbox, type Product training, in the Team dropdown list, select the EShop-WEB team, and click Create. 

On the new dashboard pane, click Add a widget. 

On the Add Widget panel, in the Search textbox, type sprint to find existing widgets that focus on sprints. In the list of results, select Sprint Overview and click Add. 

In the rectangle representing the newly added widget, click the Settings cogwheel icon and review the Configuration pane. 

On the Configuration pane, click Close without making any changes. 

Back on the Add Widget pane, in the Search textbox, type sprint again to find existing widgets that focus on sprints. In the list of results, select Sprint Capacity and click Add. 

In the Dashboard view, at the top of the pane, click Done Editing. 

In the vertical navigational pane of the Azure DevOps portal, select the Boards icon and, in the list of the Boards items, select Queries. 

On the Queries pane, click + New query. 

On the Editor tab of Queries > My Queries pane, in the Value dropdown list of the Work Item Type row, select Task. 

On the Editor tab of Queries > My Queries pane, in the second row, in the Field column, select Area Path and, in the corresponding Value dropdown list, select eShopOnWeb\EShop-WEB. 

Click Save query. 

In the New query panel, in the Enter name textbox, type Web tasks, in the Folder dropdown list, select Shared Queries, and click OK. 

Select the Charts tab and click + New chart. 

On the Configure Chart panel, in the Name textbox, type Web tasks - By assignment, in the Group by dropdown list, select Assigned To, and click OK to save the changes.

Review 

In this lab you used Azure Boards to perform a number of common agile planning and portfolio management tasks, including management of teams, areas, iterations, work items, sprints and capacity, customizing Kanban boards, defining dashboards, and customizing team processes. 

 

 

 

 

 

 

 
