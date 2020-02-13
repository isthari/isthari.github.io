---
title: "Tableau"
permalink: /user_guide/tableau
excerpt: "Tableau"
modified: 2016-04-13T15:54:02-04:00
redirect_from:
  - /theme-setup/
toc: true
---

{% include base_path %}
This article show you how to connect your existing Tableau to your cloud account

First you must download and install the Official Presto Tableau Driver [https://www.tableau.com/support/drivers](https://www.tableau.com/support/drivers)

Select Data Source: "Presto"

Choose your Operating System and Bit Version

![](bi-01-tableau-driver-download.png)

Download and install your driver

![](bi-01-tableau-driver-donwload2.png)

Once installed open Tableau Desktop 

Select Presto data source type from the menu

![](bi-01-tableau-select-driver.png)

Configure the server to connect to. It'll depend on the cloud provider and region of your account.

To get the server for your environment you must contact your Administrator

Port: 443

Contact your account administrator to get the Catalog of your Company

Select Authentication: LDAP

Introduce your username and password

Check Require SSL

Click Sign In

![](bi-01-tableau-connection-settings.png)

Now select the schema and table as usual with Tableau and start working !!!

![](bi-01-tableau-data-preview.png)

---

