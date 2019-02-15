
Web Project
# Web Project


Maintain Web Project (Content Management)

Help
## Help

At the level of the web project you define the project itself, it's domains and media servers. Each project needs to have at least one domain and one media server.

Window Type
### Window Type

**Maintain**

:::tip
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
:::

Tabs
## Tabs


Project
### Project

**Description**
 *A web project is the main datacontainer for Containers, URLs, Ads, Media etc.*
**Help**
 *A web project is the meta definition which will contain later on all data within the Web Content Management Project.*

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

Meta Author
### Meta Author

**Description**
 *Author of the content*
**Help**
 *Author of the content for the Containers Meta Data*

Meta Content Type
### Meta Content Type

**Description**
 *Defines the type of content i.e. "text/html; charset=UTF-8"*
**Help**
 *With this tag you can overwrite the type of content and how search engines will interpret it. You should keep in mind that this will not influence how the Server and Client interpret the content.*

Meta Copyright
### Meta Copyright

**Description**
 *Contains Copyright information for the content*
**Help**
 *This Tag contains detailed information about the content's copyright situation, how holds it for which timeframe etc.*

Meta Publisher
### Meta Publisher

**Description**
 *Meta Publisher defines the publisher of the content*
**Help**
 *As author and publisher must not be the same person this tag saves the responsible publisher for the content*

Meta RobotsTag
### Meta RobotsTag

**Description**
 *RobotsTag defines how search robots should handle this content*
**Help**
 *The Meta Robots Tag define on how a search engines robot should handle this page and the following ones. It defines two keywords: (NO)INDEX which defines whether or not to index this content and (NO)FOLLOW which defines whether or not to follow links. The most common combination is INDEX,FOLLOW which will force a search robot to index the content and follow links and images.*

Container Tree
### Container Tree

**Description**
 *Container Tree*
**Help**
 *Container Tree*

Stage Tree
### Stage Tree

**Description**
 *Stage Tree*
**Help**
 *Stage Tree*

Template Tree
### Template Tree

**Description**
 *Template Tree*
**Help**
 *Template Tree*

Media Tree
### Media Tree

**Description**
 *Media Tree*
**Help**
 *Media Tree*

Container
### Container

**Description**
 *View Web Container*
**Help**
 *View deployed Web Container Information.*

:::tip
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
null
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

Web Project
### Web Project

**Description**
 *A web project is the main data container for Containers, URLs, Ads, Media etc.*
**Help**
 *A web project is the meta definition which will contain later on all data within the Web Content Management Project.*

Template
### Template

**Description**
 *Template defines how content is displayed*
**Help**
 *A template describes how content should get displayed, it contains layout and maybe also scripts on how to handle the content*

Name
### Name

**Description**
 *Alphanumeric identifier of the entity*
**Help**
 *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*

Title
### Title

**Description**
 *Name this entity is referred to as*
**Help**
 *The Title indicates the name that an entity is referred to as.*

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

Summary Level
### Summary Level

**Description**
 *This is a summary entity*
**Help**
 *A summary entity represents a branch in a tree rather than an end-node. Summary entities are used for reporting and do not have own values.*

Web Container Type
### Web Container Type

**Description**
 *Web Container Type*
**Help**
 *This parameter defines the type of content for this container.*

External Link (URL)
### External Link (URL)

**Description**
 *External Link (URL) for the Container*
**Help**
 *External URL for the Container*

Container Link
### Container Link

**Description**
 *Link to another Container in the Web Project*
**Help**
 *Internal Link*

Relative URL
### Relative URL

**Description**
 *Contains the relative URL for the container*
**Help**
 *The relative URL is used together with the webproject domain to display the content*

Indexed
### Indexed

**Description**
 *Index the document for the internal search engine*
**Help**
 *For cross document search, the document can be indexed for faster search (Container, Document Type, Request Type)*

Secure content
### Secure content

**Description**
 *Defines whether content needs to get encrypted*
