# Get-TransactionLogStats.ps1
This is an updated PowerShell script of the original GetTransactionLogStats.ps1 which has been posted on October 7th, 2013.

##Description
The script published by the Exchange Team requires an update when run on a system that does not use the en-US locale as Culture.

When the script analyses the saved log file information, a DateTime error is beeing thrown:

Cannot convert value "21/05/2010" to type "System.DateTime"

##Examples
See: http://blogs.technet.com/b/exchange/archive/2013/10/07/analyzing-exchange-transaction-log-generation-statistics.aspx 

##TechNet Gallery
Find the original script at TechNet Gallery
* https://gallery.technet.microsoft.com/scriptcenter/GetTransactionLogStatsps1-3b530ac3 

Find the updated script at TechNet Gallery
* https://gallery.technet.microsoft.com/Analyzing-Exchange-be8899c8 

##Credits
Written by: Exchange Team
Updated by: Thomas Stensitzki

Find me online:

* My Blog: https://www.granikos.eu/en/justcantgetenough
* Archived Blog:	http://www.sf-tools.net/
* Twitter:	https://twitter.com/apoc70
* LinkedIn:	http://de.linkedin.com/in/thomasstensitzki
* Github:	https://github.com/Apoc70

For more Office 365, Cloud Security and Exchange Server stuff checkout services provided by Granikos

* Blog:     http://blog.granikos.eu/
* Website:	https://www.granikos.eu/en/
* Twitter:	https://twitter.com/granikos_de