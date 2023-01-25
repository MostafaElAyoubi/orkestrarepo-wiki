---
description: >-
  This document describes how to set up the Single Sign-On (SSO) for Orkestra on
  systems that use Azure for identity and access management.
---

# App Registration

## Azure AD setup&#x20;

To enable SSO, you must first complete the setup on the Microsoft AAD.

### Register the App

1. In the Microsoft Azure portal, navigate to the "Azure Active Directory" service

![](<../../.gitbook/assets/1 (2).png>)

2 . Select App registration

![](<../../.gitbook/assets/2 (1).png>)

3 . And select "New Registration"

![](../../.gitbook/assets/3.png)

4 . Enter the following details :

![](<../../.gitbook/assets/4 (1).png>)



* Display name : Orkestra
* Redirect Uri type : Public client/native (mobile & desktop)
* Redirect Uri : [https://login.microsoftonline.com/common/oauth2/nativeclient](https://login.microsoftonline.com/common/oauth2/nativeclient)
* Click on **Register** button

5 .  Create new client secret&#x20;

![](../../.gitbook/assets/5.png)

![](../../.gitbook/assets/secret.png)

6 . Go to API Permissions => Add a permission

![](../../.gitbook/assets/9.png)

6 .1 Select Microsoft Graph => application permissions

![](../../.gitbook/assets/10.png)

6 .2 Add the below permissions then click "Grant admin consent for Orkestra" :

![](../../.gitbook/assets/11.png)

![Make sure that these permissions are granted for orkestra](../../.gitbook/assets/12.png)

## Orkestra Admin setup

&#x20;Open Orkestra with an admin account ,and go to SSO console

Enter the following details&#x20;

![](<../../.gitbook/assets/SSO (1).png>)

1. &#x20;Organization Name : Your organization name (ex : Orkestra)
2. Tenant id : Go to your app registration overview => Directory(tenant) ID

![](../../.gitbook/assets/81.png)

3\. Client id : Go to your app registration overview => Application (client) ID

![](../../.gitbook/assets/82.png)



4\. Entreprise App Object Id : Go to Entreprise applications => orkestra => overview =>Object ID

![](../../.gitbook/assets/14.png)

5\. App Secret : Paste your app secret previously created

6\. Admin Id : automaticallt filled

7\. Add all domains you want to authorize (ex: orkestra.online)

##
