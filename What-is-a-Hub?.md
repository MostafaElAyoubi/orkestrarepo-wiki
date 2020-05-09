# HUB 
Every **Orkestra Online** account has an associated "Hub". 
A Hub is a storage space where you can load and organize your Dynamo definitions. It is represented by a " ![cloud](https://datashapes.files.wordpress.com/2020/05/cloudi.png?resize=30%2C20) " in the "Online Workspaces" window.
**If you are the owner/ an administrator of the Hub**, you can view and edit it's **settings** 
```diff
- A Hub cannot directly contain Dynamo definitions. -
```

To edit the Hub settings:
1. Select the Hub in the "Online Workspaces" window 
2. Click on ![settings](https://datashapes.files.wordpress.com/2020/05/hub-settings.png?) . This button will only be enabled if your are the owner/ an administrator of the Hub.

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
1. Press the "![synpackages](https://datashapes.files.wordpress.com/2020/05/synpackages.png?)" button on the bottom right of the Hub settings window
2. Browse to a folder containing the packages you wish to sync with the Hub

![selectfolder](https://datashapes.files.wordpress.com/2020/05/set-package-folder-1.png?)

The content of that folder is the Dynamo package folders:

![packagefoldercontent](https://datashapes.files.wordpress.com/2020/05/packages-1.png?)

```diff
-By default, the Package Settings at Hub level are inherited by the Workspaces located inside the Hub.-
-But those settings can be overriden at Workspace level.-
```