# ServiceNow – Importing & Securing Data

## 1. Project Overview

This project demonstrates the process of importing employee training data into ServiceNow and securing the data using role-based access control and Access Control Lists (ACLs).

The project covers data import, Transform Maps, reference fields, dot-walking, user and role configuration, ACL security, and access testing.

## 2. Project Objectives

* Import employee training data from an Excel file into ServiceNow.
* Create and configure an Employee Training Records table.
* Map imported data using Transform Maps.
* Use reference fields and dot-walking to access employee information.
* Create users and roles for controlled access.
* Configure Read and Write ACLs.
* Test access permissions using user impersonation.

## 3. Project Workflow

```text
Excel Training Data
        ↓
     Load Data
        ↓
   Transform Map
        ↓
Employee Training Records
        ↓
   Reference Field
        ↓
     Dot-Walking
        ↓
 User & Role Configuration
        ↓
     ACL Security
        ↓
   Access Testing
```

## 4. Data Import

Employee training information is provided through an Excel dataset.

The Excel file is:

`Employee_Training_Data.xlsx`

The data is loaded into ServiceNow using the Import Set process.

## 5. Transform Map

A Transform Map is used to map the imported Excel columns to the corresponding fields in the Employee Training Records table.

This ensures that the imported data is stored in the correct fields.

## 6. Reference Fields and Dot-Walking

Reference fields are used to connect employee training records with employee information.

Dot-walking allows information from the referenced record to be accessed through the reference field.

## 7. Security Implementation

The project uses role-based access control and ACLs to protect employee training information.

The security configuration includes:

* User creation
* Role assignment
* Read ACL
* Write ACL
* Access testing

## 8. Access Testing

Access permissions are tested using user impersonation.

Different users are tested to verify whether they can read or modify the required employee training information.

## 9. Expected Result

The final system provides:

* Successful Excel data import
* Correct field mapping
* Reference-based employee information access
* Controlled user access
* Read and Write security through ACLs
* Verified access permissions

## 10. Project Repository

The project source files and supporting data are maintained in this GitHub repository.

**GitHub:**
https://github.com/harithakronixtech006-tech/servicenow-importing-securing-data
