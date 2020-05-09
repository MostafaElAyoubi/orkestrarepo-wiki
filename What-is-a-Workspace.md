# Workspaces 
Workspaces are the **first level of subfolders inside a Hub**.
A Workspace is a storage space where you can load and organize your Dynamo definitions. It is represented by a " ![folder](https://datashapes.files.wordpress.com/2020/05/workspace.png?) " in the "Online Workspaces" window.
**If you are the owner/ an administrator of the Workspace**, you can view and edit it's **settings**. **If you as the owner/ an administrator of a Hub**, you can add new Workspaces to it. 

##To create a Workspace:
1. Select the Hub you wish to add a Workspace to in the **Online Workspaces** window
2. Press  ![new workspace](https://datashapes.files.wordpress.com/2020/05/addworkspace.png?resize=107%2C107)
3. Select a name for your Workspace and confirm by clicking "Create Folder"
![naming](https://datashapes.files.wordpress.com/2020/05/namingws.png?)
4. Your new Workspace will appear as a child of the Hub
![wsadded](https://datashapes.files.wordpress.com/2020/05/wsadded.png?)

##To edit the Workspace settings:
1. Select the Workspace in the "Online Workspaces" window 
2. Click on ![settings](https://datashapes.files.wordpress.com/2020/05/hub-settings.png?) . **This button will only be enabled if your are the owner/ an administrator of the Workspace**.

![enterSettings](https://datashapes.files.wordpress.com/2020/05/hu-settings-_.png?)

## User settings

In the Hub settings, you can specify which user gets access to it's content. The list of users and their level of access is diplayed here:

![userSettings](https://datashapes.files.wordpress.com/2020/05/usersettings.png?)

**If someone has access to a Hub, they have acces to ALL THE CONTENT OF THE HUB.**

You can easilly manage the users through this window:

### Add users to the Hub
1. Click on ![add](https://datashapes.files.wordpress.com/2020/05/adduser.png?)
2. Enter the email of the user you wish to add (they need to have an Orkestra Online account) and specify their role.

![enteruser](https://datashapes.files.wordpress.com/2020/05/enteruser.png?)

```diff
- Note that - for now - every person invited to a Hub will have an "Admin" role. -
- There is no "User" role at Hub level. -
- (Looking forward to collect feedback onthis particular point) -
```
### Delete users from the Hub
1. Select the user to be deleted in the list 
2. Click on ![delUser](https://datashapes.files.wordpress.com/2020/05/deluser.png?)

```diff
-By default, the User Settings at Hub level are inherited by the Workspaces located inside the Hub.-
-But those settings can be overriden at Workspace level.-
```

## Package Settings

The Hub settings also let you sync a set of packages to be used for definitions located inside that Hub. That means that when played through the [Orkestra Online Tab of the Orkestra Revit Addin](https://github.com/MostafaElAyoubi/Orkestra_Online/wiki/Orkestra-Online-Player-Tab), Orkestra switches the package environment automaticcaly accordingly with the those settings. 
This lets you set the exact package versions that are required for your definitions, which makes deploying your content much easier and safer.

![package settings](https://datashapes.files.wordpress.com/2020/05/synpackages.png?)

In order to synchronize a set of packages with your Hub, you need to : 
1. Press the ![syncpackage](https://datashapes.files.wordpress.com/2020/05/synpackages-1.png?) button on the bottom right of the Hub settings window
2. Browse to a folder containing the packages you wish to sync with the Hub

![selectfolder](https://datashapes.files.wordpress.com/2020/05/set-package-folder-1.png?)

The content of that folder is the Dynamo package folders and must look something like this:

![packagefoldercontent](https://datashapes.files.wordpress.com/2020/05/packages-1.png?)

One the sync if finished, you can see the list of packages and their versions displayed in the Orkestra Hub Settings window:

![packagesupdated](https://datashapes.files.wordpress.com/2020/05/packages-updated.png?)

```diff
-By default, the Package Settings at Hub level are inherited by the Workspaces located inside the Hub.-
-But those settings can be overriden at Workspace level.-
```