# Notification on Modification / Upload / Change / Deleting a blob in Container

This demonstration includes a workflow whenever the blob is updated or added it sends an e-mail. This will explain the idea of establishment of connectors and gives the basic workflow to decide the possible actions when a trigger is occurred.

1.  Login to Microsoft Azure portal: [Azure Portal](https://portal.azure.com/ "Azure Portal")
2.  Create a Storage account. The storage account must have a container . Refer the [How to Create Azure Storage Account] for Storage Account creation. The overview of storage account is as shown below.

3.  Create a Logic app. Refer the [How to Create Azure Logic App] for the Logic App creation. The overview of Logic app is as shown below.

4.  In the designer template choose Blank Template. 
5.  Inside the template search bar search & select Azure Blob Storage. Select the trigger as blob added or modified
 

6.	Provide the connection name and choose the storage account. Click on create. 
7.	Select the Container 
 
8.	Select next step and choose Office 365 plugin. Choose option as ‘Select an email’.
 
9.	Sign in with the outlook email account.
 
10.	Fill the details like body, subject to whom the notification should receive it. Save the workflow and run it
 
Once the logic app starts running, the person will receive a notification e-mail on the basis of modifying/update of the blob.
