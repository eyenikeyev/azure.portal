<p align="center">
<img src="https://github.com/ColtonTrauCC/vm-network/assets/147654000/2cb238ff-4e46-4a75-8967-7ef5d124ab74" height="15%" width="15%" alt="Microsoft Azure logo"/>
</p>

<h1 align = "center">Basics of Azure Portal</h1>
This tutorial goes over how to use Microsoft Azure Portal as well as how to create/manage Resource Groups and Storage Accounts within Azure Portal.

<br />

<h2>Environments and Technologies Used</h2>

<ul>
  <li>Microsoft Azure Portal</li>
</ul>

</br>

<h2>List of Prerequisites</h2>
<ul>
  <li>Microsoft Azure Account and Subscription</li>
  <ul>

<br />

<h2>Essentials</h2>

<h3>Navigating Azure Portal</h3>

<p>
<ul>
Upon logging into Azure Portal, the first image you should always see is the Home Page. The Home Page offers multiple ways to access the Azure Portal's resources, one being the search bar at the top of the center and notable headings.
<p>
</p>
<b>Azure Services</b>: The Services in Azure Portal that updates with the most recent Resources used; by all of Azure Portal's Services can be locateed on a seperate page by going to More Services</li>
</p>
<b>Resources</b>: A listing that displays and updates whenever Resources (Resource Groups, Virtual Machines, Network Security Groups, etc.) are created or recently modified</li>
</p>
<b>Navigate</b>: A quality of life heading allowing users to easily navigate to the essentials of their account, notably Resources and Subscriptions
</li>
</p>
<b>Tools</b>: Heading that offers quick links to the infrastructure and cost of the resources used in Azure as well as the online course Microsoft Learn for further education how to use Microsoft Azure
</li>
</p>
<img src="https://i.imgur.com/vCoUald.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
</ul>
</p>

<br/>

<h3>Creating a Resource Group</h3>

<p>
  <ul>
Resource Groups serve as the base for many of Microsoft Azure's services and tools. To use Virtual Machine or Network Security Groups, you need a Resource Group. Go to the Resource Group page and click on Create
</p>
Resource Groups have three fields for creation
</p>
<b>Basics</b>: Tab where you enter the name of your Resource Group and Subscription it is linked to for billing upon use of Resources in that Group
</li>
</p>
<b>Tags</b>: simple organizational tool for managing resources and view consolidated billing by applying the same tag to multiple resources and resource groups
</li>
</p>
<b>Review + Create</b>: Validation process to check if credentials are filled and subscription is usable
</li>
<p>
After validation passed, click on Create in the bottom and your Resource Group is created.
</p>
<b>Note</b>: based on server speed and internet connection, resources and resource groups will take some time to deploy, take note of the notification bell at the top right to see when deployment is complete
</li>
</p>
<img src="https://i.imgur.com/8qRWajw.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
</ul>
</p>

<br />

<h3>Creating and using the Storage Account</h3>

<p>
  <ul>
<p>
The Storage Account is a resource in Microsoft Azure that serves as a general 500 terabyte storage unit for data in the cloud, more information can be found at: https://azure.microsoft.com/en-us/products/category/storage/
</p>
Go to the Storage Account page and click on create. Storage Accounts have multiple areas for creation.
</p>
<b>Basics</b>: the resource group the resource will be in and instance details for the name of the storage account and determining performance
</li>
</p>
<b>Advanced</b>: more complex options such as adjusting security and protocols; some are not availabel depending on your storage account's instance details from Basics
</li>
</p>
<b>Networking</b>: Connectivity and Routing Options
</li>
</p>
<b>Data Protection</b>: Enables how data is recovered and tracked in storage
</li>
</p>
<b>Encryption</b>: Determines how data is encrypted, uses Microsoft managed keys by default
</li>
</p>
<b>Tags</b>: same as creation of tags in Resource Group creation
</li>
</p>
<b>Review</b>: checking validation and overview of the resource's information
</li>
</p>
