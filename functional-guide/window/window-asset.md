
Asset
# Asset


Asset used internally or by customers

Help
## Help

An asset is either created by purchasing or by delivering a product.  An asset can be used internally or be a customer asset.

Window Type
### Window Type

**Maintain**

:::tip
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
:::

Tabs
## Tabs


Asset
### Asset

**Description**
 *Asset used internally or by customers*
**Help**
 *An asset is either created by purchasing or by delivering a product.  An asset can be used internally or be a customer asset.*

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

Search Key
### Search Key

**Description**
 *Search key for the record in the format required - must be unique*
**Help**
 *A search key allows you a fast method of finding a particular record.
If you leave the search key empty, the system automatically creates a numeric number.  The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*

Inventory No
### Inventory No


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

Comment/Help
### Comment/Help

**Description**
 *Comment or Hint*
**Help**
 *The Help field contains a hint, comment or help about the use of this item.*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Parent Asset
### Parent Asset


Asset Group
### Asset Group

**Description**
 *Group of Assets*
**Help**
 *The group of assets determines default accounts.  If an asset group is selected in the product category, assets are created when delivering the asset.*

Version No
### Version No

**Description**
 *Version Number*

Product
### Product

**Description**
 *Product, Service, Item*
**Help**
 *Identifies an item which is either purchased or sold in this organization.*

Attribute Set Instance
### Attribute Set Instance

**Description**
 *Product Attribute Set Instance*
**Help**
 *The values of the actual Product Attribute Instances.  The product level attributes are defined on Product level.*

Serial No
### Serial No

**Description**
 *Product Serial Number*
**Help**
 *The Serial Number identifies a tracked, warranted product.  It can only be used when the quantity is 1.*

Manufactured Year
### Manufactured Year


Lot No
### Lot No

**Description**
 *Lot number (alphanumeric)*
**Help**
 *The Lot Number indicates the specific lot that a product was part of.*

In Service Date
### In Service Date

**Description**
 *Date when Asset was put into service*
**Help**
 *The date when the asset was put into service - usually used as start date for depreciation.*

Guarantee Date
### Guarantee Date

**Description**
 *Date when guarantee expires*
**Help**
 *Date when the normal guarantee or availability expires*

Create Date
### Create Date


Revaluation Date
### Revaluation Date


Project
### Project

**Description**
 *Financial Project*
**Help**
 *A Project allows you to track and control internal or external activities.*

Activity
### Activity

**Description**
 *Business Activity*
**Help**
 *Activities indicate tasks that are performed and used to utilize Activity based Costing*

In Possession
### In Possession

**Description**
 *The asset is in the possession of the organization*
**Help**
 *Assets which are not in possession are e.g. at Customer site and may or may not be owned by the company.*

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

User/Contact
### User/Contact

**Description**
 *User within the system - Internal or Business Partner Contact*
**Help**
 *The User identifies a unique user in the system. This could be an internal user or a business partner contact*

Locator
### Locator

**Description**
 *Warehouse Locator*
**Help**
 *The Locator indicates where in a Warehouse a product is located.*

BPartner (Agent)
### BPartner (Agent)

**Description**
 *Business Partner (Agent or Sales Rep)*

Address
### Address

**Description**
 *Location or Address*
**Help**
 *The Location / Address field defines the location of an entity.*

Location comment
### Location comment

**Description**
 *Additional comments or remarks concerning the location*

Owned
### Owned

**Description**
 *The asset is owned by the organization*
**Help**
 *The asset may not be in possession, but the asset is legally owned by the organization*

Lessor
### Lessor

**Description**
 *The Business Partner who rents or leases*

Lease Termination
### Lease Termination

**Description**
 *Lease Termination Date*
**Help**
 *Last Date of Lease*

Depreciate
### Depreciate

**Description**
 *The asset will be depreciated*
**Help**
 *The asset is used internally and will be depreciated*

Fully depreciated
### Fully depreciated

**Description**
 *The asset is fully depreciated*
**Help**
 *The asset costs are fully amortized.*

Life use
### Life use

**Description**
 *Units of use until the asset is not usable anymore*
**Help**
 *Life use and the actual use may be used to calculate the depreciation*

Use units
### Use units

