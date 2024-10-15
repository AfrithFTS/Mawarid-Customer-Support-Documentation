![](https://portal.mawarid.com.sa/System/assets/images/mawarid-logo-2.png)

## Mawarid Customer Support Documentation

### Customer Support (Customer Helpdesk)

> ### Introduction

The Customer Support Helpdesk is an essential resource for both customers and coordinators in the company. Our primary goal is to ensure smooth communication and effective support, helping you navigate the complexities of workforce management.

This Customer Support (Customer Helpdesk) application has 7 main menus. They are,

> 1. <a href="#2-tickets">Tickets</a>
> 2. <a href="#1-mails">Mails</a>
> 3. <a href="#3-master">Master</a>
> 4. <a href="#4-customer-setup">Customer Setup</a>
> 5. <a href="#5-task">Task</a>
> 6. <a href="#6-approvals">Approvals</a>
> 7. <a href="#7-all-items">All Items</a>

Each Main menu has some childmenus,

> * Tickets
>   * <a href="#all-tickets">All Tickets</a>
>   * <a href="#my-all-closed-tickets">My All Closed Tickets</a>
>   * <a href="#assigned-to-me">Assigned To Me</a>
>   * <a href="#created-by-me">Created By Me</a>
>
> * Mails
>   * <a href="#new-mail">New Mail</a>
>   * <a href="#inbox">Inbox</a>
>   * <a href="#sent-item">Sent Item</a>
>
> * Master
>   * <a href="#my-customer">My Customer</a>
>   * <a href="#my-projects">My Projects</a>
>   * <a href="#my-signature">My Signature</a>
>
> * Customer Setup
>   * <a href="#customer">Customer</a>
>   * <a href="#project">Project</a>
>   * <a href="#coordinators">Coordinators</a>
>   * <a href="#coordinator-customer">Coordinator Customer</a>
>   * <a href="#coordinator-project">Coordinator Project</a>
>
> * Task
>   * <a href="#my-pending-task">My Pending Task</a>
>   * <a href="#my-completed-task">My Completed Task</a>
>   * <a href="#my-all-task">My All Task</a>
>   * <a href="#me-created-task">Me Created Task</a>
>
> * Approvals
>   * <a href="#my-pending-approvals">My Pending Approvals</a>
>   * <a href="#my-completed-approvals">My Completed Approvals</a>
>   * <a href="#my-all-approvals">My All Approvals</a>
>   * <a href="#me-send-approvals">Me Send Approvals</a>
>
> * All Items (Only for Admin permission)
>   * <a href="#all-ticket">All Ticket</a>
>   * <a href="#all-closed-tickets">All Closed Tickets</a>
>   * <a href="#all-emails">All Emails</a>
>   * <a href="#all-tasks">All Tasks</a>
>   * <a href="#all-approvals">All Approvals</a>

### 1. Tickets

> #### All Tickets 

* This All Ticket menu has shows all of his customer's tickets in the list view.

* These list of tickets are customer's ticket, which those customers are coordinator's (user's) customer.

* It also shows all tickets of his customers which has been in any status.

* This All Ticket menu has the list of tickets, which shows `only particular tickets from the assigned customer` for the user.

* In the Ticket details page, it shows the full details of the ticket and action buttons to process the ticket.

* The action buttons for the new ticket are `Assign, Pickup, Schedule and Close.`

* For each action taken by the user, the `status of the ticket has been changed`.

* The each `status update history` of the ticket is recorded in the Conversation.

* The user can post the comments for the ticket, that comment will `send email notification` to the assigned user. This conversation notification message will go with cc to the both individual who is related to this ticket.

* In the comment box, if the user mention some other users by using `@`, the notification will send to the mentioned user. 

* Here the user can add notes for the ticket, it also will appear in the conversation.

* The ticket assigned user can assign the task to the another user to split the work. It also will receive the `mail notification` to task assigned user.

* The user can send approval request to the higher officials to get any approvals regarding the ticket.

* The task and `approval status history` also will recorded in the conervsation and also in the task and approval tab.

* Here the reply option is available, the user can `send reply` for the ticket to the customer.

* Attachments tab will shows all the list of attachments which is comes from any side of the ticket.

#### Ticket Action Scenarios:

* When a new ticket dropped in the inbox, it was in the `New` status.

* There is some actions available as `assign, pickup, schedule and close`, when the ticket status is new.

* When new ticket has been created, the `email notification` will send it to the customer and coordinator.

* When the ticket assigned to the user, an `assigned user will receive email notification`.

* Also when the user pickup the ticket, he also will receive notification.

* When the user `close or reopen` the ticket, the `customer will receive the email notification` as to inform that his ticket has been closed or reopened.

* When someone assign or pickup the ticket, there is `no status change` happens.

* If the user schedule the ticket, the new ticket status has been `changed into Scheduled`.

* After the ticket has been scheduled, there is a new `start action` will be available.

* If the user click the start action, the scheduled status ticket will changed into `Inprogress status`.

#### Email Notifications:

* When the `new ticket` has been created, the email notification will send it to the `Customer and the Coordinator.`

* If the ticket has been `assigned or pickup` by someone, the `assigned person will receive the email notification` as he was assigned to the ticket.

* If the ticket has been `assigned as a task` to the user, the `assigned user will received the email notification.`

* If `any status change` may happens by the task assigned user, the `email notification will received by the task creator.`

* Same as like in the approval also, if the ticket has been `send for the approval, the approver will receive the email notification.`

* That approver will take `any actions, the approval sender will receive the notification.`

* Also in the comment section for the both task and in approvals, if any comment made by the `task assigned user or the approver, the creator will receive notification.`

* If the creator/sender made a comments in `task or approvals, the assigned person or approver will receive notification.`

* This `comment email notification` is also applicable for the `ticket details conversation` comments area.

> #### My All Closed Tickets

* My All Closed Tickets has shows the lists of closed tickets.

* These Closed tickets are customer's ticket which has been closed by the coordinator (user).

> #### Assigned To Me

* The Assigned To Me menu page shows the tickets, which the tickets are assigned for the user, whether the tickets are created by other user or by him is doesn't matter.

* If the user has pickup any ticket, it also consider as assigned to him. So, those tickets also will show in the list.

> #### Created By Me

* This Created By Me menu page shows the list of tickets only it's all created by the user.

* It shows all the tickets which is only created by the user, whether the tickets are in any status.

* No other differences are there comparing to previous menus as Assigned To Me and All Tickets. Functionalities are same as Inbox, only the data is different which is depends on the user.

### 2. Mails

> #### New Mail

* This New Mail menu is a popup to `send email (creating ticket through email)` by selecting Customer (From) in dropdown who has assigned for the particular user.

* This is an `Internal mail send to create ticket` within the application.

> #### Inbox

* This Inbox menu shows the list of all mails came in through his support mail.

* This mail inbox menu is just a list view to see the incoming mails separately like outlook or gmail.

> #### Sent Item

* In the Sent Item menu, it shows the list of all mails gone through the system.

* This Sent item menu is just a list view to see the outgoing mails separately like outlook or gmail.

### 3. Master

> #### My Customer

* This is the My Customer menu, it shows the lists of customers which is assigned for the user.

* To view the customer details, click the customer code.

> #### My Projects

* This My Projects menu shows the lists of projects, which has been assigned for his customer and projects.

* To view the project details, click the project code.

> #### My Signature

* This My Signature menu is the setup of signature content, while sending email with signature.

* The user can edit the Signature.

### 4. Customer Setup

This Customer Setup menu has the setup menus, to setup the customers, projects, coordinators, coordinators customer and coordinators project. The Customer and Project menu shows all the customers and project lists, it's only for the view.

> #### Customer

* This Cutsomer menu is the purpose of creating customers with the support mail.

* This customer list shows all the customers not only the user's customers.

* This Customer menu shows the fields of `Customer code, Short Name, Name, Support Email, Project Supervisor, Owner and Account.`

* To view the customer details, click the customer code in the list.

* And this customer details page also shows the `projects that have been assigned for the customer`, even a new project has also able to create for the customer here.

* Here the user can able to `edit and delete` the customer and it's details.

> #### Project

* This Project menu is the purpose of `creating projects.`

* This Project list shows all the projects, not only the `user's customer assigned project.`

* Projects list shows the data on the fields of `Project Id, Project Code, Project Name, Project Type, Contract Type, Customer Code and Customer Name.`

* Click the RecId in the table to view the project details.

* Here the user can able to `edit and delete` the project and it's details.

> #### Coordinators

* This Coordinators menu has the purpose of `creating coordinators.`

* This Coordinators menu shows the `list of all coordinators.`

* Coordinators lists shows the data on the fields of `User Id, Name, Email, Mobile and Signature of the Coordinators.`

* To view the details of the coordinators, click the User Id.

* In the Coordinators details page, it shows the `coordinator's customers and it's projects list.`

* Here the user can easily assign customers and projects for the coordinators in that particular coordinator's details page.

* And the user can able to edit only the coordinator's signature, not the details of coordinators because this datas are coming from the CRM.

* The user can delete the coordinators only here in the list.

> #### Coordinator Customer

* This Coordinator Customer menu has shows the list of all Coordinators and their customers.

* This list has shows the datas on the fields of Coordinator's User Id, Coordinator Name, Coordinator Email, Coordinator Mobile Number, Customer Code and Customer Name.

* This Coordinator Customer menu page is just for the view of the coordinators and their customers pairly. No other actions can take here.

> #### Coordinator Project

* This Coordinator Project menu has shows the list of all Coordinators and their Customers and Projects.

* This list has shows the datas on the fields of Coordinator's User Id, Coordinator Name, Coordinator Email, Coordinator Mobile Number, Customer Code, Customer Name, Project Code and Project Name.

* This Coordinator Project menu page is just for the view of the coordinators and their customers and projects pairly. No other actions can take here.

### 5. Task

> #### My Pending Task

* My Pending Task menu page shows the list of tasks in card view, which is assigned for me (user), need to take action.

* To view the details of the task, click the Task Id in the card view and the details page of task will open in side view.

* Every actions of the task taken will be recorded in the convesation.

* Here the user can take action for the task as Doing and Done.

* After the user Done the task, it will move to the next menu "My Completed Task".

> #### My Completed Task

* My Completed Task menu page shows the list of completed tasks in the card view, which is assigned for me (user) and completed.

* To view the details of the task, click the Task Id in the card view and the details page of task will open in side view.

* This menu has only list of completed tasks which is assigned of the user.

> #### My All Task

* My All Task menu page shows the list of all tasks in the card view, which is assigned for me (user) even it is in any status.

* To view the details of the task, click the Task Id in the card view and the details page of task will open in side view.

> #### Me Created Task

* Me Created Task menu page shows the list tasks in the card view, which the tasks are created by me (user).

* Here the user can see his created task's status in this menu.

* To view the details of the task, click the Task Id in the card view and the details page of task will open in side view.

### 6. Approvals

> #### My Pending Approvals

* My Pending Approvals menu page shows the list of approvals in card view, which is assigned for me (user), need to take action.

* To view the details of the approval, click the Approval Id in the card view and the details page of approval will open in side view.

* Every actions of the approval taken will be recorded in the convesation.

* Here the user can take action for the approval as Approve or Reject.

* After the user take action on approval, it will move to the next menu "My Completed Approvals".

> #### My Completed Approvals

* My Completed Approvals menu page shows the list of completed approvals in the card view, which is assigned for me (user) and completed.

* To view the details of the approval, click the Approval Id in the card view and the details page of approval will open in side view.

* This menu has only list of completed approvals which is assigned of the user.

> #### My All Approvals

* My All Approvals menu page shows the list of all approvals in the card view, which is assigned for me (user) even it is in any status.

* To view the details of the approval, click the Approval Id in the card view and the details page of approval will open in side view.

> #### Me Send Approvals

* Me Send Approvals menu page shows the list approvals in the card view, which the approvals are created by me (user).

* Here the user can see his created approval's status in this menu.

* To view the details of the approval, click the Approval Id in the card view and the details page of approval will open in side view.

### 7. All Items

> #### All Ticket

* This All Ticket menu has shows all the tickets in the list view.

* In this menu, it shows all tickets which has been created by all the users in the customer support.

* It also shows all tickets which the tickets has been in any status.

> #### All Closed Tickets

* This All Closed Tickets menu has shows all the closed tickets in the list view.

* In this menu, it shows all closed tickets which the tickets of all the customers.

* This closed tickets menu is a table view to see all closed tickets separately.

> #### All Emails

* All Emails menu has shows the list of emails in the list view.

* This menu has shows all incoming mails & outgoing mails of all coordinators and customers email.

> #### All Tasks

* This All Tasks menu has shows the list of tasks in the list view.

* This menu has shows all the tasks list which is created by all the users in the entire customer support.

> #### All Approvals

* This All Approvals menu has shows the list of approvals in the list view.

* This menu has shows all the approvals list which is created by all the users in the entire customer support.