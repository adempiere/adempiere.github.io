
User
# User


Maintain Users of the system

Help
## Help

The User Window allows you to maintain User of the system.  Users can log into the system and have access to functionality via one or more roles.  A user can also be a business partner contact.

Window Type
### Window Type

**Maintain**

:::tip
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
:::

Tabs
## Tabs


User Contact
### User Contact

**Description**
 *Maintain User or Business Partner Contact*
**Help**
 *The User Tab defines the log in for Users who have access to the system.  For application access, users need to have a role assigned.*

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

Comments
### Comments

**Description**
 *Comments or additional information*
**Help**
 *The Comments field allows for free form entry of additional information.*

Business Partner
### Business Partner

**Description**
 *Identifies a Business Partner*
**Help**
 *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*

Partner Location
### Partner Location

**Description**
 *Identifies the (ship to) address for this Business Partner*
**Help**
 *The Partner address indicates the location of a Business Partner*

EMail Address
### EMail Address

**Description**
 *Electronic Mail Address*
**Help**
 *The Email Address is the Electronic Mail ID for this User and should be fully qualified (e.g. joe.smith@company.com). The Email Address is used to access the self service application functionality from the web.*

Title
### Title

**Description**
 *Name this entity is referred to as*
**Help**
 *The Title indicates the name that an entity is referred to as.*

Birthday
### Birthday

**Description**
 *Birthday or Anniversary day*
**Help**
 *Birthday or Anniversary day*

Phone
### Phone

**Description**
 *Identifies a telephone number*
**Help**
 *The Phone field identifies a telephone number*

2nd Phone
### 2nd Phone

**Description**
 *Identifies an alternate telephone number.*
**Help**
 *The 2nd Phone field identifies an alternate telephone number.*

Fax
### Fax

**Description**
 *Facsimile number*
**Help**
 *The Fax identifies a facsimile number for this Business Partner or  Location*

Notification Type
### Notification Type

**Description**
 *Type of Notifications*
**Help**
 *Emails or Notification sent out for Request Updates, etc.*

Position
### Position

**Description**
 *Job Position*

Is Project Manager
### Is Project Manager

**Description**
 *Is Project Manager*
**Help**
 *Is Project Manager indicates if the contact is assigned as project manager to a project*

Is Project Member
### Is Project Member

**Description**
 *Is Project Member*
**Help**
 *Is Project Member indicates if the contact is assigned to a project and will receive notifications of any project changes*

Login User
### Login User

**Help**
 *Define if the user can login*

Internal User
### Internal User

**Description**
 *Is just for use internal*

Search Key
### Search Key

**Description**
 *Search key for the record in the format required*
**Help**
 *7 bit lower case alpha numeric - max length 8 - can be used for operating system names.*

Password
### Password

**Description**
 *Password of any length (case sensitive)*
**Help**
 *The Password for this User.  Passwords are required to identify authorized users.  For Adempiere Users, you can change the password via the Process "Reset Password".*

User PIN
### User PIN


Webstore User
### Webstore User

**Description**
 *Is a user for Webstore*
**Help**
 *It is created from Webstore*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Full BP Access
### Full BP Access

**Description**
 *The user/contact has full access to Business Partner information and resources*
**Help**
 *If selected, the user has full access to the Business Partner (BP) information (Business Documents like Orders, Invoices - Requests) or resources (Assets, Downloads). If you deselect it, the user has no access rights unless, you explicitly grant it in tab "BP Access"*

EMail User ID
### EMail User ID

**Description**
 *User Name (ID) in the Mail System*
**Help**
 *The user name in the mail system is usually the string before the @ of your email address.  Required if the mail server requires authentification to send emails.*

EMail User Password
### EMail User Password

**Description**
 *Password of your email user id*
**Help**
 *Required if the mail server requires authentification to send emails.*

Supervisor
### Supervisor

