---
ms.technology: devops-agile
ms.author: kaelli
author: KathrynEE
ms.topic: include
ms.date: 07/09/2020
---


## Prerequisites

Boards are automatically created when you create a project or add a team. Each team has access to their own product and portfolio boards as described in [About teams and Agile tools](/azure/devops/organizations/settings/about-teams-and-settings#each-team-gets-their-own-set-of-tools).

::: moniker range="azure-devops"

* You must connect to a project. If you don't have a project yet, [create one](/azure/devops/boards/get-started/sign-up-invite-teammates). 
* You must be added to a project as a member of the **Contributors** or **Project Administrators** security group. To get added, [Add users to a project or team](/azure/devops/organizations/security/add-users-team-project). 
* To add work items and exercise all board features, you must be granted **Basic** access or higher. For details, see [About access levels](/azure/devops/organizations/security/access-levels).
* To view or modify work items, you must have your **View work items in this node** and **Edit work items in this node** permissions set to **Allow**.  By default, the **Contributors** group has this permission set. To learn more, see [Set permissions and access for work tracking](/azure/devops/organizations/security/set-permissions-access-work-tracking).  
* Users with **Stakeholder** access for a private project can't exercise these board features: add work items, drag-and-drop work items to update status, update fields displayed on cards. They can add tasks and change task status. 
* Users with **Stakeholder** access for a public project have full access to board features just like users with **Basic** access. For details, see [About access levels](/azure/devops/organizations/security/access-levels).


::: moniker-end

::: moniker range="< azure-devops"

* You must connect to a project. If you don't have a project yet, [create one](/azure/devops/organizations/projects/create-project).
* You must be added to a project as a member of the **Contributors** or **Project Administrators** security group. To get added, [Add users to a project or team](/azure/devops/organizations/security/add-users-team-project).  
* To add work items and exercise all board features, you must be granted **Basic** access or higher. For details, see [About access levels](/azure/devops/organizations/security/access-levels).
* To view or modify work items, you must have your **View work items in this node** and **Edit work items in this node** permissions set to **Allow**.  By default, the **Contributors** group has this permission set. To learn more, see [Set permissions and access for work tracking](/azure/devops/organizations/security/set-permissions-access-work-tracking).  
* Users with **Stakeholder** access can't exercise these board features: add work items, drag-and-drop work items to update status, or update fields displayed on cards. They can add tasks and change task status. 

::: moniker-end 
 