**Description**
 *Currently used units of the assets*

Last Maintenance
### Last Maintenance

**Description**
 *Last Maintenance Date*

Last Unit
### Last Unit

**Description**
 *Last Maintenance Unit*

Last Note
### Last Note

**Description**
 *Last Maintenance Note*

Next Maintenence
### Next Maintenence

**Description**
 *Next Maintenence Date*

Next Unit
### Next Unit

**Description**
 *Next Maintenence Unit*

Asset Status
### Asset Status


Activation Date
### Activation Date


Asset Depreciation Date
### Asset Depreciation Date

**Description**
 *Date of last depreciation*
**Help**
 *Date of the last deprecation, if the asset is used internally and depreciated.*

Disposed
### Disposed

**Description**
 *The asset is disposed*
**Help**
 *The asset is no longer used and disposed*

Asset Disposal Date
### Asset Disposal Date

**Description**
 *Date when the asset is/was disposed*

Product
### Product


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

Fixed Asset
### Fixed Asset

**Description**
 *Fixed Asset used internally or by customers*
**Help**
 *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Product
### Product

**Description**
 *Product, Service, Item*
**Help**
 *Identifies an item which is either purchased or sold in this organization.*

Attribute Set Instance
### Attribute Set Instance

**Description**
 *Product Attribute Set Instance*
**Help**
 *The values of the actual Product Attribute Instances.  The product level attributes are defined on Product level.*

Fixed Asset Current Qty
### Fixed Asset Current Qty

**Description**
 *Fixed Asset Current Quantity*

Locator
### Locator

**Description**
 *Warehouse Locator*
**Help**
 *The Locator indicates where in a Warehouse a product is located.*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Asset Balances
### Asset Balances

**Description**
 *Asset Balance Report and Adjustments*

:::tip
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
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

Fixed Asset
### Fixed Asset

**Description**
 *Fixed Asset used internally or by customers*
**Help**
 *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Fixed Asset Cost
### Fixed Asset Cost

**Description**
 *Cost of acquisition of the Fixed Asset*

Posting Type
### Posting Type

**Description**
 *The type of posted amount for the transaction*
**Help**
 *The Posting Type indicates the type of amount (Actual, Budget, Reservation, Commitment, Statistical) the transaction.*

Asset Salvage Value
### Asset Salvage Value


Accumulated Depreciation
### Accumulated Depreciation


Accumulated Depreciation (fiscal)
### Accumulated Depreciation (fiscal)


Remaining Amt
### Remaining Amt


Remaining Amt (fiscal)
### Remaining Amt (fiscal)


SL Expense/Period
### SL Expense/Period


SL Expense/Period (fiscal)
### SL Expense/Period (fiscal)


Life periods (min)
### Life periods (min)


Life periods (max)
### Life periods (max)


Usable Life - Years
### Usable Life - Years

**Description**
 *Years of the usable life of the asset*

Use Life - Years (fiscal)
### Use Life - Years (fiscal)


Usable Life - Months
### Usable Life - Months

**Description**
 *Months of the usable life of the asset*

Use Life - Months (fiscal)
### Use Life - Months (fiscal)


Depreciate
### Depreciate

**Description**
 *The asset will be depreciated*
**Help**
 *The asset is used internally and will be depreciated*

Current Period
### Current Period


Account Date
### Account Date

**Description**
 *Accounting Date*
**Help**
 *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*

Update depreciation
### Update depreciation


Accounting Setup
### Accounting Setup

**Description**
 *Enter accounting setup information*

:::tip
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The Accounting Tab checkbox indicates if this window contains accounting information. To display accounting information, enable this in Tools>Preference and Role.
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

Accounting Schema
### Accounting Schema

**Description**
 *Rules for accounting*
**Help**
 *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*

Fixed Asset
### Fixed Asset

**Description**
 *Fixed Asset used internally or by customers*
**Help**
 *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*

Valid from
### Valid from

**Description**
 *Valid from including this date (first day)*
**Help**
 *The Valid From date indicates the first day of a date range*

Asset Salvage Value
### Asset Salvage Value


Posting Type
### Posting Type

**Description**
 *The type of posted amount for the transaction*
