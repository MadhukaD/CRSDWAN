# CRSDWAN
CRSDWAN is a simple dashboard built for the SDWAN department in Sri Lanka Telecom. Through this dashboard, the users will be able to manage the Change Requests (CRs) they get from their enterprise customers.

## User types
There are two user types: **Admin users** and **Non-Admin users**

- Admin users - These users have the admin privileges over the web application.
>> Capeabilities - Can perform all the functionalities of the web app.

- Admin users - These users have limited access over the web application.
>> Capeabilities - Can perform basic functionalities of the web app (Export Data, Download & View files, View description, View the approval status, Select stages in Actions, Add & View comments).

## Functionalities of the web application

- Add User - An Admin user can add another user (Admin or Non-Admin) to the system.
- Add Customer - Users can add their customers to the system.
- Add Team - Users can add teams to the system (types of customers).
- Add CR Type - Users can add types of the Change Requests.
- Add CR - Users can submit a Change Request.
- Export Data - Users can download the data on a selected date range.
- Dashboard - View real-time information of the submitted CRs such as CR's status, Elapsed time, Comments, etc.

Dashboard has several functionalities that users can perform.

- Files: Users can add files (Can be a text file or an image) related to the Change Request, and delete, view or download them.
- Description - Users can view the description added when submitting the Change Request.
- Mark Approval - Admin users can approve the CR and other users can only view the approval status.
- Actions - In a Change Request process, there are four stages; Assigned, WIP (Work In Progress), Request Info and Completed. Users can update the CR progress by selecting the appropriate stage.
- Comments - Users can add comments on a Change Request as well as view all the comments for that Change Request.
- Delete CR - Admin users can delete CRs where CR progress = Completed.
