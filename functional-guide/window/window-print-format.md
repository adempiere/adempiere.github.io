
Print Format
# Print Format


Maintain Print Format

Help
## Help

The print format determines how data is rendered for print.

Window Type
### Window Type

**Maintain**

```
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
```

Tabs
## Tabs


Print Format
### Print Format

**Description**
 *Maintain Print Format*
**Help**
 *The print format determines how data is rendered for print.*

```
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
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

Default
### Default

**Description**
 *Default value*
**Help**
 *The Default Checkbox indicates if this record will be used as a default value.*

Table
### Table

**Description**
 *Database Table information*
**Help**
 *The Database Table provides the information of the table definition*

Report View
### Report View

**Description**
 *View used to generate this report*
**Help**
 *The Report View indicates the view used to generate this report.*

Form
### Form

**Description**
 *If Selected, a Form is printed, if not selected a columnar List report*
**Help**
 *A form has individual elements with layout information (example: invoice, check)

A columnar list report has individual columns (example: list of invoices)*

Table Based
### Table Based

**Description**
 *Table based List Reporting*
**Help**
 *Table based columnar list reporting is invoked from the Window Report button*

Print Table Format
### Print Table Format

**Description**
 *Table Format in Reports*
**Help**
 *Print Table Format determines Fonts, Colors of  the printed Table*

Standard Header/Footer
### Standard Header/Footer

**Description**
 *The standard Header and Footer is used*
**Help**
 *If the standard header is not used, it must be explicitly defined.*

Print Parameters
### Print Parameters

**Description**
 *Print query parameters on list report*
**Help**
 *If selected, query parameters will be printed at the start of the report.*

Summary Level
### Summary Level

**Description**
 *This is a summary entity*
**Help**
 *A summary entity represents a branch in a tree rather than an end-node. Summary entities are used for reporting and do not have own values.*

Print Paper
### Print Paper

**Description**
 *Printer paper definition*
**Help**
 *Printer Paper Size, Orientation and Margins*

Printer Name
### Printer Name

**Description**
 *Name of the Printer*
**Help**
 *Internal (Operating System) Name of the Printer; Please mote that the printer name may be different on different clients. Enter a printer name, which applies to ALL clients (e.g. printer on a server). 
If none is entered, the default printer is used. You specify your default printer when you log in. You can also change the default printer in Preferences.*

Print Font
### Print Font

**Description**
 *Maintain Print Font*
**Help**
 *Font used for printing*

Print Color
### Print Color

**Description**
 *Color used for printing and display*
**Help**
 *Colors used for printing and display*

Header Margin
### Header Margin

**Description**
 *Margin of the Header in 1/72 of an inch*
**Help**
 *Distance from the top of the printable page to the start of the main content in 1/72 of an inch (point)*

Footer Margin
### Footer Margin

**Description**
 *Margin of the Footer in 1/72 of an inch*
**Help**
 *Distance from the bottom of the main content to the end of the printable page in 1/72 of an inch (point)*

Jasper Process
### Jasper Process

**Description**
 *The Jasper Process used by the printengine if any process defined*

Copy/Create
### Copy/Create

**Description**
 *Copy existing OR create Print Format from Table*
**Help**
 *Select either a table to create a print format [creates initial rough layout]
OR a print format to copy into the current print format [copies layout].*

Args
### Args


Classname
### Classname

**Description**
 *Java Classname*
**Help**
 *The Classname identifies the Java classname used by this report or process.*

Display Order
### Display Order

**Description**
 *Display Order of the Print Format Items*

```
null
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.
```
Sort Order
### Sort Order

**Description**
 *Sort Order of the Print Format Items*

```
null
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.
```
Format Item
### Format Item

**Description**
 *Print Format Item*
**Help**
 *Item in the print format maintaining layout information.  The following additional variables are available when printing:
@*Page@ - the current page number
* @*PageCount@ - the total number of pages
* @*MultiPageInfo@ - "Page x of y" - only printed if more than one page
* @*CopyInfo@ - if it is a copy of the document "Duplicate" is printed
* @*ReportName@ - name of the report
* @*Header@ - Full Header with user/client/org name and connection
* @*CurrentDate@ - the print date
* @*CurrentDateTime@ - the print time

The layoit logic for forms is: 
- if not printed: ignore 
- set New Line Position 
- new page 
- new line, if something was printed since last new line
- format item
- print it (if not null/empty selected)
(i.e. supress null does not prevent new line)*

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

Print Format
### Print Format

**Description**
 *Data Print Format*
**Help**
 *The print format determines how data is rendered for print.*

Sequence
### Sequence

**Description**
 *Method of ordering records; lowest number comes first*
**Help**
 *The Sequence indicates the order of records*

Name
### Name

**Description**
 *Alphanumeric identifier of the entity*
**Help**
 *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*

Print Text
### Print Text

**Description**
 *The label text to be printed on a document or correspondence.*
**Help**
 *The Label to be printed indicates the name that will be printed on a document or correspondence. The max length is 2000 characters.*

Print Label Suffix
### Print Label Suffix

**Description**
 *The label text to be printed on a document or correspondence after the field*
**Help**
 *The Label to be printed indicates the name that will be printed on a document or correspondence after the field. The max length is 60 characters.*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Centrally maintained
### Centrally maintained

**Description**
 *Information maintained in System Element table*
**Help**
 *The Centrally Maintained checkbox indicates if the Name, Description and Help maintained in 'System Element' table  or 'Window' table.*

Suppress Null
### Suppress Null

**Description**
 *Suppress columns or elements with NULL value*
**Help**
 *If a Form entry is NULL and if selected, the field (including label) is not printed. 
If all elements in a table column are NULL and if selected, the column is not printed.*

Suppress Repeats
### Suppress Repeats

**Description**
 *Suppress repeated elements in column.*
**Help**
 *Determines whether repeated elements in a column are repeated in a printed table.*

Display Logic
### Display Logic

**Description**
 *If the Field is displayed, the result determines if the field is actually displayed*
**Help**
 *format := {expression} [{logic} {expression}]*  
expression := @{context}@{operand}{value} or @{context}@{operand}{value}*  
logic := {|}|{&}
context := any global or window context 
value := strings or numbers
logic operators	:= AND or OR with the previous result from left to right 
operand := eq{=}, gt{&gt;}, le{&lt;}, not{~^!} 
Examples: 
@AD_Table_ID@=14 | @Language@!GERGER 
@PriceLimit@>10 | @PriceList@>@PriceActual@
@Name@>J
Strings may be in single quotes (optional)*

Format Type
### Format Type

**Description**
 *Print Format Type*
**Help**
 *The print format type determines what will be printed.*

Column
### Column

**Description**
 *Column in the table*
**Help**
 *Link to the database column of the table*

Line Width
### Line Width

**Description**
 *Width of the lines*

Format Pattern
### Format Pattern

**Description**
 *The pattern used to format a number or date.*
**Help**
 *A string complying with either Java SimpleDateFormat or DecimalFormat pattern syntax used to override the default presentation format of a date or number type field.*

Included Print Format
### Included Print Format

**Description**
 *Print format that is included here.*
**Help**
 *Included Print formats allow to e.g. Lines to Header records. The Column provides the parent link.*

Image Field
### Image Field

**Description**
 *The image is retrieved from the data column*
**Help**
 *The Image URL is retrieved from the data column*

Image attached
### Image attached

**Description**
 *The image to be printed is attached to the record*
**Help**
 *The image to be printed is stored in the database as attachment to this record. The image can be a gif, jpeg or png.*

Image URL
### Image URL

**Description**
 *URL of  image*
**Help**
 *URL of image; The image is not stored in the database, but retrieved at runtime. The image can be a gif, jpeg or png.*

Area
### Area

**Description**
 *Print Area*
**Help**
 *Print area of this item*

Barcode Type
### Barcode Type

**Description**
 *Type of barcode*

Print Barcode Text
### Print Barcode Text

**Description**
 *Print barcode text beneath symbol*

Relative Position
### Relative Position

**Description**
 *The item is relative positioned (not absolute)*
**Help**
 *The relative positioning of the item is determined by X-Z space and next line*

Set NL Position
### Set NL Position

**Description**
 *Set New Line Position*
**Help**
 *When enabled, the current x (horizontal) Position before printing the item is saved. The next New Line will use the saved x (horizontal) Position, enabling to print data in columns.
The setting is not restricted to an area (header, content, footer), allowing to align information also with Header and Footer with the Content.*

X Position
### X Position

**Description**
 *Absolute X (horizontal) position in 1/72 of an inch*
**Help**
 *Absolute X (horizontal) position in 1/72 of an inch*

Y Position
### Y Position

**Description**
 *Absolute Y (vertical) position in 1/72 of an inch*
**Help**
 *Absolute Y (vertical) position in 1/72 of an inch*

Next Line
### Next Line

**Description**
 *Print item on next line*
**Help**
 *If not selected, the item is printed on the same line*

Next Page
### Next Page

**Description**
 *The column is printed on the next page*
**Help**
 *Before printing this column, there will be a page break.*

Below Column
### Below Column

**Description**
 *Print this column below the column index entered*
**Help**
 *This column is printed in a second line below the content of the first line identified. Please be aware, that this is depends on the actual sequence. Enter a 1 to add the info below the first column.*

Line Alignment
### Line Alignment

**Description**
 *Line Alignment*
**Help**
 *For relative positioning, the line alignment*

Field Alignment
### Field Alignment

**Description**
 *Field Text Alignment*
**Help**
 *Alignment of field text. The default is determined by the data/display type: Numbers are right aligned, other data is left aligned*

X Space
### X Space

**Description**
 *Relative X (horizontal) space in 1/72 of an inch*
**Help**
 *Relative X (horizontal) space in 1/72 of an inch in relation to the end of the previous item.*

Y Space
### Y Space

**Description**
 *Relative Y (vertical) space in 1/72 of an inch*
**Help**
 *Relative Y (vertical) space in 1/72 of an inch in relation to the end of the previous item.*

Max Width
### Max Width

**Description**
 *Maximum Width in 1/72 if an inch - 0 = no restriction*
**Help**
 *Maximum width of the element in 1/72 of an inch (point). If zero (0), there is no width restriction.*

Fixed Width
### Fixed Width

**Description**
 *Column has a fixed width*
**Help**
 *The Column has a fixed width, independent from the content*

Shape Type
### Shape Type

**Description**
 *Type of the shape to be painted*

Max Height
### Max Height

**Description**
 *Maximum Height in 1/72 if an inch - 0 = no restriction*
**Help**
 *Maximum height of the element in 1/72 of an inch (point). If zero (0), there is no height restriction.*

One Line Only
### One Line Only

**Description**
 *If selected, only one line is printed*
**Help**
 *If the column has a width restriction, the text is broken into multiple lines. If One Line is selected, only the first line is printed.*

Fill Shape
### Fill Shape

**Description**
 *Fill the shape with the color selected*

Print Color
### Print Color

**Description**
 *Color used for printing and display*
**Help**
 *Colors used for printing and display*

Print Font
### Print Font

**Description**
 *Maintain Print Font*
**Help**
 *Font used for printing*

Arc Diameter
### Arc Diameter

**Description**
 *Arc Diameter for rounded Rectangles*
**Help**
 *Width of the horizontal/vertical diameter of the arc at the four corners*

Order by
### Order by

**Description**
 *Include in sort order*
**Help**
 *The records are ordered by the value of this column. If a column is used for grouping, it needs to be included in the sort order as well.*

Record Sort No
### Record Sort No

**Description**
 *Determines in what order the records are displayed*
**Help**
 *The Record Sort No indicates the ascending sort sequence of the records. If the number is negative, the records are sorted descending. 
Example: A tab with C_DocType_ID (1), DocumentNo (-2) will be sorted ascending by document type and descending by document number (SQL: ORDER BY C_DocType, DocumentNo DESC)*

Descending
### Descending

**Description**
 *Sort your data using a SQL Desc Order By statement*

Group by
### Group by

**Description**
 *After a group change, totals, etc. are printed*
**Help**
 *Grouping allows to print sub-totals. If a group changes, the totals are printed.  Group by columns need to be included in the sort order.*

Page break
### Page break

**Description**
 *Start with new page*
**Help**
 *Before printing this item, create a new page*

Calculate Sum (S)
### Calculate Sum (S)

**Description**
 *Calculate the Sum of numeric content or length*
**Help**
 *Calculate the Sum (S) of the data if the field is numeric, otherwise total sum length of the field.*

Running Total
### Running Total

**Description**
 *Create a running total (sum)*
**Help**
 *A running total creates a sum at the end of a page and on the top of the next page for all columns, which have a Sum function.  You should define running total only once per format.*

Calculate Count (¿)
### Calculate Count (¿)

**Description**
 *Count number of not empty elements*
**Help**
 *Calculate the total number (¿) of not empty (NULL) elements (maximum is the number of lines).*

Running Total Lines
### Running Total Lines

**Description**
 *Create Running Total Lines (page break) every x lines*
**Help**
 *When you want to print running totals, enter the number of lines per page after you want to create a running total line and page break. You should define running total only once per format.*

Calculate Minimum (¿)
### Calculate Minimum (¿)

**Description**
 *Calculate the minimum amount*
**Help**
 *Calculate the Minimum (¿) of the data if the field is numeric, otherwise minimum length of the field.*

Calculate Maximum (?)
### Calculate Maximum (?)

**Description**
 *Calculate the maximum amount*
**Help**
 *Calculate the Maximum (¿)  of the data if the field is numeric, otherwise maximum length of the field.*

Calculate Mean (µ)
### Calculate Mean (µ)

**Description**
 *Calculate Average of numeric content or length*
**Help**
 *Calculate the Mean (µ) of the data if the field is numeric, otherwise calculate the average length of the field.*

Calculate Variance (s²)
### Calculate Variance (s²)

**Description**
 *Calculate Variance*
**Help**
 *The Variance (s²) is the a measure of dispersion - used in combination with the Mean (µ)*

Calculate Deviation (s)
### Calculate Deviation (s)

**Description**
 *Calculate Standard Deviation*
**Help**
 *The Standard Deviation (s) is the a measure of dispersion - used in combination with the Mean (µ)*

Item Translation
### Item Translation

**Description**
 *Print Format Translation*

```
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The Translation Tab checkbox indicate if a tab contains translation information. To display translation information, enable this in Tools>Preference.
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

