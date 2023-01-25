---
description: >-
  Before you start inviting users to hubs/workspaces, there is a couple of
  important elements to beare in mind!
---

# Inviting SSO users to Hubs/Workspaces

### 1. You need to wait for users to login one first time before you can invite them

This is due to the fact that granting the access through AAD doesn't generate the Orkestra Online account. The Orkestra Online account is generated when the user first logs in to their account. Before that, if you try and invite them, you'll get an error message saying that the user doesn't exist.&#x20;

### 2. You can't use AAD groups to manage Hub/Workspace access (yet)

As of right now, you'll need to invite users separately, even if they've been granted access to Orkestra through an AAD group. [You can use the .Csv additio](https://datashapes.gitbook.io/orkestra-online/orkestra-desktop-app/what-is-a-hub) method to batch invite users to hubs/workspaces though!&#x20;
