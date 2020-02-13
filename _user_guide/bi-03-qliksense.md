---
title: "QlikSense"
permalink: /user_guide/qliksense
excerpt: "QlikSense"
modified: 2016-04-13T15:54:02-04:00
redirect_from:
  - /theme-setup/
toc: true
---

{% include base_path %}
This article shows you how to connecto your existing QlikSense to your cloud account

First you must download and install the presto driver from Simba https://www.simba.com/drivers/presto-odbc-jdbc/

Then open the ODBC Administrator

<img src="bi-03-qliksense-open-odbc.png" width="75%"/>


Click on "Add" button

<img src="bi-03-qliksense-odbc-add.png" width="75%"/>


Select "Simba Presto ODBC Driver" and click Finish

<img src="bi-03-qliksense-odbc-presto.png" width="75%"/>


Select Authentication type: "LDAP Authentication"

Introduce your user and password

Contact your account administrator to get the server for your environment

Port number 443

Click on "Test" button to check your connectivity

<img src="bi-03-qliksense-odbc-test.png" width="75%"/>


Now on QlikSense click on Add data from files and other sources

<img src="bi-03-qliksense-add-data.png" width="75%"/>


Search for ODBC Connector and click on it

<img src="bi-03-qliksense-add-odbc.png" width="75%"/>


In the User DSN select your new datasource and introduce your username and password, then click on create

<img src="bi-03-qliksense-add-dsn.png" width="75%"/>


Now you can continue working as usual with QlikSense