**Help**
 *The Posting Type indicates the type of amount (Actual, Budget, Reservation, Commitment, Statistical) the transaction.*

Depreciation
### Depreciation


Depreciation (fiscal)
### Depreciation (fiscal)


Asset Acct
### Asset Acct


Accumulated Depreciation Account
### Accumulated Depreciation Account


Depreciation Account
### Depreciation Account


Disposal Revenue Acct
### Disposal Revenue Acct


Disposal Loss Acct
### Disposal Loss Acct


Activation/Addition
### Activation/Addition

**Description**
 *Activation/Addition*

:::tip
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
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

Document No
### Document No

**Description**
 *Document sequence number of the document*
**Help**
 *The document number is usually automatically generated by the system and determined by the document type of the document. If the document is not saved, the preliminary number is displayed in "<>".

If the document type of your document has no automatic document sequence defined, the field is empty if you create a new document. This is for documents which usually have an external number (like vendor invoice).  If you leave the field empty, the system will generate a document number for you. The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*

Create Asset
### Create Asset


Fixed Asset
### Fixed Asset

**Description**
 *Fixed Asset used internally or by customers*
**Help**
 *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*

Document Date
### Document Date

**Description**
 *Date of the Document*
**Help**
 *The Document Date indicates the date the document was generated.  It may or may not be the same as the accounting date.*

Account Date
### Account Date

**Description**
 *Accounting Date*
**Help**
 *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*

Posting Type
### Posting Type

**Description**
 *The type of posted amount for the transaction*
**Help**
 *The Posting Type indicates the type of amount (Actual, Budget, Reservation, Commitment, Statistical) the transaction.*

Capital/Expense
### Capital/Expense


Source Type
### Source Type


Invoice
### Invoice

**Description**
 *Invoice Identifier*
**Help**
 *The Invoice Document.*

Invoice Line
### Invoice Line

**Description**
 *Invoice Detail Line*
**Help**
 *The Invoice Line uniquely identifies a single line of an Invoice.*

Match Invoice
### Match Invoice

**Description**
 *Match Shipment/Receipt to Invoice*

Shipment/Receipt Line
### Shipment/Receipt Line

**Description**
 *Line on Shipment or Receipt document*
**Help**
 *The Shipment/Receipt Line indicates a unique line in a Shipment/Receipt document*

Project
### Project

**Description**
 *Financial Project*
**Help**
 *A Project allows you to track and control internal or external activities.*

Charge
### Charge

**Description**
 *Additional document charges*
**Help**
 *The Charge indicates a type of Charge (Handling, Shipping, Restocking)*

Imported Fixed Asset
### Imported Fixed Asset


Product
### Product

**Description**
 *Product, Service, Item*
**Help**
 *Identifies an item which is either purchased or sold in this organization.*

Attribute Set Instance
### Attribute Set Instance

**Description**
 *Product Attribute Set Instance*
**Help**
 *The values of the actual Product Attribute Instances.  The product level attributes are defined on Product level.*

Locator
### Locator

**Description**
 *Warehouse Locator*
**Help**
 *The Locator indicates where in a Warehouse a product is located.*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Source Amount
### Source Amount


Asset value
### Asset value

**Description**
 *Book Value of the asset*

Entered Amount
### Entered Amount


Currency
### Currency

**Description**
 *The Currency for this record*
**Help**
 *Indicates the Currency to be used when processing or reporting on this record*

Fixed Asset Current Qty
### Fixed Asset Current Qty

**Description**
 *Fixed Asset Current Quantity*

Accumulated Depreciation
### Accumulated Depreciation


Accumulated Depreciation (fiscal)
### Accumulated Depreciation (fiscal)


Delta Use Life Years
### Delta Use Life Years


Delta Use Life Years (fiscal)
### Delta Use Life Years (fiscal)

**Description**
 *Delta Use Life Years (fiscal)*

Life periods (min)
### Life periods (min)


Life periods (max)
### Life periods (max)


Processed
### Processed

**Description**
 *The document has been processed*
**Help**
 *The Processed checkbox indicates that a document has been processed.*

Document Status
### Document Status

**Description**
 *The current status of the document*
**Help**
 *The Document Status indicates the status of a document at this time.  If you want to change the document status, use the Document Action field*

