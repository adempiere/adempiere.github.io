
Transport Unit
# Transport Unit


Transport units are the building blocks used to create a vehicle. Depending on the type of transport unit, you can assign one or more compartments to a transport unit

Help
## Help

Some types of transport unit do not require a compartment. The characteristics for each transport unit are stored in master data records. Master data records are centrally available for use by the scheduling, loading confirmation, and delivery confirmation processes.

Window Type
### Window Type

**Maintain**


Tabs
## Tabs


Transport Unit
### Transport Unit

**Description**
 *Transport Unit*
**Help**
 *Transport units are the building blocks used to create a vehicle. Depending on the type of transport unit, you can assign one or more compartments to a transport unit*

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

Image
### Image

**Description**
 *Image or Icon*
**Help**
 *Images and Icon can be used to display supported graphic formats (gif, jpg, png).
You can either load the image (in the database) or point to a graphic via a URI (i.e. it can point to a resource, http address)*

Search Key
### Search Key

**Description**
 *Search key for the record in the format required - must be unique*
**Help**
 *A search key allows you a fast method of finding a particular record.
If you leave the search key empty, the system automatically creates a numeric number.  The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*

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

Document Note
### Document Note

**Description**
 *Additional information for a Document*
**Help**
 *The Document Note is used for recording any additional information regarding this product.*

Comment/Help
### Comment/Help

**Description**
 *Comment or Hint*
**Help**
 *The Help field contains a hint, comment or help about the use of this item.*

Transport Unit Type
### Transport Unit Type


Transport Status
### Transport Status

**Description**
 *Transport unit status*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Transport Compatibility Group
### Transport Compatibility Group


Volume Unit of Measure
### Volume Unit of Measure


Volume
### Volume

**Description**
 *Volume of a product*
**Help**
 *The Volume indicates the volume of the product in the Volume UOM of the Client*

Minimum Volume
### Minimum Volume


Maximum Volume
### Maximum Volume


Dimension Unit of Measure
### Dimension Unit of Measure


Transport Length
### Transport Length


Transport Width
### Transport Width


Transport Height
### Transport Height


Weight Unit of Measure
### Weight Unit of Measure


Weight
### Weight

**Description**
 *Weight of a product*
**Help**
 *The Weight indicates the weight  of the product in the Weight UOM of the Client*

Minimum Weight
### Minimum Weight

**Description**
 *Minimum Weight of a product*
**Help**
 *The Minimum Weight indicates the weight  of the product in the Weight UOM of the Client*

Maximum Weight
### Maximum Weight


Unladen Weight
### Unladen Weight


Number of axles
### Number of axles


Carrier Number
### Carrier Number


Transport Unit Copy
### Transport Unit Copy

**Description**
 *Allows Copy other Transport Unit*

Transport Unit
### Transport Unit


Compartment Assignment
### Compartment Assignment

**Description**
 *Compartment Assignment*

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

Transport Unit
### Transport Unit


Sequence
### Sequence

**Description**
 *Method of ordering records; lowest number comes first*
**Help**
 *The Sequence indicates the order of records*

Transport Compartment
### Transport Compartment


Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Asset
### Asset

**Description**
 *Asset*

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

Guarantee Date
### Guarantee Date

**Description**
 *Date when guarantee expires*
**Help**
 *Date when the normal guarantee or availability expires*

Create Date
### Create Date


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
 *Identifies the (ship from) address for this Business Partner*
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


Fixed Asset
### Fixed Asset

**Description**
 *Fixed Asset used internally or by customers*
**Help**
 *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*
