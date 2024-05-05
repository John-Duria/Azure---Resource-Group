<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/a/a8/Microsoft_Azure_Logo.svg"/>
</p>


<h1>Creating a Resource Group in the Cloud (Azure)</h1>
This tutorial outlines Step-by-Step Guide to Creating a Resource Group in Azure.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>Task</h2>

- Task 1. Creating a Resource Group and Deploying Windows 10 and Windows Server VMs.
- Task 2. How to ensure connectivity between the client and Domain Controller.
- Task 3. How to install Active Directory.
- Task 4. How to create an Admin and Normal User Account in AD.
- Task 5. How to join Client-1 to your domain (mydomain.com)
- Task 6. How to setup Remote Desktop for non-administrative users on Client-1
- Task 7. How to create a bunch of additional users and attempt to log into client-1 with one of the users
1. Sign in to the Azure Portal:

    Open your web browser and navigate to the Azure portal.
    Sign in with your Azure account credentials.

2. Navigate to Resource Groups:

    Once signed in, you'll see the Azure dashboard. Use the left-hand navigation pane to click on "Resource groups" under the "All services" section.

3. Create a New Resource Group:

    In the Resource groups blade, click on "+ Add" to create a new resource group.

4. Fill in Resource Group Details:

    In the "Basics" tab of the Create a resource group dialog:
        Subscription: Choose the Azure subscription you want to use.
        Resource group: Enter a unique name for your resource group. This name must be unique within the subscription and adhere to Azure naming rules (letters, numbers, hyphens, and periods are allowed).
        Region: Select the Azure region where you want your resource group to be located.

5. Review and Create:

    After filling in the details, click on "Review + create" to review your resource group settings.

6. Review the Details:

    Azure will validate the details you provided. Ensure all the information is correct.

7. Create the Resource Group:

    Click "Create" to create the resource group with the specified settings.

8. Wait for Deployment:

    Azure will now deploy your resource group. This process usually completes within a few seconds.

9. Resource Group Creation Confirmation:

    Once deployment is complete, you will receive a notification that the resource group has been successfully created.

10. Accessing Your Resource Group:
- Navigate back to the "Resource groups" section from the Azure portal's left-hand navigation pane.
- You should now see your newly created resource group listed here.
