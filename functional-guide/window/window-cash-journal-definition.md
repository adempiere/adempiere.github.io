
Cash Journal Definition
# Cash Journal Definition


Maintain Cash Journal

Help
## Help

The Cash Journal Window is used to define the cash and accounts associated with an organization or business partner

Window Type
### Window Type

**Maintain**

```
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
```

Tabs
## Tabs


Payment Processor
### Payment Processor

**Description**
 *Processor for online payments*
**Help**
 *The Electronic Payments Tab is used to define the parameters for the processing of electronic payments. If no currency is defined, all currencies are accepted. If a minumum amount is defined (or not zero), the payment processor is only used if the payment amount is equal or higher than the minumum amount. 
The class needs to implement org.compiere.model.PaymentProcessor*

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

Bank Account
### Bank Account

**Description**
 *Account at the Bank*
**Help**
 *The Bank Account identifies an account at this Bank.*

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

Host Address
### Host Address

**Description**
 *Host Address URL or DNS*
**Help**
 *The Host Address identifies the URL or DNS of the target host*

Host port
### Host port

**Description**
 *Host Communication Port*
**Help**
 *The Host Port identifies the port to communicate with the host.*

Partner ID
### Partner ID

**Description**
 *Partner ID or Account for the Payment Processor*
**Help**
 *Partner ID (Verisign) or Account ID (Optimal)*

Vendor ID
### Vendor ID

**Description**
 *Vendor ID for the Payment Processor*

User ID
### User ID

**Description**
 *User ID or account number*
**Help**
 *The User ID identifies a user and allows access to records or processes.*

Password
### Password

**Description**
 *Password of any length (case sensitive)*
**Help**
 *The Password for this User.  Passwords are required to identify authorized users.  For Adempiere Users, you can change the password via the Process "Reset Password".*

Proxy address
### Proxy address

**Description**
 *Address of your proxy server*
**Help**
 *The Proxy Address must be defined if you must pass through a firewall to access your payment processor.*

Proxy port
### Proxy port

**Description**
 *Port of your proxy server*
**Help**
 *The Proxy Port identifies the port of your proxy server.*

Proxy logon
### Proxy logon

**Description**
 *Logon of your proxy server*
**Help**
 *The Proxy Logon identifies the Logon ID for your proxy server.*

Proxy password
### Proxy password

**Description**
 *Password of your proxy server*
**Help**
 *The Proxy Password identifies the password for your proxy server.*

Accept MasterCard
### Accept MasterCard

**Description**
 *Accept Master Card*
**Help**
 *Indicates if Master Cards are accepted*

Accept Visa
### Accept Visa

**Description**
 *Accept Visa Cards*
**Help**
 *Indicates if Visa Cards are accepted*

Accept AMEX
### Accept AMEX

**Description**
 *Accept American Express Card*
**Help**
 *Indicates if American Express Cards are accepted*

Accept Diners
### Accept Diners

**Description**
 *Accept Diner's Club*
**Help**
 *Indicates if Diner's Club Cards are accepted*

Accept Corporate
### Accept Corporate

**Description**
 *Accept Corporate Purchase Cards*
**Help**
 *Indicates if Corporate Purchase Cards are accepted*

Accept Discover
### Accept Discover

**Description**
 *Accept Discover Card*
**Help**
 *Indicates if Discover Cards are accepted*

Accept Direct Deposit
### Accept Direct Deposit

**Description**
 *Accept Direct Deposit (payee initiated)*
**Help**
 *Indicates if Direct Deposits (wire transfers, etc.) are accepted. Direct Deposits are initiated by the payee.*

Accept Direct Debit
### Accept Direct Debit

**Description**
 *Accept Direct Debits (vendor initiated)*
**Help**
 *Accept Direct Debit transactions. Direct Debits are initiated by the vendor who has permission to deduct amounts from the payee's account.*

Accept Electronic Check
### Accept Electronic Check

**Description**
 *Accept ECheck (Electronic Checks)*
**Help**
 *Indicates if EChecks are accepted*

Accept ATM
### Accept ATM

**Description**
 *Accept Bank ATM Card*
**Help**
 *Indicates if Bank ATM Cards are accepted*

Minimum Amt
### Minimum Amt

**Description**
 *Minimum Amount in Document Currency*

Only Currency
### Only Currency

**Description**
 *Restrict accepting only this currency*
**Help**
 *The Only Currency field indicates that this bank account accepts only the currency identified here.*

Require CreditCard Verification Code
### Require CreditCard Verification Code

**Description**
 *Require 3/4 digit Credit Verification Code*
**Help**
 *The Require CC Verification checkbox indicates if this bank accounts requires a verification number for credit card transactions.*

