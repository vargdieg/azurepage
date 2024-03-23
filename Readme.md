# Azure page
Project to create a basic Azure page
The inital goal of this project is to be able to create a static web page, that can be editable using the github repo

# Prerequisites
1. Create or have an [Azure account][1]
2. Create an [github repo][2]

# Step-by-Step
1. [Create resource group](#create-resource-group)
2. [Create an static web app in azure](#create-an-static-web-app-in-azure)


## Create resource group
In the azure menu, go to all services, under general search for the resource group

![resourcegroup][resource-group]

When you select create you are going to be prompted to a menu, select your azure suscription and a region location of your resources
Alson input a name for the group resources

Go to next

![ResourceGroupCreation][create-resource-group]

In the next page you can see labels, and you can create label to group your resources

![labelResourceGroup][label-resource-group]

Then click on next and create to create an group of resources

For more information about resource groups check out the [Manage Azure resource groups by using the Azure portal][3]

## Create an static web app in azure
In the azure menu, go to all services, and under the web and mobile search for the web static application

![webStaticApp][image-web-static-app]

Select the suscription and a resource group (you can use the one created above or another one if you have already created)

![webStaticApp1][image-web-static-app1]

Under the host plan you can select free, under the region you can select the most suitable for you
For the details since the project is in github we are going to select Github and to initiate session (you may need to provide credentials for your repo)

![webStaticApp][image-web-static-app2]



For more information about creating an static web app using azure checkout the [build your first static web app][4]

[1]:https://azure.microsoft.com/en-us/free
[2]:https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories
[3]:https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/manage-resource-groups-portal
[4]:https://learn.microsoft.com/en-us/azure/static-web-apps/get-started-portal?tabs=vanilla-javascript&pivots=github

[image-web-static-app]:./images/AzureWebStaticApp.png
[resource-group]:./images/AzureGroupResource.png
[label-resource-group]:./images/AzureResourceGroupLabel.png
[create-resource-group]:./images/CreatingAzureResourceGroup.png
[image-web-static-app1]:./images/AzureStaticWebApp1.png
[image-web-static-app2]:./images/AzureStaticWebApp2.png