---
title: Connect to the SAP HANA Cockpit
description: In this tutorial, you will open the application from the dashboard and connect to the SAP HANA Cockpit.
auto_validation: true
time: 10
tags: [tutorial>beginner, products>sap-hana, products>sap-cloud-platform\,-sap-hana-service]
primary_tag: products>sap-hana
---

## Prerequisites
 - You have created an instance of the SAP Cloud Platform, SAP HANA Service in Cloud Foundry


## Details
### You will learn
  - How to connect to the SAP HANA Cockpit which allows you to perform administrative tasks in the physical database

The SAP HANA Cockpit is useful because it provides graphical tools to monitor resources and the overall heath of your database

**This tutorial cannot currently be completed with the trial account.**

---

[ACCORDION-BEGIN [Step 1: ](Ensure that the instance is created)]

Navigate back to the **SAP Cloud Platform Cockpit** to check on the progress status of your instance.

Click on the **trial** subaccount.

![New project from template](1.png)

Click on **Spaces** and click on the **dev** space.

![New project from template](2.png)

Click on **Service Instances**.

![New project from template](3.png)

Ensure that you see ***Created*** under **Last Operation** for the HDB instance.

![New project from template](4.png)

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [Step 2: ](Access the SAP HANA Service Dashboard)]

Click on the **Open Dashboard** icon ![New project from template](5.png) under **Actions**.

![New project from template](6.png)

When prompted, click **Authorize** to authorize access for the cockpit.

![New project from template](7.png)

The SAP HANA Service Dashboard will open. Notice that you can see the connectivity endpoints and the Cockpit. You are also able to see your database ID.

>**Note**: Keep this tab open as you will use it later.

![New project from template](sap hana service dashboard.png)

[DONE]
[ACCORDION-END]


[ACCORDION-BEGIN [Step 3: ](Access the SAP HANA Cockpit)]

Access the **SAP HANA Cockpit** using the button located at the top right corner.

![New project from template](8.png)

Enter the following credentials and then click **OK** to log in to the database:

**Username**: `SYSTEM`

**Password**: `HanaRocks1`

> Adapt the password to match the one you chose during setup if you changed it.

![New project from template](9.png)

You can now explore the SAP HANA Cockpit for your database instance.

![New project from template](10.png)

>**Note**: Keep this tab open as you will be using it later.

Open the **SQL Console**.

![HaaS SQL Console](11.png)

Execute the following statement to complete the validation below.

![HaaS SQL Console](12.png)

[VALIDATE_1]
[ACCORDION-END]

---
