# What is a Workspace?

Workspaces are the **first level of subfolders inside a Hub**. A Workspace is a storage space where you can load and organize your Dynamo definitions. It is represented by a " ![folder](https://datashapes.files.wordpress.com/2020/05/workspace.png?) " in the "Online Workspaces" window. **If you are the owner/ an administrator of the Workspace**, you can view and edit its **settings**. **If you are the owner/ an administrator of a Hub**, you can add new Workspaces to it.

## To create a Workspace:

1. Select the Hub you wish to add a Workspace to in the **Online Workspaces** window
2. Press  ![new workspace](https://datashapes.files.wordpress.com/2020/05/addworkspace.png?)
3.  Select a name for your Workspace, selection the [version compatibility](what-is-a-workspace.md#software-compatibility-settings) and confirm by clicking "Create Folder"


4.  Your new Workspace will appear as a child of the Hub



![WorkSpace creation interface](../.gitbook/assets/addworkspace.png)

![](https://datashapes.files.wordpress.com/2020/05/wsadded.png?)

```diff
The version compatibility is going to help filter the content based on the Revit/Rhino/Civil3D version you're in!
For example, if a WorkSpace is set as compatible with Revit 2020 only, it's content won't be 
displayed inside other version of Revit in order to reduce run errors and compatibility issues.
```

## To edit the Workspace settings:

1. Select the Workspace in the "Online Workspaces" window&#x20;
2. Click on ![settings](https://datashapes.files.wordpress.com/2020/05/hub-settings.png?) . **This button will only be enabled if your are the owner/ an administrator of the Workspace**.

![](https://datashapes.files.wordpress.com/2020/05/enterwssettings.png?)

## User settings

In the Workspace Settings, you can specify which user gets access to its content. The list of users and their level of access is diplayed here:

![](../.gitbook/assets/usersettings.png)

**If someone has access to the parent Hub of the Workspace as a Hub Admin, they automatically have access to the Workspace as well.**

You can easily manage the users through this window:

### Add users to the Workspace

1. Click on ![add](https://datashapes.files.wordpress.com/2020/05/adduser.png?)
2. Enter the email address of the user you wish to add (they need to have an Orkestra Online account) and specify their role.

![](https://datashapes.files.wordpress.com/2020/05/enteruser.png?)

A **user** will be able to use the definitions through the Orkestra Revit Addin and view its properties but won't be able to download / open the script or edit its properties. \
An **admin** will be able to edit all settings of the Workspace and will also be able to download, open and edit definitions and their properties.

### Add multiple users to the Workspace from .csv file <a href="#add-multiple-users-to-the-hub-from-.csv-file" id="add-multiple-users-to-the-hub-from-.csv-file"></a>

1. Click on <img src="../.gitbook/assets/image (2) (2).png" alt="" data-size="line"> ​​
2. Select your .csv file. The format of the .csv must be as follow (UTF-8 Comma delimited) : first column is email, second column is access level.

![](<../.gitbook/assets/image (1) (2).png>)



### Delete users from the Workspace

1. Select the user to be deleted in the list&#x20;
2. Click on ![delUser](https://datashapes.files.wordpress.com/2020/05/deluser.png?)

### Updating a user's role:

1.  Select a user in the list and use the dropdown menu to pick their new role


2. Click on ![delUser](https://datashapes.files.wordpress.com/2020/05/updaterole.png?) to update the user role information in the platform&#x20;

![](../.gitbook/assets/userrole.png)

## Package Settings

The Workspace settings also let you sync a set of packages to be used for definitions located inside that Workspace. This means that when a script is launched through the **** [**Orkestra Online Player Tab of the Orkestra Revit Addin**](../orkestra-revit-addin/orkestra-online-player-tab.md), Orkestra switches the package environment automatically to match the parent Workspace's package settings. This lets you set the exact package versions that are required for your definitions, which makes deploying your content much easier and safer.

By default, the Hub settings are inherited. The list of packages is greyed out and the sync button is disabled. If you wish to set specific package settings for a Workspace, you first need to Override the Hub settings by switching on the ![override](https://datashapes.files.wordpress.com/2020/05/overridehubsettings.png?) toggle and confirm that you want to override the settings.

Once the toggle is switched on, the modifications are enabled for the Workspace:

![](../.gitbook/assets/overridehubsettings.gif)

### Synchronizing a set of packages with your Workspace, you need to :&#x20;

1\. Press the ![syncpackage](https://datashapes.files.wordpress.com/2020/05/synpackages-1.png?) button on the bottom right of the Hub settings window \
2\. Browse to a folder containing the packages you wish to sync with the Hub

![](https://datashapes.files.wordpress.com/2020/05/set-package-folder-1.png?)

The content of that folder is the Dynamo package folders and must look something like this:

![](https://datashapes.files.wordpress.com/2020/05/packages-1.png?)

Once the sync if finished, you can see the list of packages and their versions displayed in the Orkestra Hub Settings window.

### Adding a single package to the package settings

1. Press the <img src="../.gitbook/assets/image (12).png" alt="syncpackage" data-size="line">button&#x20;
2. Browse to to the package folder you wish to add
3. Confirm

![](../.gitbook/assets/addsinglepackage.gif)

OR : simply drag and drop a package folder

![](../.gitbook/assets/dragdrop-package.gif)

### Removing a single package to the WorkSpace settings

1. Select the package you wish to remove
2. Click the <img src="../.gitbook/assets/image (11).png" alt="syncpackage" data-size="line"> button

![](../.gitbook/assets/deletesingle-package.gif)

## Software Compatibility Settings

Ever since Orkestra 1.1.0, you can specify the software compatibility of a Workspace:

![Setting the software compatibility for a Workspace](../.gitbook/assets/softwarecompatibilitysettings.gif)

&#x20;This will have two consequences:&#x20;

* You'll be able to filter  your content -based on this informations- while browsing&#x20;

![](../.gitbook/assets/versionbroswsing.gif)

* In all Orkestra integrations, the content will be automatically filtered based on the software version you're in. For example, if you're in Revit 2020, you'll only see the werspaces set as compatible with Revit 2020.

```diff
 A Workspace can contain sub folders, but there are no specific user or package settings at their level
```