**Help**
 *If you select this parameter this container will only get delivered over a secure connection i.e. SSL etc. if no encryption can be found no content will be delivered*

Meta Author
### Meta Author

**Description**
 *Author of the content*
**Help**
 *Author of the content for the Containers Meta Data*

Meta Content Type
### Meta Content Type

**Description**
 *Defines the type of content i.e. "text/html; charset=UTF-8"*
**Help**
 *With this tag you can overwrite the type of content and how search engines will interpret it. You should keep in mind that this will not influence how the Server and Client interpret the content.*

Meta Language
### Meta Language

**Description**
 *Language HTML Meta Tag*

Meta Copyright
### Meta Copyright

**Description**
 *Contains Copyright information for the content*
**Help**
 *This Tag contains detailed information about the content's copyright situation, how holds it for which timeframe etc.*

Meta Description
### Meta Description

**Description**
 *Meta info describing the contents of the page*
**Help**
 *The Meta Description tag should contain a short description on the page content*

Meta Keywords
### Meta Keywords

**Description**
 *Contains the keywords for the content*
**Help**
 *Contains keyword info on the main search words this content is relevant to*

Meta Publisher
### Meta Publisher

**Description**
 *Meta Publisher defines the publisher of the content*
**Help**
 *As author and publisher must not be the same person this tag saves the responsible publisher for the content*

Meta RobotsTag
### Meta RobotsTag

**Description**
 *RobotsTag defines how search robots should handle this content*
**Help**
 *The Meta Robots Tag define on how a search engines robot should handle this page and the following ones. It defines two keywords: (NO)INDEX which defines whether or not to index this content and (NO)FOLLOW which defines whether or not to follow links. The most common combination is INDEX,FOLLOW which will force a search robot to index the content and follow links and images.*

Notice
### Notice

**Description**
 *Contains last write notice*
**Help**
 *Contains info on what changed with the last write*

Priority
### Priority

**Description**
 *Indicates if this request is of a high, medium or low priority.*
**Help**
 *The Priority indicates the importance of this request.*

Container Translation
### Container Translation

**Description**
 *View Container Translation*
**Help**
 *View deployed Web Container Translations*

:::tip
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The Translation Tab checkbox indicate if a tab contains translation information. To display translation information, enable this in Tools>Preference.
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

Web Container
### Web Container

**Description**
 *Web Container contains content like images, text etc.*
**Help**
 *A Container defines the abstract level around the content, it defines how the content gets displayed, indexed and stored.*

Language
### Language

**Description**
 *Language for this entity*
**Help**
 *The Language identifies the language to use for display and formatting*

Translated
### Translated

**Description**
 *This column is translated*
**Help**
 *The Translated checkbox indicates if this column is translated.*

Name
### Name

**Description**
 *Alphanumeric identifier of the entity*
**Help**
 *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*

Title
### Title

**Description**
 *Name this entity is referred to as*
**Help**
 *The Title indicates the name that an entity is referred to as.*

Meta Description
### Meta Description

**Description**
 *Meta info describing the contents of the page*
**Help**
 *The Meta Description tag should contain a short description on the page content*

Meta Keywords
### Meta Keywords

**Description**
 *Contains the keywords for the content*
**Help**
 *Contains keyword info on the main search words this content is relevant to*

Container Element
### Container Element

**Description**
 *View Web Container Element*
**Help**
 *View deployed Web Container Element*

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

Web Container
### Web Container

**Description**
 *Web Container contains content like images, text etc.*
**Help**
 *A Container defines the abstract level around the content, it defines how the content gets displayed, indexed and stored.*

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

Content HTML
### Content HTML

**Description**
 *Contains the content itself*
**Help**
 *Contains the content itself as HTML code. Should normally only use basic tags, no real layouting*

Container Element Translation
### Container Element Translation

**Description**
 *View Web Container Element Translation*
**Help**
 *View deployed Web Container Element Translation*

