---
description: >-
  Orkestra's web API allows you to list your online content as Json! Here's a
  workflow to connect it directly with PowerBI (You nee Orkestra 1.2.0 or more
  recent for this).
---

# Content Metrics

### In OrkestraIn Orkestra

#### 1. Getting your UserKey from the Account section of Orkestra

![Clicking on the Copy to clipboard button will copy your Orkestra UserKey to your clipboard](../.gitbook/assets/ListContent1.png)

### In PowerBI

#### 1. Go to the opening screen of PowerBI and select “Get data from another source”

![](../.gitbook/assets/1.png)

#### 2. Select “Other”, then “Web”, then “Connect”

![](../.gitbook/assets/2.png)

#### 3. Paste the Url from your clipboard and hit OK

Enter the web request URL : <mark style="color:purple;">**https://api.orkestra.online/listcontent?userKey=**</mark><mark style="color:red;"><</mark><mark style="color:red;">**yourUserKey**</mark><mark style="color:red;">></mark>

![](../.gitbook/assets/ListContentUrl.png)

#### 4. The response will be automatically recognized and converted to a table by PowerBI. You can hit “Close\&Apply”

![](../.gitbook/assets/ListContentTable.png)

#### 5. Build your custom Dashboards!

![](../.gitbook/assets/ListContentSample.png)

##
