Check for an internet connection by pinging one of Google's DNSes

The Windows code for the ping call is based on isnetavl by Nishant Kumar. To allow drop-in compatibility the name was kept the same.  
Because this calls the system command line, the syntax is slightly different between Unix and Windows, as is the response. See the help text for the tested OSes.

Some organizations block ping from working, in which case an HTML fallback is used (by attempting to load the google.com homepage).

Licence: CC by-nc-sa 4.0