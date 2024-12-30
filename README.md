# AZURE---TASK-22

## Create a blob container and a time-based retention policy

Continue in the Azure portal, working with your storage account.

In the Data storage section, click Containers.

Click + Container and Create a container with the following settings:

On your container, scroll to the ellipsis (...) on the far right, select Access Policy.

In the Immutable blob storage area, select Add policy.

Select Save.

## Manage blob uploads

Return to the containers page, select your data container and then click Upload.

On the Upload blob blade, expand the Advanced section.

Click Upload.

Confirm you have a new folder, and your file was uploaded.

Select your upload file and review the options including Download, Delete, Change tier, and Acquire lease.

Copy the file URL and paste into a new Inprivate browsing window.

You should be presented with an XML-formatted message stating ResourceNotFound or PublicAccessNotPermitted.

Note: This is expected, since the container you created has the public access level set to Private (no anonymous access).

## Configure limited access to the blob storage

Select your uploaded file and then on the Generate SAS tab. You can also use the ellipsis (...) to the far right. Specify the following settings (leave others with their default values):


Click Generate SAS token and URL.

Copy the Blob SAS URL entry to the clipboard.

Open another InPrivate browser window and navigate to the Blob SAS URL you copied in the previous step.

Note: You should be able to view the content of the file.
