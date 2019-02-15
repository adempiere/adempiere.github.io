
Import Accounts
# Import Accounts


Import Natural Accounts

Help
## Help

Import accounts and their hierarchies and optional update the default accounts.  
Updating the Default Accounts changes the natural account segment of the used account, e.g. account 01-240 becomes 01-300).  If you create a new combination, the old account (e.g. 01-240) will remain, otherwise replaced.
If you select this, make sure that you not multiple default accounts using one natural account and HAVE A BACKUP !!
The Parameters are default values for null import record values, they do not overwrite any data.

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
Element
### Element

**Description**
 *Accounting Element*
**Help**
 *The Account Element uniquely identifies an Account Type.  These are commonly known as a Chart of Accounts.*

```
The field must have a value for the record to be saved to the database.
```
Update Default Accounts
### Update Default Accounts

**Description**
 *Update Default Accounts*

Create New Combination
### Create New Combination

**Description**
 *Create New Account Combination*

Delete old imported records
### Delete old imported records

**Description**
 *Before processing delete old imported records in the import table*