**Description**
 *Supervisor for this user/organization - used for escalation and approval*
**Help**
 *The Supervisor indicates who will be used for forwarding and escalating issues for this user - or for approvals.*

LDAP User Name
### LDAP User Name

**Description**
 *User Name used for authorization via LDAP (directory) services*
**Help**
 *Optional LDAP system user name for the user. If not defined, the normal Name of the user is used. This allows to use the internal (LDAP) user id (e.g. jjanke) and the normal display name (e.g. Jorg Janke).  The LDAP User Name can also be used without LDAP enables (see system window).  This would allow to sign in as jjanke and use the display name of Jorg Janke.*

Trx Organization
### Trx Organization

**Description**
 *Performing or initiating organization*
**Help**
 *The organization which performs or initiates this transaction (for another organization).  The owning Organization may not be the transaction organization in a service bureau environment, with centralized services, and inter-organization transactions.*

Connection Profile
### Connection Profile

**Description**
 *How a Java Client connects to the server(s)*
**Help**
 *Depending on the connection profile, different protocols are used and tasks are performed on the server rather then the client. Usually the user can select different profiles, unless it is enforced by the User or Role definition. The User level profile overwrites the Role based profile.*

EMail Configuration
### EMail Configuration


Greeting
### Greeting

**Description**
 *Greeting to print on correspondence*
**Help**
 *The Greeting identifies the greeting to print on correspondence.*

EMail Verify
### EMail Verify

**Description**
 *Date Email was verified*

Last Contact
### Last Contact

**Description**
 *Date this individual was last contacted*
**Help**
 *The Last Contact indicates the date that this Business Partner Contact was last contacted.*

Verification Info
### Verification Info

**Description**
 *Verification information of EMail Address*
**Help**
 *The field contains additional information how the EMail Address has been verified*

Last Result
### Last Result

**Description**
 *Result of last contact*
**Help**
 *The Last Result identifies the result of the last contact made.*

HasRole
### HasRole

**Description**
 *Has Role Y/N*

RecentItems Max Saved
### RecentItems Max Saved


RecentItems Max Shown
### RecentItems Max Shown


User Roles
### User Roles

**Description**
 *User Roles*
**Help**
 *The User Roles Tab define the Roles each user may have.  The Roles will determine what windows, tasks, processes and workflows that a User has access to.*

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

Default
### Default

**Description**
 *Default value*
**Help**
 *The Default Checkbox indicates if this record will be used as a default value.*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

User Substitute
### User Substitute

**Description**
 *Substitute of the user*
**Help**
 *A user who can act for this user.*

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

User/Contact
### User/Contact

**Description**
 *User within the system - Internal or Business Partner Contact*
**Help**
 *The User identifies a unique user in the system. This could be an internal user or a business partner contact*

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

Substitute
### Substitute

**Description**
 *Entity which can be used in place of this entity*
**Help**
 *The Substitute identifies the entity to be used as a substitute for this entity.*

Valid from
### Valid from

**Description**
 *Valid from including this date (first day)*
**Help**
 *The Valid From date indicates the first day of a date range*

Valid to
### Valid to

**Description**
 *Valid to including this date (last day)*
**Help**
 *The Valid To date indicates the last day of a date range*

Org Assignment
### Org Assignment

**Description**
 *User Assigment to Organization*
**Help**
 *Assign Users to Organizations*

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

User/Contact
### User/Contact

**Description**
 *User within the system - Internal or Business Partner Contact*
**Help**
 *The User identifies a unique user in the system. This could be an internal user or a business partner contact*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Valid from
### Valid from

**Description**
 *Valid from including this date (first day)*
**Help**
 *The Valid From date indicates the first day of a date range*

Valid to
### Valid to

**Description**
 *Valid to including this date (last day)*
**Help**
 *The Valid To date indicates the last day of a date range*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Org Access
### Org Access

**Description**
 *Maintain User Org Access*