Sequence
### Sequence

**Description**
 *Document Sequence*
**Help**
 *The Sequence defines the numbering sequence to be used for documents.*

Payment Processor Class
### Payment Processor Class

**Description**
 *Payment Processor Java Class*
**Help**
 *Payment Processor class identifies the Java class used to process payments extending the org.compiere.model.PaymentProcessor class. 
Example implementations are Optimal Payments: org.compiere.model.PP_Optimal or Verisign: org.compiere.model.PP_PayFlowPro*

Commission %
### Commission %

**Description**
 *Commission stated as a percentage*
**Help**
 *The Commission indicates (as a percentage) the commission to be paid.*

Cost per transaction
### Cost per transaction

**Description**
 *Fixed cost per transaction*
**Help**
 *The Cost per Transaction indicates the fixed cost per to be charged per transaction.*

Statement Loader
### Statement Loader

**Description**
 *Definition of Bank Statement Loader (SWIFT, OFX)*
**Help**
 *The loader definition privides the parameters to load bank statements from EFT formats like SWIFT (MT940) or OFX. The required parameters depend on the actual statement loader class*

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

Bank Account
### Bank Account

**Description**
 *Account at the Bank*
**Help**
 *The Bank Account identifies an account at this Bank.*

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

Financial Institution ID
### Financial Institution ID

**Description**
 *The ID of the Financial Institution / Bank*
**Help**
 *Depending on the loader, it might require a ID of the financial institution*

Branch ID
### Branch ID

**Description**
 *Bank Branch ID*
**Help**
 *Dependent on the loader, you may have to provide a bank branch ID*

Account No
### Account No

**Description**
 *Account Number*
**Help**
 *The Account Number indicates the Number assigned to this bank account.*

PIN
### PIN

**Description**
 *Personal Identification Number*

User ID
### User ID

**Description**
 *User ID or account number*
**Help**
 *The User ID identifies a user and allows access to records or processes.*

Password
### Password

**Description**
 *Password of any length (case sensitive)*
**Help**
 *The Password for this User.  Passwords are required to identify authorized users.  For Adempiere Users, you can change the password via the Process "Reset Password".*

Host Address
### Host Address

**Description**
 *Host Address URL or DNS*
**Help**
 *The Host Address identifies the URL or DNS of the target host*

Host port
### Host port

**Description**
 *Host Communication Port*
**Help**
 *The Host Port identifies the port to communicate with the host.*

Proxy address
### Proxy address

**Description**
 *Address of your proxy server*
**Help**
 *The Proxy Address must be defined if you must pass through a firewall to access your payment processor.*

Proxy port
### Proxy port

**Description**
 *Port of your proxy server*
**Help**
 *The Proxy Port identifies the port of your proxy server.*

Proxy logon
### Proxy logon

**Description**
 *Logon of your proxy server*
**Help**
 *The Proxy Logon identifies the Logon ID for your proxy server.*

Proxy password
### Proxy password

**Description**
 *Password of your proxy server*
**Help**
 *The Proxy Password identifies the password for your proxy server.*

File Name
### File Name

**Description**
 *Name of the local file or URL*
