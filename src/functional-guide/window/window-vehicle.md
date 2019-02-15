
Vehicle
# Vehicle


A vehicle is the means by which you transport product from one location to another

Help
## Help

Each vehicle is unique and consists of a fixed number of transport units
Each transport unit is unique and consists of a fixed number of compartments
Each compartment is unique and is used as the basis to schedule and load product for transport.
Although the following figure uses a truck as an example, TD supports the following types of vehicles:
Trucks (road transport)
Trains (rail transport)
Ships (marine transport)
Barges (inland water transport)
Pipelines (pipeline transport)

Window Type
### Window Type

**Maintain**


Tabs
## Tabs


Vehicle
### Vehicle

**Description**
 *Vehicle*

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

Image
### Image

**Description**
 *Image or Icon*
**Help**
 *Images and Icon can be used to display supported graphic formats (gif, jpg, png).
You can either load the image (in the database) or point to a graphic via a URI (i.e. it can point to a resource, http address)*

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

Document Note
### Document Note

**Description**
 *Additional information for a Document*
**Help**
 *The Document Note is used for recording any additional information regarding this product.*

Fixed Asset
### Fixed Asset

**Description**
 *Fixed Asset used internally or by customers*
**Help**
 *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*

Transport Compatibility Group
### Transport Compatibility Group


Vehicle Type
### Vehicle Type


Vehicle Status
### Vehicle Status


Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

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


Number of compartments
### Number of compartments


Vehicle Copy
### Vehicle Copy


Vehicle
### Vehicle


Driver Assignment
### Driver Assignment


Requirement Assignment
### Requirement Assignment

**Description**
 *Process which will assignment Requirement to Vehicle*

License Assignment
### License Assignment

**Description**
 *Process which will assignment License*

Transport Requirement Assignment
### Transport Requirement Assignment


License Types Assignment
### License Types Assignment


Vehicle Asset
### Vehicle Asset

**Description**
 *Vehicle Asset*

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


Last Maintenance Use Unit
### Last Maintenance Use Unit


Last Maintenence Date
### Last Maintenence Date


Next Maintenance Use Unit
### Next Maintenance Use Unit


Fixed Asset
### Fixed Asset

**Description**
 *Fixed Asset used internally or by customers*
**Help**
 *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*

Product
### Product

**Description**
 *Define Product*
**Help**
 *The Product Tab defines each product and identifies it for use in price lists and orders. The Location is the default location when receiving the stored product.*

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

Comment/Help
### Comment/Help

**Description**
 *Comment or Hint*
**Help**
 *The Help field contains a hint, comment or help about the use of this item.*

Document Note
### Document Note

**Description**
 *Additional information for a Document*
**Help**
 *The Document Note is used for recording any additional information regarding this product.*

UOM
### UOM

**Description**
 *Unit of Measure*
**Help**
 *The UOM defines a unique non monetary Unit of Measure*

UPC/EAN
### UPC/EAN

**Description**
 *Bar Code (Universal Product Code or its superset European Article Number)*
**Help**
 *Use this field to enter the bar code for the product in any of the bar code symbologies (Codabar, Code 25, Code 39, Code 93, Code 128, UPC (A), UPC (E), EAN-13, EAN-8, ITF, ITF-14, ISBN, ISSN, JAN-13, JAN-8, POSTNET and FIM, MSI/Plessey, and Pharmacode)*

SKU
### SKU

**Description**
 *Stock Keeping Unit*
**Help**
 *The SKU indicates a user defined stock keeping unit.  It may be used for an additional bar code symbols or your own schema.*

Image URL
### Image URL

**Description**
 *URL of  image*
**Help**
 *URL of image; The image is not stored in the database, but retrieved at runtime. The image can be a gif, jpeg or png.*

Description URL
### Description URL

**Description**
 *URL for the description*

Download URL
### Download URL

**Description**
 *URL of the Download files*
**Help**
 *Semicolon separated list of URLs to be downloaded or distributed*

Discontinued
### Discontinued

**Description**
 *This product is no longer available*
**Help**
 *The Discontinued check box indicates a product that has been discontinued.*

Discontinued At
### Discontinued At

**Description**
 *Discontinued At indicates Date when product was discontinued*

Discontinued by
### Discontinued by

**Description**
 *Discontinued By*
**Help**
 *The Discontinued By indicates the individual who discontinued this product*

Product Category
### Product Category

**Description**
 *Category of a Product*
**Help**
 *Identifies the category which this product belongs to.  Product categories are used for pricing and selection.*

Freight Category
### Freight Category

**Description**
 *Category of the Freight*
**Help**
 *Freight Categories are used to calculate the Freight for the Shipper selected*

Product Classification
### Product Classification

**Description**
 *Classification of a Product*
**Help**
 *Identifies the classification which this product belongs to.*

Product Class
### Product Class

**Description**
 *Class of a Product*
**Help**
 *Identifies the Class which this product belongs to*

Product Group
### Product Group

**Description**
 *Group of a Product*
**Help**
 *Identifies the Group which this product belongs to.*

Part Type
### Part Type


Classification
### Classification

**Description**
 *Classification for grouping*
**Help**
 *The Classification can be used to optionally group products.*

Group1
### Group1


Group2
### Group2


Purchased
### Purchased

**Description**
 *Organization purchases this product*
**Help**
 *The Purchased check box indicates if this product is purchased by this organization.*

Locator
### Locator

**Description**
 *Warehouse Locator*
**Help**
 *The Locator indicates where in a Warehouse a product is located.*

Attribute Set Instance
### Attribute Set Instance

**Description**
 *Product Attribute Values*
**Help**
 *The values of the actual Product Attributes. Product Instance attributes are defined in the actual transactions.*

Driver Assignment
### Driver Assignment


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

Vehicle
### Vehicle


Sequence
### Sequence

**Description**
 *Method of ordering records; lowest number comes first*
**Help**
 *The Sequence indicates the order of records*

Driver
### Driver


Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Transport Assignment
### Transport Assignment

**Description**
 *Transport Assignment*

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

Vehicle
### Vehicle


Sequence
### Sequence

**Description**
 *Method of ordering records; lowest number comes first*
**Help**
 *The Sequence indicates the order of records*

Transport Unit
### Transport Unit


Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

License Assignment
### License Assignment

**Description**
 *License Assignment*

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

Vehicle
### Vehicle


Sequence
### Sequence

**Description**
 *Method of ordering records; lowest number comes first*
**Help**
 *The Sequence indicates the order of records*

License
### License


Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Requirement Assignment
### Requirement Assignment

**Description**
 *Requirement Assignment*

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

Vehicle
### Vehicle


Sequence
### Sequence

**Description**
 *Method of ordering records; lowest number comes first*
**Help**
 *The Sequence indicates the order of records*

Transport Requirement
### Transport Requirement


Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Valid
### Valid

**Description**
 *Element is valid*
**Help**
 *The element passed the validation check*
