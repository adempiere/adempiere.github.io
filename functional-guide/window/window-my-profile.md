
My Profile
# My Profile


My user information

Window Type
### Window Type

**Maintain**

```
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
```

Tabs
## Tabs


User Contact
### User Contact

**Description**
 *Maintain User or Business Partner Contact*
**Help**
 *The User Tab defines the log in for Users who have access to the system.  For application access, users need to have a role assigned.*

```
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
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

Comments
### Comments

**Description**
 *Comments or additional information*
**Help**
 *The Comments field allows for free form entry of additional information.*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

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

User PIN
### User PIN


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

Webstore User
### Webstore User

**Description**
 *Is a user for Webstore*
**Help**
 *It is created from Webstore*

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

RecentItems Max Saved
### RecentItems Max Saved


RecentItems Max Shown
### RecentItems Max Shown


User Mail
### User Mail

**Description**
 *Mail sent to the user*
**Help**
 *Archive of mails sent to users*

```
The tab with advanced functionality is only displayed, if enabled in Tools>Preference.
The Read Only indicates that this field may only be Read.  It may not be updated.
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