:::tip
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The Translation Tab checkbox indicate if a tab contains translation information. To display translation information, enable this in Tools>Preference.
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

Container Element
### Container Element

**Description**
 *Container element i.e. Headline, Content, Footer etc.*
**Help**
 *A container element defines the smallest definition of content, i.e. the headline, the content etc.*

Language
### Language

**Description**
 *Language for this entity*
**Help**
 *The Language identifies the language to use for display and formatting*

Translated
### Translated

**Description**
 *This column is translated*
**Help**
 *The Translated checkbox indicates if this column is translated.*

Content HTML
### Content HTML

**Description**
 *Contains the content itself*
**Help**
 *Contains the content itself as HTML code. Should normally only use basic tags, no real layouting*

Container T.Table
### Container T.Table

**Description**
 *View Container Template Table*
**Help**
 *Link to individual Record*

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

Web Container
### Web Container

**Description**
 *Web Container contains content like images, text etc.*
**Help**
 *A Container defines the abstract level around the content, it defines how the content gets displayed, indexed and stored.*

Template Table
### Template Table

**Description**
 *CM Template Table Link*
**Help**
 *Link a Template with a Table*

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

Record ID
### Record ID

**Description**
 *Direct internal record ID*
**Help**
 *The Record ID is the internal unique identifier of a record. Please note that zooming to the record may not be successful for Orders, Invoices and Shipment/Receipts as sometimes the Sales Order type is not known.*

Sql WHERE
### Sql WHERE

**Description**
 *Fully qualified SQL WHERE clause*
**Help**
 *The Where Clause indicates the SQL WHERE clause to use for record selection. The WHERE clause is added to the query. Fully qualified means "tablename.columnname".*

Other SQL Clause
### Other SQL Clause

**Description**
 *Other SQL Clause*
**Help**
 *Any other complete clause like GROUP BY, HAVING, ORDER BY, etc. after WHERE clause.*

Stage
### Stage

**Description**
 *Maintain Container Stage*
**Help**
 *Maintain Container Stage information.*

:::tip
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
null
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

Web Project
### Web Project

**Description**
 *A web project is the main data container for Containers, URLs, Ads, Media etc.*
**Help**
 *A web project is the meta definition which will contain later on all data within the Web Content Management Project.*

Template
### Template

**Description**
 *Template defines how content is displayed*
**Help**
 *A template describes how content should get displayed, it contains layout and maybe also scripts on how to handle the content*

Name
### Name

**Description**
 *Alphanumeric identifier of the entity*
**Help**
 *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*

Title
### Title

**Description**
 *Name this entity is referred to as*
**Help**
 *The Title indicates the name that an entity is referred to as.*

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

Summary Level
### Summary Level

**Description**
 *This is a summary entity*
**Help**
 *A summary entity represents a branch in a tree rather than an end-node. Summary entities are used for reporting and do not have own values.*

Web Container Type
### Web Container Type

**Description**
 *Web Container Type*
**Help**
 *This parameter defines the type of content for this container.*

External Link (URL)
### External Link (URL)

**Description**
 *External Link (URL) for the Container*
**Help**
 *External URL for the Container*

Container Link
### Container Link

**Description**
 *Stage Link to another Container in the Web Project*
**Help**
 *Internal Link*

Relative URL
### Relative URL

**Description**
 *Contains the relative URL for the container*
**Help**
 *The relative URL is used together with the webproject domain to display the content*

Indexed
### Indexed

**Description**
 *Index the document for the internal search engine*
**Help**
 *For cross document search, the document can be indexed for faster search (Container, Document Type, Request Type)*

Secure content
### Secure content

**Description**
 *Defines whether content needs to get encrypted*
**Help**
 *If you select this parameter this container will only get delivered over a secure connection i.e. SSL etc. if no encryption can be found no content will be delivered*

Meta Author
### Meta Author

**Description**
 *Author of the content*
**Help**
 *Author of the content for the Containers Meta Data*

