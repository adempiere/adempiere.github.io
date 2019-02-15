
Accounting Processor
# Accounting Processor


Maintain Accounting Processor and Logs

Help
## Help

Accounting Processor/Server Parameters and Logs

Window Type
### Window Type

**Maintain**

```
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
```

Tabs
## Tabs


Accounting Processor
### Accounting Processor

**Description**
 *Maintain Accounting Processor/Server Parameters*
**Help**
 *Accounting Processor/Server Parameters. If no account schema is selected, all accounting schema are processed. If no transaction table is selected, accounting for all transaction is created.*

```
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.
```
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

Accounting Schema
### Accounting Schema

**Description**
 *Rules for accounting*
**Help**
 *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*

Table
### Table

**Description**
 *Database Table information*
**Help**
 *The Database Table provides the information of the table definition*

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

Log
### Log

**Description**
 *Result of the execution of the Accounting Processor*
**Help**
 *Result of the execution of the Accounting Processor*

```
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.
```
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

Accounting Processor
### Accounting Processor

**Description**
 *Accounting Processor/Server Parameters*
**Help**
 *Accounting Processor/Server Parameters*

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