Asset Addition Process
### Asset Addition Process


Cost Details
### Cost Details

**Description**
 *Cost Detail*

:::tip
The Accounting Tab checkbox indicates if this window contains accounting information. To display accounting information, enable this in Tools>Preference and Role.
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

Fixed Asset
### Fixed Asset

**Description**
 *Fixed Asset used internally or by customers*
**Help**
 *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*

Posting Type
### Posting Type

**Description**
 *The type of posted amount for the transaction*
**Help**
 *The Posting Type indicates the type of amount (Actual, Budget, Reservation, Commitment, Statistical) the transaction.*

Capital/Expense
### Capital/Expense


Source Type
### Source Type


Journal Batch
### Journal Batch

**Description**
 *General Ledger Journal Batch*
**Help**
 *The General Ledger Journal Batch identifies a group of journals to be processed as a group.*

Invoice
### Invoice

**Description**
 *Invoice Identifier*
**Help**
 *The Invoice Document.*

Line No
### Line No

**Description**
 *Unique line for this document*
**Help**
 *Indicates the unique line for a document.  It will also control the display order of the lines within a document.*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Asset value
### Asset value

**Description**
 *Book Value of the asset*

Fixed Asset Current Qty
### Fixed Asset Current Qty

**Description**
 *Fixed Asset Current Quantity*

Disposal
### Disposal


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

Fixed Asset
### Fixed Asset

**Description**
 *Fixed Asset used internally or by customers*
**Help**
 *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*

Disposed Method
### Disposed Method


Disposed Date
### Disposed Date


Document Date
### Document Date

**Description**
 *Date of the Document*
**Help**
 *The Document Date indicates the date the document was generated.  It may or may not be the same as the accounting date.*

Account Date
### Account Date

**Description**
 *Accounting Date*
**Help**
 *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*

Asset Proceeds
### Asset Proceeds


Asset Trade
### Asset Trade


Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Processed
### Processed

**Description**
 *The document has been processed*
**Help**
 *The Processed checkbox indicates that a document has been processed.*

Asset Usage
### Asset Usage

**Description**
 *Record Asset Usage*

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

Fixed Asset
### Fixed Asset

**Description**
 *Fixed Asset used internally or by customers*
**Help**
 *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*

UseDate
### UseDate


Use units
### Use units

**Description**
 *Currently used units of the assets*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Delivery
### Delivery

**Description**
 *Delivery or availability*
**Help**
 *Record of delivery or availability*

:::tip
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
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

Fixed Asset
### Fixed Asset

**Description**
 *Fixed Asset used internally or by customers*
**Help**
 *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*

Product Download
### Product Download

**Description**
 *Product downloads*
**Help**
 *Define download for a product. If the product is an asset, the user can download the data.*

Movement Date
### Movement Date

**Description**
 *Date a product was moved in or out of inventory*
**Help**
 *The Movement Date indicates the date that a product moved in or out of inventory.  This is the result of a shipment, receipt or inventory movement.*

User/Contact
### User/Contact

**Description**
 *User within the system - Internal or Business Partner Contact*
**Help**
 *The User identifies a unique user in the system. This could be an internal user or a business partner contact*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Version No
### Version No

**Description**
 *Version Number*

Lot No
### Lot No

**Description**
 *Lot number (alphanumeric)*
**Help**
 *The Lot Number indicates the specific lot that a product was part of.*

Serial No
### Serial No

**Description**
 *Product Serial Number*
**Help**
 *The Serial Number identifies a tracked, warranted product.  It can only be used when the quantity is 1.*

Shipment/Receipt Line
### Shipment/Receipt Line

**Description**
 *Line on Shipment or Receipt document*
**Help**
 *The Shipment/Receipt Line indicates a unique line in a Shipment/Receipt document*

EMail Address
### EMail Address

**Description**
 *Electronic Mail Address*
**Help**
 *The Email Address is the Electronic Mail ID for this User and should be fully qualified (e.g. joe.smith@company.com). The Email Address is used to access the self service application functionality from the web.*

Message ID
### Message ID

**Description**
 *EMail Message ID*
**Help**
 *SMTP Message ID for tracking purposes*