Meta Content Type
### Meta Content Type

**Description**
 *Defines the type of content i.e. "text/html; charset=UTF-8"*
**Help**
 *With this tag you can overwrite the type of content and how search engines will interpret it. You should keep in mind that this will not influence how the Server and Client interpret the content.*

Meta Language
### Meta Language

**Description**
 *Language HTML Meta Tag*

Meta Copyright
### Meta Copyright

**Description**
 *Contains Copyright information for the content*
**Help**
 *This Tag contains detailed information about the content's copyright situation, how holds it for which timeframe etc.*

Meta Description
### Meta Description

**Description**
 *Meta info describing the contents of the page*
**Help**
 *The Meta Description tag should contain a short description on the page content*

Meta Keywords
### Meta Keywords

**Description**
 *Contains the keywords for the content*
**Help**
 *Contains keyword info on the main search words this content is relevant to*

Meta Publisher
### Meta Publisher

**Description**
 *Meta Publisher defines the publisher of the content*
**Help**
 *As author and publisher must not be the same person this tag saves the responsible publisher for the content*

Meta RobotsTag
### Meta RobotsTag

**Description**
 *RobotsTag defines how search robots should handle this content*
**Help**
 *The Meta Robots Tag define on how a search engines robot should handle this page and the following ones. It defines two keywords: (NO)INDEX which defines whether or not to index this content and (NO)FOLLOW which defines whether or not to follow links. The most common combination is INDEX,FOLLOW which will force a search robot to index the content and follow links and images.*

Priority
### Priority

**Description**
 *Indicates if this request is of a high, medium or low priority.*
**Help**
 *The Priority indicates the importance of this request.*

Notice
### Notice

**Description**
 *Contains last write notice*
**Help**
 *Contains info on what changed with the last write*

Modified
### Modified

**Description**
 *The record is modified*
**Help**
 *Indication that the record is modified*

Validate
### Validate

**Description**
 *Validate Staging Area*

Stage Translation
### Stage Translation

**Description**
 *Maintain Container Stage Translation*

:::tip
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The Translation Tab checkbox indicate if a tab contains translation information. To display translation information, enable this in Tools>Preference.
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

Web Container Stage
### Web Container Stage

**Description**
 *Web Container Stage contains the staging content like images, text etc.*
**Help**
 *A Container defines the abstract level around the content, it defines how the content get's displayed, indexed and stored.
The ID is related 1 to 1 to the container ID*

Language
### Language

**Description**
 *Language for this entity*
**Help**
 *The Language identifies the language to use for display and formatting*

Translated
### Translated

**Description**
 *This column is translated*
**Help**
 *The Translated checkbox indicates if this column is translated.*

Name
### Name

**Description**
 *Alphanumeric identifier of the entity*
**Help**
 *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*

Title
### Title

**Description**
 *Name this entity is referred to as*
**Help**
 *The Title indicates the name that an entity is referred to as.*

Meta Description
### Meta Description

**Description**
 *Meta info describing the contents of the page*
**Help**
 *The Meta Description tag should contain a short description on the page content*

Meta Keywords
### Meta Keywords

**Description**
 *Contains the keywords for the content*
**Help**
 *Contains keyword info on the main search words this content is relevant to*

Stage Element
### Stage Element

**Description**
 *Container Stage Element*

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

Web Container Stage
### Web Container Stage

**Description**
 *Web Container Stage contains the staging content like images, text etc.*
**Help**
 *A Container defines the abstract level around the content, it defines how the content get's displayed, indexed and stored.
The ID is related 1 to 1 to the container ID*

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

Content HTML
### Content HTML

**Description**
 *Contains the content itself*
**Help**
 *Contains the content itself as HTML code. Should normally only use basic tags, no real layouting*

Stage Element Translation
### Stage Element Translation

**Description**
 *Container Stage Element Translation*