Print Format Item
### Print Format Item

**Description**
 *Item/Column in the Print format*
**Help**
 *Item/Column in the print format maintaining layout information*

Language
### Language

**Description**
 *Language for this entity*
**Help**
 *The Language identifies the language to use for display and formatting*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Translated
### Translated

**Description**
 *This column is translated*
**Help**
 *The Translated checkbox indicates if this column is translated.*

Print Text
### Print Text

**Description**
 *The label text to be printed on a document or correspondence.*
**Help**
 *The Label to be printed indicates the name that will be printed on a document or correspondence. The max length is 2000 characters.*

Print Label Suffix
### Print Label Suffix

**Description**
 *The label text to be printed on a document or correspondence after the field*
**Help**
 *The Label to be printed indicates the name that will be printed on a document or correspondence after the field. The max length is 60 characters.*

Graph
### Graph

**Description**
 *Define Graph to be included*

```
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
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

Print Format
### Print Format

**Description**
 *Data Print Format*
**Help**
 *The print format determines how data is rendered for print.*

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

Graph Type
### Graph Type

**Description**
 *Type of graph to be painted*
**Help**
 *Type of graph to be painted*

Description Column
### Description Column

**Description**
 *Description Column for Pie/Line/Bar Charts*
**Help**
 *Graph Description Column for Pie and Line/Bar Charts*

Data Column
### Data Column

**Description**
 *Data Column for Pie and Line Charts*
**Help**
 *Graph Data Column for Pie and Line/Bar Charts*

Data Column 2
### Data Column 2

**Description**
 *Data Column for Line Charts*
**Help**
 *Additional Graph Data Column for Line/Bar Charts*

Data Column 3
### Data Column 3

**Description**
 *Data Column for Line Charts*
**Help**
 *Additional Graph Data Column for Line/Bar Charts*

Data Column 4
### Data Column 4

**Description**
 *Data Column for Line Charts*
**Help**
 *Additional Graph Data Column for Line/Bar Charts*

Data Column 5
### Data Column 5

**Description**
 *Data Column for Line Charts*
**Help**
 *Additional Graph Data Column for Line/Bar Charts*