Delivery Confirmation
### Delivery Confirmation

**Description**
 *EMail Delivery confirmation*

URL
### URL

**Description**
 *Full URL address - e.g. http://www.adempiere.org*
**Help**
 *The URL defines an fully qualified web address like http://www.adempiere.org*

Referrer
### Referrer

**Description**
 *Referring web address*

Remote Addr
### Remote Addr

**Description**
 *Remote Address*
**Help**
 *The Remote Address indicates an alternative or external address.*

Remote Host
### Remote Host

**Description**
 *Remote host Info*

Asset History
### Asset History

**Description**
 *Detail asset transaction history*

:::tip
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The Accounting Tab checkbox indicates if this window contains accounting information. To display accounting information, enable this in Tools>Preference and Role.
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

Fixed Asset
### Fixed Asset

**Description**
 *Fixed Asset used internally or by customers*
**Help**
 *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*

Details
### Details


Posting Type
### Posting Type

**Description**
 *The type of posted amount for the transaction*
**Help**
 *The Posting Type indicates the type of amount (Actual, Budget, Reservation, Commitment, Statistical) the transaction.*

ChangeType
### ChangeType


Created
### Created

**Description**
 *Date this record was created*
**Help**
 *The Created field indicates the date that this record was created.*

Updated By
### Updated By

**Description**
 *User who updated this records*
**Help**
 *The Updated By field indicates the user who updated this record.*

Accounting Schema
### Accounting Schema

**Description**
 *Rules for accounting*
**Help**
 *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*

A_Period_Start
### A_Period_Start


A_Period_End
### A_Period_End


DepreciationType
### DepreciationType


A_Depreciation_Manual_Amount
### A_Depreciation_Manual_Amount


A_Depreciation_Manual_Period
### A_Depreciation_Manual_Period


Variable Percent
### Variable Percent


A_Depreciation_Table_Header_ID
### A_Depreciation_Table_Header_ID


Calculation Type
### Calculation Type


Spread Type
### Spread Type


ConventionType
### ConventionType


Asset Salvage Value
### Asset Salvage Value


Split Percent
### Split Percent


Owned
### Owned

**Description**
 *The asset is owned by the organization*
**Help**
 *The asset may not be in possession, but the asset is legally owned by the organization*

In Possession
### In Possession

**Description**
 *The asset is in the possession of the organization*
**Help**
 *Assets which are not in possession are e.g. at Customer site and may or may not be owned by the company.*

Depreciate
### Depreciate

**Description**
 *The asset will be depreciated*
**Help**
 *The asset is used internally and will be depreciated*

Fully depreciated
### Fully depreciated

**Description**
 *The asset is fully depreciated*
**Help**
 *The asset costs are fully amortized.*

Disposed
### Disposed

**Description**
 *The asset is disposed*
**Help**
 *The asset is no longer used and disposed*

A_Reval_Cal_Method
### A_Reval_Cal_Method


ChangeAmt
### ChangeAmt


Asset value
### Asset value

**Description**
 *Book Value of the asset*

AssetBookValueAmt
### AssetBookValueAmt


AssetAccumDepreciationAmt
### AssetAccumDepreciationAmt


Market value Amount
### Market value Amount

**Description**
 *Market value of the asset*
**Help**
 *For reporting, the market value of the asset*

A_QTY_Original
### A_QTY_Original


Fixed Asset Current Qty
### Fixed Asset Current Qty

**Description**
 *Fixed Asset Current Quantity*

Account Date
### Account Date

**Description**
 *Accounting Date*
**Help**
 *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*

Create Date
### Create Date


In Service Date
### In Service Date

**Description**
 *Date when Asset was put into service*
**Help**
 *The date when the asset was put into service - usually used as start date for depreciation.*

Asset Depreciation Date
### Asset Depreciation Date

**Description**
 *Date of last depreciation*
**Help**
 *Date of the last deprecation, if the asset is used internally and depreciated.*

Revaluation Date
### Revaluation Date


Asset Disposal Date
### Asset Disposal Date

**Description**
 *Date when the asset is/was disposed*

Usable Life - Years
### Usable Life - Years

**Description**
 *Years of the usable life of the asset*

Usable Life - Months
### Usable Life - Months

