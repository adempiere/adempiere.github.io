
Reset Accounting
# Reset Accounting


Reset Accounting Entries ** Stop Accounting Server before starting **

Help
## Help

Delete accounting records of documents to be re-created by the next run of the accounting engine.  This is a dramatic step and you want to do this ONLY after changes of the accounting structure (e.g. different default accounts, etc.) and if fixing via manual Journal entries is not sensible.

Parameters
## Parameters


Client
### Client

**Description**
 *Client/Tenant for this installation.*
**Help**
 *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*

```
The field must have a value for the record to be saved to the database.
```
Table
### Table

**Description**
 *Database Table information*
**Help**
 *The Database Table provides the information of the table definition*

Delete existing Accounting Entries
### Delete existing Accounting Entries

**Description**
 *The selected accounting entries will be deleted!  DANGEROUS !!!*

```
The field must have a value for the record to be saved to the database.
```
Account Date
### Account Date

**Description**
 *Optional account date range*
**Help**
 *Only documents within this date range which are also in open periods will be reset.*

```
The Range checkbox indicates that this parameter is a range of values.
```