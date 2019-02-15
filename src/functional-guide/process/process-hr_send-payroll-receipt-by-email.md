
Send Payroll Receipt by Email
# Send Payroll Receipt by Email


This process is used to send the Payroll Receipt for each Employee by EMail

Parameters
## Parameters


Process
### Process

**Description**
 *Process or Report*
**Help**
 *The Process field identifies a unique Process or Report in the system.*

:::tip
The field must have a value for the record to be saved to the database.
:::
Payroll Process
### Payroll Process


:::tip
The field must have a value for the record to be saved to the database.
:::
Mail Template
### Mail Template

**Description**
 *Text templates for mailings*
**Help**
 *The Mail Template indicates the mail template for return messages. Mail text can include variables.  The priority of parsing is User/Contact, Business Partner and then the underlying business object (like Request, Dunning, Workflow object).
So, @Name@ would resolve into the User name (if user is defined defined), then Business Partner name (if business partner is defined) and then the Name of the business object if it has a Name.
For Multi-Lingual systems, the template is translated based on the Business Partner's language selection.*

:::tip
The field must have a value for the record to be saved to the database.
:::
Business Partner Group
### Business Partner Group

**Description**
 *Business Partner Group*
**Help**
 *The Business Partner Group provides a method of defining defaults to be used for individual Business Partners.*

Business Partner
### Business Partner

**Description**
 *Identifies a Business Partner*
**Help**
 *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*

Payroll Department
### Payroll Department


Payroll Job
### Payroll Job


Activity
### Activity

**Description**
 *Business Activity*
**Help**
 *Activities indicate tasks that are performed and used to utilize Activity based Costing*
