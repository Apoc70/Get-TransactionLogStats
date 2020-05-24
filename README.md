# Get-TransactionLogStats.ps1
This is an updated PowerShell script of the original GetTransactionLogStats.ps1 which has been posted on October 7th, 2013.

## Description

The script published by the Exchange Team requires an update when run on a system that does not use the en-US locale as Culture.

When the script analyses the saved log file information, a DateTime error is beeing thrown:

Cannot convert value "21/05/2010" to type "System.DateTime"

## Examples

See: http://blogs.technet.com/b/exchange/archive/2013/10/07/analyzing-exchange-transaction-log-generation-statistics.aspx 

## Credits

Originally written by: Exchange Product Group
Updated by: Thomas Stensitzki

## Stay connected

- My Blog: [http://justcantgetenough.granikos.eu](http://justcantgetenough.granikos.eu)
- Twitter: [https://twitter.com/stensitzki](https://twitter.com/stensitzki)
- LinkedIn: [http://de.linkedin.com/in/thomasstensitzki](http://de.linkedin.com/in/thomasstensitzki)
- Github: [https://github.com/Apoc70](https://github.com/Apoc70)
- MVP Blog: [https://blogs.msmvps.com/thomastechtalk/](https://blogs.msmvps.com/thomastechtalk/)
- Tech Talk YouTube Channel (DE): [http://techtalk.granikos.eu](http://techtalk.granikos.eu)

For more Office 365, Cloud Security, and Exchange Server stuff checkout services provided by Granikos

- Blog: [http://blog.granikos.eu](http://blog.granikos.eu)
- Website: [https://www.granikos.eu/en/](https://www.granikos.eu/en/)
- Twitter: [https://twitter.com/granikos_de](https://twitter.com/granikos_de)