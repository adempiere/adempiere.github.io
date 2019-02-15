
Project Processor
# Project Processor


Define Project Processors

Help
## Help

The Project Processor Window allows you to define different processes that you want to occur and the frequency and timing of these processes  A Project Processor can be just for a specific Project Type or for all.

Window Type
### Window Type

**Maintain**

:::tip
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
:::

Tabs
## Tabs


Project Processor
### Project Processor

**Description**
 *Project Processor*
**Help**
 *The Project Processor Tab allows you to define processes that you want to occur and the frequency and timing of these processes. If no other user is found, the items are assigned to the supervisor. A Project Processor can be just for a specific Project Type or for all.*

:::tip
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
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

Project Type
### Project Type

**Description**
 *Type of the project*
**Help**
 *Type of the project with optional phases of the project with standard performance information*

Project Task Category
### Project Task Category

**Description**
 *Set Category for project task*

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

Alert after Days Due
### Alert after Days Due

**Description**
 *Send email alert after number of days due (0=no alerts)*
**Help**
 *Send an email alert after the item is Due (after Date Next Action). If set to zero, no alert is sent.*

Reminder Days
### Reminder Days

**Description**
 *Days between sending Reminder Emails for a due or inactive Document*
**Help**
 *When a document is due for too long without activity, a reminder is sent. 0 means no reminders.
The Remind Days are the days when the next email reminder is sent.*

Escalate after Days Due
### Escalate after Days Due

**Description**
 *Escalation to superior after number of due days (0 = no)*
**Help**
 *The item will be escalated and assigned to the supervisor after the number of days over due. If 0, there is no escalation.*

Supervisor
### Supervisor

**Description**
 *Supervisor for this user/organization - used for escalation and approval*
**Help**
 *The Supervisor indicates who will be used for forwarding and escalating issues for this user - or for approvals.*

Inactivity Alert Days
### Inactivity Alert Days

**Description**
 *Send Alert when there is no activity after days (0= no alert)*
**Help**
 *An email alert is sent when the request shows no activity for the number of days defined.*

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

Log
### Log


:::tip
The Read Only indicates that this field may only be Read.  It may not be updated.
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

Project Processor
### Project Processor

**Description**
 *Processor for Project*
**Help**
 *Processor for Project*

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