**Description**
 *Months of the usable life of the asset*

Life use
### Life use

**Description**
 *Units of use until the asset is not usable anymore*
**Help**
 *Life use and the actual use may be used to calculate the depreciation*

Use units
### Use units

**Description**
 *Currently used units of the assets*

Parent Asset
### Parent Asset


User/Contact
### User/Contact

**Description**
 *User within the system - Internal or Business Partner Contact*
**Help**
 *The User identifies a unique user in the system. This could be an internal user or a business partner contact*

Address
### Address

**Description**
 *Location or Address*
**Help**
 *The Location / Address field defines the location of an entity.*

Lot No
### Lot No

**Description**
 *Lot number (alphanumeric)*
**Help**
 *The Lot Number indicates the specific lot that a product was part of.*

Serial No
### Serial No

**Description**
 *Product Serial Number*
**Help**
 *The Serial Number identifies a tracked, warranted product.  It can only be used when the quantity is 1.*

Version No
### Version No

**Description**
 *Version Number*

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

Asset Acct
### Asset Acct


Depreciation Account
### Depreciation Account


Accumulated Depreciation Account
### Accumulated Depreciation Account


Disposal Revenue
### Disposal Revenue


Disposal Revenue Acct
### Disposal Revenue Acct


Disposal Loss Acct
### Disposal Loss Acct


Loss on Disposal
### Loss on Disposal


Reval Cost Offset Acct
### Reval Cost Offset Acct


Revaluation Cost Offset for Current Year
### Revaluation Cost Offset for Current Year


Revaluation Cost Offset for Prior Year
### Revaluation Cost Offset for Prior Year


Reval Cost Offset Prior Acct
### Reval Cost Offset Prior Acct


A_Reval_Accumdep_Offset_Cur
### A_Reval_Accumdep_Offset_Cur


Revaluation Accumulated Depreciation Offset for Current Year
### Revaluation Accumulated Depreciation Offset for Current Year


Revaluation Accumulated Depreciation Offset for Prior Year
### Revaluation Accumulated Depreciation Offset for Prior Year


A_Reval_Accumdep_Offset_Prior
### A_Reval_Accumdep_Offset_Prior


Reval Depexp Offset Acct
### Reval Depexp Offset Acct


Revaluation Expense Offs
### Revaluation Expense Offs


A_Asset_Change_ID
### A_Asset_Change_ID


Issue Project
### Issue Project

**Description**
 *Automatic Issue Reporting*

:::tip
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
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

Fixed Asset
### Fixed Asset

**Description**
 *Fixed Asset used internally or by customers*
**Help**
 *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*

Project
### Project

**Description**
 *Financial Project*
**Help**
 *A Project allows you to track and control internal or external activities.*

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

System Status
### System Status

**Description**
 *Status of the system - Support priority depends on system status*
**Help**
 *System status helps to prioritize support resources*

Statistics
### Statistics

**Description**
 *Information to help profiling the system for solving support issues*
**Help**
 *Profile information do not contain sensitive information and are used to support issue detection and diagnostics as well as general anonymous statistics*

Profile
### Profile

**Description**
 *Information to help profiling the system for solving support issues*
**Help**
 *Profile information do not contain sensitive information and are used to support issue detection and diagnostics*

Finance Information
### Finance Information

**Description**
 *Finace Information for the Asset*

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

Fixed Asset
### Fixed Asset

**Description**
 *Fixed Asset used internally or by customers*
**Help**
 *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Asset Finance Method
### Asset Finance Method


Business Partner
### Business Partner

**Description**
 *Identifies a Business Partner*
**Help**
 *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*

Contract Date
### Contract Date


Asset Expired Date
### Asset Expired Date


Asset Monthly Payment
### Asset Monthly Payment


Asset Due On
### Asset Due On


Purchase Option
### Purchase Option


Purchase Price
### Purchase Price


Purchase Option Credit
### Purchase Option Credit


Purchase Option Credit %
### Purchase Option Credit %


Text Message
### Text Message

**Description**
 *Text Message*

License Information
### License Information

**Description**
 *License Information for Asset*

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

Fixed Asset
### Fixed Asset

**Description**
 *Fixed Asset used internally or by customers*
