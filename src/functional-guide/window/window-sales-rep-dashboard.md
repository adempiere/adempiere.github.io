
Sales Rep Dashboard
# Sales Rep Dashboard


The Sales Rep Dashboard provides a single location for managing sales opportunities

:::tip
Beta functionality is not fully tested or completed.
:::
Window Type
### Window Type

**Maintain**

:::tip
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
:::

Tabs
## Tabs


Dashboard
### Dashboard

**Description**
 *Sales Rep dashboard*

:::tip
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
null
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.
:::
Fields
## Fields


Sales Pipeline
### Sales Pipeline


Opportunity by Campaign
### Opportunity by Campaign


Sales Volume in 1.000
### Sales Volume in 1.000

**Description**
 *Total Volume of Sales in Thousands of Currency*
**Help**
 *The Sales Volume indicates the total volume of sales for a Business Partner.*

Open Requests
### Open Requests


Leads
### Leads

**Description**
 *Leads assigned to Sales Rep*

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

EMail Address
### EMail Address

**Description**
 *Electronic Mail Address*
**Help**
 *The Email Address is the Electronic Mail ID for this User and should be fully qualified (e.g. joe.smith@company.com). The Email Address is used to access the self service application functionality from the web.*

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

Address
### Address

**Description**
 *Location or Address*
**Help**
 *The Location / Address field defines the location of an entity.*

Title
### Title

**Description**
 *Name this entity is referred to as*
**Help**
 *The Title indicates the name that an entity is referred to as.*

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

Position
### Position

**Description**
 *Job Position*

Birthday
### Birthday

**Description**
 *Birthday or Anniversary day*
**Help**
 *Birthday or Anniversary day*

Last Contact
### Last Contact

**Description**
 *Date this individual was last contacted*
**Help**
 *The Last Contact indicates the date that this Business Partner Contact was last contacted.*

Last Result
### Last Result

**Description**
 *Result of last contact*
**Help**
 *The Last Result identifies the result of the last contact made.*

Campaign
### Campaign

**Description**
 *Marketing Campaign*
**Help**
 *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*

Sales Representative
### Sales Representative

**Description**
 *Sales Representative or Company Agent*
**Help**
 *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*

Lead Source
### Lead Source

**Description**
 *The source of this lead/opportunity*

Lead Source Description
### Lead Source Description

**Description**
 *Additional information on the source of this lead/opportunity*

Lead Status
### Lead Status

**Description**
 *The status of this lead/opportunity in the sales cycle*

Lead Status Description
### Lead Status Description

**Description**
 *Additional information on the status of this lead/opportunity*

Opportunities
### Opportunities

**Description**
 *Opportunities assigned to Sales Rep*

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

Document No
### Document No

**Description**
 *Document sequence number of the document*
**Help**
 *The document number is usually automatically generated by the system and determined by the document type of the document. If the document is not saved, the preliminary number is displayed in "<>".

If the document type of your document has no automatic document sequence defined, the field is empty if you create a new document. This is for documents which usually have an external number (like vendor invoice).  If you leave the field empty, the system will generate a document number for you. The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*

Business Partner
### Business Partner

**Description**
 *Identifies a Business Partner*
**Help**
 *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*

User/Contact
### User/Contact

**Description**
 *User within the system - Internal or Business Partner Contact*
**Help**
 *The User identifies a unique user in the system. This could be an internal user or a business partner contact*

Campaign
### Campaign

**Description**
 *Marketing Campaign*
**Help**
 *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*

Sales Representative
### Sales Representative

**Description**
 *Sales Representative or Company Agent*
**Help**
 *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*

Sales Stage
### Sales Stage

**Description**
 *Stages of the sales process*
**Help**
 *Define what stages your sales process will move through*

Probability
### Probability


Expected Close Date
### Expected Close Date

**Description**
 *Expected Close Date*
**Help**
 *The Expected Close Date indicates the expected last or final date*

Opportunity Amount
### Opportunity Amount

**Description**
 *The estimated value of this opportunity.*

Weighted Amount
### Weighted Amount

**Description**
 *The amount adjusted by the probability.*

Currency
### Currency

**Description**
 *The Currency for this record*
**Help**
 *Indicates the Currency to be used when processing or reporting on this record*

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

Order
### Order

**Description**
 *Order*
**Help**
 *The Order is a control document.  The  Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*

Close Date
### Close Date

**Description**
 *Close Date*
**Help**
 *The Close Date indicates the last or final date*

Cost
### Cost

**Description**
 *Cost information*

Activities
### Activities

**Description**
 *Sales Rep Activities*

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

Sales Representative
### Sales Representative

**Description**
 *Sales Representative or Company Agent*
**Help**
 *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*

Activity Type
### Activity Type

**Description**
 *Type of activity, e.g. task, email, phone call*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

User/Contact
### User/Contact

**Description**
 *User within the system - Internal or Business Partner Contact*
**Help**
 *The User identifies a unique user in the system. This could be an internal user or a business partner contact*

Sales Opportunity
### Sales Opportunity


Comments
### Comments

**Description**
 *Comments or additional information*
**Help**
 *The Comments field allows for free form entry of additional information.*

Start Date
### Start Date

**Description**
 *First effective day (inclusive)*
**Help**
 *The Start Date indicates the first or starting date*

End Date
### End Date

**Description**
 *Last effective date (inclusive)*
**Help**
 *The End Date indicates the last date in this range.*

Complete
### Complete

**Description**
 *It is complete*
**Help**
 *Indication that this is complete*