:::tip
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The Translation Tab checkbox indicate if a tab contains translation information. To display translation information, enable this in Tools>Preference.
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

Container Stage Element
### Container Stage Element

**Description**
 *Container element i.e. Headline, Content, Footer etc.*
**Help**
 *A container element defines the smallest definition of content, i.e. the headline, the content etc.*

Language
### Language

**Description**
 *Language for this entity*
**Help**
 *The Language identifies the language to use for display and formatting*

Translated
### Translated

**Description**
 *This column is translated*
**Help**
 *The Translated checkbox indicates if this column is translated.*

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

Content HTML
### Content HTML

**Description**
 *Contains the content itself*
**Help**
 *Contains the content itself as HTML code. Should normally only use basic tags, no real layouting*

Stage T.Table
### Stage T.Table

**Description**
 *Maintain Container Stage Template Table*
**Help**
 *Link to individual Record*

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

Web Container Stage
### Web Container Stage

**Description**
 *Web Container Stage contains the staging content like images, text etc.*
**Help**
 *A Container defines the abstract level around the content, it defines how the content get's displayed, indexed and stored.
The ID is related 1 to 1 to the container ID*

Template Table
### Template Table

**Description**
 *CM Template Table Link*
**Help**
 *Link a Template with a Table*

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

Record ID
### Record ID

**Description**
 *Direct internal record ID*
**Help**
 *The Record ID is the internal unique identifier of a record. Please note that zooming to the record may not be successful for Orders, Invoices and Shipment/Receipts as sometimes the Sales Order type is not known.*

Sql WHERE
### Sql WHERE

**Description**
 *Fully qualified SQL WHERE clause*
**Help**
 *The Where Clause indicates the SQL WHERE clause to use for record selection. The WHERE clause is added to the query. Fully qualified means "tablename.columnname".*

Other SQL Clause
### Other SQL Clause

**Description**
 *Other SQL Clause*
**Help**
 *Any other complete clause like GROUP BY, HAVING, ORDER BY, etc. after WHERE clause.*

Template
### Template

**Description**
 *Web Project Template*
**Help**
 *CM Project Template*

:::tip
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
null
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

Web Project
### Web Project

**Description**
 *A web project is the main data container for Containers, URLs, Ads, Media etc.*
**Help**
 *A web project is the meta definition which will contain later on all data within the Web Content Management Project.*

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

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Summary Level
### Summary Level

**Description**
 *This is a summary entity*
**Help**
 *A summary entity represents a branch in a tree rather than an end-node. Summary entities are used for reporting and do not have own values.*

Use Ad
### Use Ad

**Description**
 *Whether or not this templates uses Ad's*
**Help**
 *This describe whether or not this Template will use Ad's*

Uses News
### Uses News

**Description**
 *Template or container uses news channels*
**Help**
 *This content (container or template) uses news channels*

Elements
### Elements

**Description**
 *Contains list of elements separated by CR*
**Help**
 *Contains a list of elements this template uses separated by a Carriage Return. Last line should be empty*

Included
### Included

**Description**
 *Defines whether this content / template is included into another one*
**Help**
 *Templates can be independent or included. Included Templates are also called subtemplates*

TemplateXST
### TemplateXST

**Description**
 *Contains the template code itself*
**Help**
 *Here we include the template code itself*

Valid
### Valid

**Description**
 *Element is valid*
**Help**
 *The element passed the validation check*

Validate
### Validate

**Description**
 *Validate Template*

Template Table
### Template Table

**Description**
 *Maintain Template Tables*
**Help**
 *Link a Template with a Table*

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

Template
### Template

**Description**
 *Template defines how content is displayed*
**Help**
 *A template describes how content should get displayed, it contains layout and maybe also scripts on how to handle the content*

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

Sql WHERE
### Sql WHERE

**Description**
 *Fully qualified SQL WHERE clause*
**Help**
 *The Where Clause indicates the SQL WHERE clause to use for record selection. The WHERE clause is added to the query. Fully qualified means "tablename.columnname".*

