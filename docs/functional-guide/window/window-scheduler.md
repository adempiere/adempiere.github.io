
Scheduler
# Scheduler


Maintain Schedule Processes and Logs

Help
## Help

Schedule processes to be executed asynchronously

Window Type
### Window Type

**Maintain**

:::tip
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
:::

Tabs
## Tabs


Schedule Process
### Schedule Process

**Description**
 *Schedule processes*
**Help**
 *Schedule processes to be executed asynchronously*

:::tip
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.
:::
Fields
## Fields


Client
### Client

**Description**
 *Client/Tenant for this installation.*
**Help**
 *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*

Organization
### Organization

**Description**
 *Organizational entity within client*
**Help**
 *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*

Name
### Name

**Description**
 *Alphanumeric identifier of the entity*
**Help**
 *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Process
### Process

**Description**
 *Process or Report*
**Help**
 *The Process field identifies a unique Process or Report in the system.*

Schedule Type
### Schedule Type

**Description**
 *Type of schedule*
**Help**
 *Define the method how the next occurrence is calculated*

Frequency Type
### Frequency Type

**Description**
 *Frequency of event*
**Help**
 *The frequency type is used for calculating the date of the next event.*

Frequency
### Frequency

**Description**
 *Frequency of events*
**Help**
 *The frequency is used in conjunction with the frequency type in determining an event. Example: If the Frequency Type is Week and the Frequency is 2 - it is every two weeks.*

Ignore Processing Time
### Ignore Processing Time

**Description**
 *Do not include processing time for the DateNextRun calculation*
**Help**
 *When this is selected, the previous DateNextRun is always use as the source for the next DateNextRun calculation.*

Cron Scheduling Pattern
### Cron Scheduling Pattern

**Description**
 *Cron pattern to define when the process should be invoked.*
**Help**
 *Cron pattern to define when the process should be invoked. See http://en.wikipedia.org/wiki/Cron#crontab_syntax for cron scheduling syntax and example.*

Supervisor
### Supervisor

**Description**
 *Supervisor for this user/organization - used for escalation and approval*
**Help**
 *The Supervisor indicates who will be used for forwarding and escalating issues for this user - or for approvals.*

Days to keep Log
### Days to keep Log

**Description**
 *Number of days to keep the log entries*
**Help**
 *Older Log entries may be deleted*

Date last run
### Date last run

**Description**
 *Date the process was last run.*
**Help**
 *The Date Last Run indicates the last time that a process was run.*

Date next run
### Date next run

**Description**
 *Date the process will run next*
**Help**
 *The Date Next Run indicates the next time this process will run.*

Table
### Table

**Description**
 *Database Table information*
**Help**
 *The Database Table provides the information of the table definition*

Record ID
### Record ID

**Description**
 *Direct internal record ID*
**Help**
 *The Record ID is the internal unique identifier of a record. Please note that zooming to the record may not be successful for Orders, Invoices and Shipment/Receipts as sometimes the Sales Order type is not known.*

Parameter
### Parameter

**Description**
 *Scheduler Parameter*
**Help**
 *Provide parameter for scheduled process*

:::tip
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.
:::
Fields
## Fields


Client
### Client

**Description**
 *Client/Tenant for this installation.*
**Help**
 *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*

Organization
### Organization

**Description**
 *Organizational entity within client*
**Help**
 *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*

Scheduler
### Scheduler

**Description**
 *Schedule Processes*
**Help**
 *Schedule processes to be executed asynchronously*

Process Parameter
### Process Parameter


Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Default Parameter
### Default Parameter

**Description**
 *Default value of the parameter*
**Help**
 *The default value can be a variable like @#Date@*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Scheduler Recipient
### Scheduler Recipient

**Description**
 *Recipient of the Scheduler Notification*
**Help**
 *You can send the notifications to users or roles*

:::tip
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.
:::
Fields
## Fields


Client
### Client

**Description**
 *Client/Tenant for this installation.*
**Help**
 *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*

Organization
### Organization

**Description**
 *Organizational entity within client*
**Help**
 *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*

Scheduler
### Scheduler

**Description**
 *Schedule Processes*
**Help**
 *Schedule processes to be executed asynchronously*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

User/Contact
### User/Contact

**Description**
 *User within the system - Internal or Business Partner Contact*
**Help**
 *The User identifies a unique user in the system. This could be an internal user or a business partner contact*

Role
### Role

**Description**
 *Responsibility Role*
**Help**
 *The Role determines security and access a user who has this Role will have in the System.*

Log
### Log

**Description**
 *Scheduler Log*
**Help**
 *Result of the execution of the Scheduler*

:::tip
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.
:::
Fields
## Fields


Client
### Client

**Description**
 *Client/Tenant for this installation.*
**Help**
 *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*

Organization
### Organization

**Description**
 *Organizational entity within client*
**Help**
 *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*

Scheduler
### Scheduler

**Description**
 *Schedule Processes*
**Help**
 *Schedule processes to be executed asynchronously*

Created
### Created

**Description**
 *Date this record was created*
**Help**
 *The Created field indicates the date that this record was created.*

Summary
### Summary

**Description**
 *Textual summary of this request*
**Help**
 *The Summary allows free form text entry of a recap of this request.*

Error
### Error

**Description**
 *An Error occurred in the execution*

Reference
### Reference

**Description**
 *Reference for this record*
**Help**
 *The Reference displays the source document number.*

Text Message
### Text Message

**Description**
 *Text Message*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*
