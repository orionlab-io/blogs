# Notification on Modification / Upload / Change / Deleting a blob in Container

This demonstration includes a workflow whenever the blob is updated or added it sends an e-mail. This will explain the idea of establishment of connectors and gives the basic workflow to decide the possible actions when a trigger is occurred.

1.  Login to [Microsoft Azure Portal](https://portal.azure.com/ "Microsoft Azure Portal")
    
2.  Create a Storage account. The storage account must have a container . Refer the [How to Create Azure Storage Account] for Storage Account creation. The overview of storage account is as shown below.

  ![Azure Portal](https://github.com/orionlab-io/blogs/blob/main/Azure%20Logic%20Apps/Images/azure-portal.png)

3.  Create a Logic app. Refer the [How to Create Azure Logic App] for the Logic App creation. The overview of Logic app is as shown below.

  ![Azure Logic Designer](https://github.com/orionlab-io/blogs/blob/main/Azure%20Logic%20Apps/Images/azure-logic.png)
    
4.  In the designer template choose Blank Template. 

5.  Inside the template search bar search & select Azure Blob Storage. Select the trigger as blob added or modified
 
 ![Azure Logic Designer](https://github.com/orionlab-io/blogs/blob/main/Azure%20Logic%20Apps/Images/azure-logic-designed.png)

6.	Provide the connection name and choose the storage account. Click on create. 

 ![Azure Logic Designer](https://github.com/orionlab-io/blogs/blob/main/Azure%20Logic%20Apps/Images/choose-connecttion.png)

7.	Select the Container 
 
 ![Azure Logic Designer](https://github.com/orionlab-io/blogs/blob/main/Azure%20Logic%20Apps/Images/select-container.png)
 
8.	Select next step and choose Office 365 plugin. Choose option as ‘Select an email’.

![Azure Logic Designer](https://github.com/orionlab-io/blogs/blob/main/Azure%20Logic%20Apps/Images/select-mail.png)
 
9.	Sign in with the outlook email account.

![Azure Logic Designer](https://github.com/orionlab-io/blogs/blob/main/Azure%20Logic%20Apps/Images/sign-in.png)

10.	Fill the details like body, subject to whom the notification should receive it. Save the workflow and run it
 
Once the logic app starts running, the person will receive a notification e-mail on the basis of modifying/update of the blob.

#### For any Support Please Contact us at [connect@orionlab.io](mailto:connect@orionlab.io)
## ![OrionLab Logo](https://github.com/orionlab-io/blogs/blob/main/orion-lab-github-logo.png)
