
Column Encryption
# Column Encryption


Test and enable Column Encryption

Help
## Help

To enable storage encryption or remove encryption is dangerous as you may loose data. You need to verify that the column is big enough to hold the encrypted value.  You can provide your own encryption method, but cannot change it once enabled.  
The default implementation supports US ASCII String conversion (not Unicode, Numbers, Dates)
Note that support is restricted to setup and test, but not data recovery.

Parameters
## Parameters


Encrypted
### Encrypted

**Description**
 *Display or Storage is encrypted*
**Help**
 *Display encryption (in Window/Tab/Field) - all characters are displayed as '*' - in the database it is stored in clear text. You will not be able to report on these columns.
Data storage encryption (in Table/Column) - data is stored encrypted in the database (dangerous!) and you will not be able to report on those columns. Independent from Display encryption.*

Change the current Setting
### Change the current Setting

**Description**
 *Confirm that you want to change the current setting*

Maximum Length
### Maximum Length

**Description**
 *Maximum Length of Data*

Test Value
### Test Value

**Description**
 *Value to test*