**Help**
 *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*

Description
### Description


Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Account State
### Account State

**Description**
 *State of the Credit Card or Account holder*
**Help**
 *The State of the Credit Card or Account holder*

Issuing Agency
### Issuing Agency


Asset License No
### Asset License No


Asset License Fee
### Asset License Fee


Asset Renewal Date
### Asset Renewal Date


Insurance Information
### Insurance Information

**Description**
 *Insurance Information for asset*

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

Fixed Asset
### Fixed Asset

**Description**
 *Fixed Asset used internally or by customers*
**Help**
 *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*

Insurance Company
### Insurance Company


Asset Policy No
### Asset Policy No


Asset Renewal Date
### Asset Renewal Date


Asset Insurance Premium
### Asset Insurance Premium


Asset Replace Cost
### Asset Replace Cost


Asset Insurance Value
### Asset Insurance Value


Description
### Description


Tax Information
### Tax Information

**Description**
 *Tax information for asset*

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

Fixed Asset
### Fixed Asset

**Description**
 *Fixed Asset used internally or by customers*
**Help**
 *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*

Asset Tax Entity
### Asset Tax Entity


Account State
### Account State

**Description**
 *State of the Credit Card or Account holder*
**Help**
 *The State of the Credit Card or Account holder*

Asset New Used
### Asset New Used


Asset Finance Method
### Asset Finance Method


Asset Investment CR
### Asset Investment CR


Text Message
### Text Message

**Description**
 *Text Message*

Other Information
### Other Information

**Description**
 *Other information associated with asset*

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

Fixed Asset
### Fixed Asset

**Description**
 *Fixed Asset used internally or by customers*
**Help**
 *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*

A_User1
### A_User1


A_User10
### A_User10


A_User2
### A_User2


A_User11
### A_User11


A_User3
### A_User3


A_User12
### A_User12


A_User4
### A_User4


A_User13
### A_User13


A_User5
### A_User5


A_User14
### A_User14


A_User6
### A_User6


A_User15
### A_User15


A_User7
### A_User7


A_User8
### A_User8


A_User9
### A_User9


Description
### Description


Expense
### Expense


:::tip
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The Read Only indicates that this field may only be Read.  It may not be updated.
:::
Fields
## Fields


Entry Type
### Entry Type


Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Expense
### Expense


Expense (fiscal)
### Expense (fiscal)


Account (debit)
### Account (debit)

**Description**
 *Account used*
**Help**
 *The (natural) account used*

Account (credit)
### Account (credit)

**Description**
 *Account used*
**Help**
 *The (natural) account used*

Asset Period
### Asset Period


Account Date
### Account Date

**Description**
 *Accounting Date*
**Help**
 *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*

Posting Type
### Posting Type

**Description**
 *The type of posted amount for the transaction*
**Help**
 *The Posting Type indicates the type of amount (Actual, Budget, Reservation, Commitment, Statistical) the transaction.*

Fixed Asset
### Fixed Asset

**Description**
 *Fixed Asset used internally or by customers*
**Help**
 *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*

Processed
### Processed

**Description**
 *The document has been processed*
**Help**
 *The Processed checkbox indicates that a document has been processed.*

Comment/Help
### Comment/Help

**Description**
 *Comment or Hint*
**Help**
 *The Help field contains a hint, comment or help about the use of this item.*

Fixed Asset Cost
### Fixed Asset Cost

**Description**
 *Cost of acquisition of the Fixed Asset*

Delta Asset Cost
### Delta Asset Cost


Accumulated Depreciation
### Accumulated Depreciation


Accumulated Depreciation (delta)
### Accumulated Depreciation (delta)


Accumulated Depreciation (fiscal)
### Accumulated Depreciation (fiscal)


Accumulated Depreciation - fiscal (delta)
### Accumulated Depreciation - fiscal (delta)


Remaining Amt
### Remaining Amt


Remaining Amt (fiscal)
### Remaining Amt (fiscal)


Usable Life - Months
### Usable Life - Months

**Description**
 *Months of the usable life of the asset*

Use Life - Months (fiscal)
### Use Life - Months (fiscal)


Asset Addition
### Asset Addition


Asset Disposed
### Asset Disposed

