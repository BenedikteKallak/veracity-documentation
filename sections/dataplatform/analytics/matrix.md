---
author: Veracity
description: This page explains how to utilize the analytics capabilities
---

# User management and access control

Adding or removing users will be managed exclusively through the Data Workbench:

- Users will not have admin-level access in databricks. 
- Creating or upgrading clusters will not be permitted.
- Enable Unity Catalog
- Creating Credentials  will not be permitted.
- Creating External Locations  will not be permitted.
- Creating New Catalog  will not be permitted.
- Create New Schema  will not be permitted.
- Creating New Group  will not be permitted.

|Action | Data Workbench Admin	|Data Workbench Reader|
|--|--|--|
|Create Managed Table|	<figure> <img src="assets/crosscheckmark.jpg"/> </figure> | <figure> <img src="assets/crosscheckmark.jpg"/> </figure>|
Create External Table|	<figure> <img src="assets/checkmark.jpg"/> </figure> | <figure> <img src="assets/crosscheckmark.jpg"/> </figure>|
|Create View	|<figure> <img src="assets/crosscheckmark.jpg"/> </figure> | <figure> <img src="assets/crosscheckmark.jpg"/> </figure>|
|Run SQL	|<figure> <img src="assets/checkmark.jpg"/> </figure> | <figure> <img src="assets/checkmark.jpg"/> </figure>|
|Run Python	|<figure> <img src="assets/checkmark.jpg"/> </figure> | <figure> <img src="assets/crosscheckmark.jpg"/> </figure>|
|Save Data to storage	|<figure> <img src="assets/checkmark.jpg"/> </figure> | <figure> <img src="assets/crosscheckmark.jpg"/> </figure>|
|Update Cluster Packages "Requirments.txt"	|<figure> <img src="assets/crosscheckmark.jpg"/> </figure> | <figure> <img src="assets/crosscheckmark.jpg"/> </figure>|
|Create Workflows	|<figure> <img src="assets/crosscheckmark.jpg"/> </figure> | <figure> <img src="assets/crosscheckmark.jpg"/> </figure>|
|Share	|<figure> <img src="assets/crosscheckmark.jpg"/> </figure> | <figure> <img src="assets/crosscheckmark.jpg"/> </figure>|
|Create Dashboard	|<figure> <img src="assets/checkmark.jpg"/> </figure> | <figure> <img src="assets/checkmark.jpg"/> </figure>|
|Create Secret	|<figure> <img src="assets/checkmark.jpg"/> </figure> | <figure> <img src="assets/checkmark.jpg"/> </figure>|
|Create Model	|<figure> <img src="assets/checkmark.jpg"/> </figure> | <figure> <img src="assets/checkmark.jpg"/> </figure>|
|Use R	|<figure> <img src="assets/crosscheckmark.jpg"/> </figure> | <figure> <img src="assets/crosscheckmark.jpg"/> </figure>|