**Help**
 *Name of a file in the local directory space - or URL (file://.., http://.., ftp://..)*

Statement Loader Class
### Statement Loader Class

**Description**
 *Class name of the bank statement loader*
**Help**
 *The name of the actual bank statement loader implementing the interface org.compiere.impexp.BankStatementLoaderInterface*

Date Format
### Date Format

**Description**
 *Date format used in the input format*
**Help**
 *The date format is usually detected, but sometimes need to be defined.*

Date last run
### Date last run

**Description**
 *Date the process was last run.*
**Help**
 *The Date Last Run indicates the last time that a process was run.*

Cash Journal
### Cash Journal

**Description**
 *Maintain Cash Journal*
**Help**
 *The Cash Journal Tab defines a cash that is used by an organization or business partner.  Each Cash is given an identifying Name, Address, Routing No and Swift Code*

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

Address
### Address

**Description**
 *Location or Address*
**Help**
 *The Location / Address field defines the location of an entity.*

Own Bank
### Own Bank

**Description**
 *Bank for this Organization*
**Help**
 *The Own Bank field indicates if this bank is for this Organization as opposed to a Bank for a Business Partner.*

Cash Account
### Cash Account

**Description**
 *Maintain Cash Account*
**Help**
 *The Account Tab is used to define one or more accounts for a Cash.  Each account has a unique Account No and Currency. The cash account organization is used for accounting.*

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

Bank
### Bank

**Description**
 *Bank*
**Help**
 *The Bank is a unique identifier of a Bank for this Organization or for a Business Partner with whom this Organization transacts.*

Account No
### Account No

**Description**
 *Account Number*
**Help**
 *The Account Number indicates the Number assigned to this bank account.*

Sales Transaction
### Sales Transaction

**Description**
 *This is a Sales Transaction*
**Help**
 *The Sales Transaction checkbox indicates if this item is a Sales Transaction.*

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

Currency
### Currency

**Description**
 *The Currency for this record*
**Help**
 *Indicates the Currency to be used when processing or reporting on this record*

Credit limit
### Credit limit

**Description**
 *Amount of Credit allowed*
**Help**
 *The Credit Limit field indicates the credit limit for this account.*

Current balance
### Current balance

**Description**
 *Current Balance*
**Help**
 *The Current Balance field indicates the current balance in this account.*

Payment Export Class
### Payment Export Class


Business Partner
### Business Partner

**Description**
 *Identifies a Business Partner*
**Help**
 *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*

Cash Account Document
### Cash Account Document

**Description**
 *Maintain Cash Account Documents*
**Help**
 *In this tab, you define the documents used for this cash account. You define your check and other payment document (sequence) number as well as format.*

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

Bank Account
### Bank Account

**Description**
 *Account at the Bank*
**Help**
 *The Bank Account identifies an account at this Bank.*

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

Payment Rule
### Payment Rule

**Description**
 *How you pay the invoice*
**Help**
 *The Payment Rule indicates the method of invoice payment.*

Current Next
### Current Next

**Description**
 *The next number to be used*
**Help**
 *The Current Next indicates the next number to use for this document*

Check Print Format
### Check Print Format

**Description**
 *Print Format for printing Checks*
**Help**
 *You need to define a Print Format to print the document.*

Accounting
### Accounting

**Description**
 *Maintain Accounting Data*
**Help**
 *The Accounting Tab is used to define the accounts used for transactions with this Cash.*

```
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The Accounting Tab checkbox indicates if this window contains accounting information. To display accounting information, enable this in Tools>Preference and Role.
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

Bank Account
### Bank Account

**Description**
 *Account at the Bank*
**Help**
 *The Bank Account identifies an account at this Bank.*

Accounting Schema
### Accounting Schema

**Description**
 *Rules for accounting*
**Help**
 *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Bank Asset
### Bank Asset

**Description**
 *Bank Asset Account*
**Help**
 *The Bank Asset Account identifies the account to be used for booking changes to the balance in this bank account*

Bank In Transit
### Bank In Transit

**Description**
 *Bank In Transit Account*
**Help**
 *The Bank in Transit Account identifies the account to be used for funds which are in transit.*

Unallocated Cash
### Unallocated Cash

**Description**
 *Unallocated Cash Clearing Account*
**Help**
 *Receipts not allocated to Invoices*

Bank Unidentified Receipts
### Bank Unidentified Receipts

**Description**
 *Bank Unidentified Receipts Account*
**Help**
 *The Bank Unidentified Receipts Account identifies the account to be used when recording receipts that can not be reconciled at the present time.*

Payment Selection
### Payment Selection

**Description**
 *AP Payment Selection Clearing Account*

Bank Expense
### Bank Expense

**Description**
 *Bank Expense Account*
**Help**
 *The Bank Expense Account identifies the account to be used for recording charges or fees incurred from this Bank.*

Bank Interest Expense
### Bank Interest Expense

**Description**
 *Bank Interest Expense Account*
**Help**
 *The Bank Interest Expense Account identifies the account to be used for recording interest expenses.*

Bank Interest Revenue
### Bank Interest Revenue

**Description**
 *Bank Interest Revenue Account*
**Help**
 *The Bank Interest Revenue Account identifies the account to be used for recording interest revenue from this Bank.*

Bank Revaluation Gain
### Bank Revaluation Gain

**Description**
 *Bank Revaluation Gain Account*
**Help**
 *The Bank Revaluation Gain Account identifies the account to be used for recording gains that are recognized when converting currencies.*

Bank Revaluation Loss
### Bank Revaluation Loss

**Description**
 *Bank Revaluation Loss Account*
**Help**
 *The Bank Revaluation Loss Account identifies the account to be used for recording losses that are recognized when converting currencies.*

Bank Settlement Gain
### Bank Settlement Gain

**Description**
 *Bank Settlement Gain Account*
**Help**
 *The Bank Settlement Gain account identifies the account to be used when recording a currency gain when the settlement and receipt currency are not the same.*

Bank Settlement Loss
### Bank Settlement Loss

**Description**
 *Bank Settlement Loss Account*
**Help**
 *The Bank Settlement loss account identifies the account to be used when recording a currency loss when the settlement and receipt currency are not the same.*