Other SQL Clause
### Other SQL Clause

**Description**
 *Other SQL Clause*
**Help**
 *Any other complete clause like GROUP BY, HAVING, ORDER BY, etc. after WHERE clause.*

Template Ad Category
### Template Ad Category

**Description**
 *Maintain Template Advertisement Category*
**Help**
 *Link a Template with an Advertisement Category*

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

Template
### Template

**Description**
 *Template defines how content is displayed*
**Help**
 *A template describes how content should get displayed, it contains layout and maybe also scripts on how to handle the content*

Advertisement Category
### Advertisement Category

**Description**
 *Advertisement Category like Banner Homepage*
**Help**
 *The advertisement category defines a container for ad's like for example all banners used on the homepage in rotation are stored in a category "Banner Homepage" etc.*

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

Media
### Media

**Description**
 *Media Elements*

:::tip
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
null
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

Web Project
### Web Project

**Description**
 *A web project is the main data container for Containers, URLs, Ads, Media etc.*
**Help**
 *A web project is the meta definition which will contain later on all data within the Web Content Management Project.*

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

Summary Level
### Summary Level

**Description**
 *This is a summary entity*
**Help**
 *A summary entity represents a branch in a tree rather than an end-node. Summary entities are used for reporting and do not have own values.*

Media Type
### Media Type

**Description**
 *Defines the media type for the browser*
**Help**
 *The browser and the media server need info on the type of content*

Image
### Image

**Description**
 *Image or Icon*
**Help**
 *Images and Icon can be used to display supported graphic formats (gif, jpg, png).
You can either load the image (in the database) or point to a graphic via a URI (i.e. it can point to a resource, http address)*

Content
### Content


Media Direct Deploy
### Media Direct Deploy


Domain
### Domain

**Description**
 *Maintain Web Project Domains*
**Help**
 *Link between the Web Project and the public URLs (Domains)*

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

Web Project
### Web Project

**Description**
 *A web project is the main data container for Containers, URLs, Ads, Media etc.*
**Help**
 *A web project is the meta definition which will contain later on all data within the Web Content Management Project.*

Web Container
### Web Container

**Description**
 *Web Container contains content like images, text etc.*
**Help**
 *A Container defines the abstract level around the content, it defines how the content gets displayed, indexed and stored.*

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

Fully Qualified Domain Name
### Fully Qualified Domain Name

**Description**
 *Fully Qualified Domain Name i.e. www.comdivision.com*
**Help**
 *This field contains the so called fully qualified domain name including host and domain, but not anything protocol specific like http or the document path.*

Media Server
### Media Server

**Description**
 *Web Project Media Server*
**Help**
 *Media Server for the web project*

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

Web Project
### Web Project

**Description**
 *A web project is the main data container for Containers, URLs, Ads, Media etc.*
**Help**
 *A web project is the meta definition which will contain later on all data within the Web Content Management Project.*

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

IP Address
### IP Address

**Description**
 *Defines the IP address to transfer data to*
**Help**
 *Contains info on the IP address to which we will transfer data*

Transfer passive
### Transfer passive

**Description**
 *FTP passive transfer*
**Help**
 *Should the transfer be run in passive mode?*

UserName
### UserName

**Description**
 *UserName / Login to use for login*
**Help**
 *UserName / Login to use for the login
Email of the responsible person for the system (registered in WebStore)*

Password
### Password

**Description**
 *Password of any length (case sensitive)*
**Help**
 *The Password for this User.  Passwords are required to identify authorized users.  For Adempiere Users, you can change the password via the Process "Reset Password".*

Folder
### Folder

**Description**
 *A folder on a local or remote system to store data into*
**Help**
 *We store files in folders, especially media files.*

URL
### URL

**Description**
 *Full URL address - e.g. http://www.adempiere.org*
**Help**
 *The URL defines an fully qualified web address like http://www.adempiere.org*