**Help**
 *Add the client and organizations the user has access to. Entries here are ignored, if in the Role, User Org Access is not selected or the role has access to all roles.
Note that access information is cached and requires re-login or reset of cache.*

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

User/Contact
### User/Contact

**Description**
 *User within the system - Internal or Business Partner Contact*
**Help**
 *The User identifies a unique user in the system. This could be an internal user or a business partner contact*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Read Only
### Read Only

**Description**
 *Field is read only*
**Help**
 *The Read Only indicates that this field may only be Read.  It may not be updated.*

User Mail
### User Mail

**Description**
 *Mail sent to the user*
**Help**
 *Archive of mails sent to users*

:::tip
The tab with advanced functionality is only displayed, if enabled in Tools>Preference.
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

User/Contact
### User/Contact

**Description**
 *User within the system - Internal or Business Partner Contact*
**Help**
 *The User identifies a unique user in the system. This could be an internal user or a business partner contact*

Mail Template
### Mail Template

**Description**
 *Text templates for mailings*
**Help**
 *The Mail Template indicates the mail template for return messages. Mail text can include variables.  The priority of parsing is User/Contact, Business Partner and then the underlying business object (like Request, Dunning, Workflow object).
So, @Name@ would resolve into the User name (if user is defined defined), then Business Partner name (if business partner is defined) and then the Name of the business object if it has a Name.
For Multi-Lingual systems, the template is translated based on the Business Partner's language selection.*

Mail Message
### Mail Message

**Description**
 *Web Store Mail Message Template*

Created
### Created

**Description**
 *Date this record was created*
**Help**
 *The Created field indicates the date that this record was created.*

Message ID
### Message ID

**Description**
 *EMail Message ID*
**Help**
 *SMTP Message ID for tracking purposes*

Subject
### Subject

**Description**
 *Email Message Subject*
**Help**
 *Subject of the EMail*

Mail Text
### Mail Text

**Description**
 *Text used for Mail message*
**Help**
 *The Mail Text indicates the text used for mail messages.*

Delivery Confirmation
### Delivery Confirmation

**Description**
 *EMail Delivery confirmation*

Delivered
### Delivered


Queries
### Queries

**Description**
 *View and maintain saved queries*

:::tip
The tab with advanced functionality is only displayed, if enabled in Tools>Preference.
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

User/Contact
### User/Contact

**Description**
 *User within the system - Internal or Business Partner Contact*
**Help**
 *The User identifies a unique user in the system. This could be an internal user or a business partner contact*

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

Table
### Table

**Description**
 *Database Table information*
**Help**
 *The Database Table provides the information of the table definition*

Validation code
### Validation code

**Description**
 *Validation Code*
**Help**
 *The Validation Code displays the date, time and message of the error.*

LDAP Access
### LDAP Access

**Description**
 *User Access via LDAP*

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

User/Contact
### User/Contact

**Description**
 *User within the system - Internal or Business Partner Contact*
**Help**
 *The User identifies a unique user in the system. This could be an internal user or a business partner contact*

Ldap Processor
### Ldap Processor

**Description**
 *LDAP Server to authenticate and authorize external systems based on Adempiere*
**Help**
 *The LDAP Server allows third party software (e.g. Apache) to use the users defined in the system to authenticate and authorize them.  There is only one server per Adempiere system.  The "o" is the Client key and the optional "ou" is the Interest Area key.*

Interest Area
### Interest Area

**Description**
 *Interest Area or Topic*
**Help**
 *Interest Areas reflect interest in a topic by a contact. Interest areas can be used for marketing campaigns.*

Created
### Created

**Description**
 *Date this record was created*
**Help**
 *The Created field indicates the date that this record was created.*

Error
### Error

**Description**
 *An Error occurred in the execution*

Summary
### Summary

**Description**
 *Textual summary of this request*
**Help**
 *The Summary allows free form text entry of a recap of this request.*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*
