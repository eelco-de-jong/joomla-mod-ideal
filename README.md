# joomla-mod-ideal
iDEAL module designed to work with Buckaroo PSP

This custom ideal module is designed to work with Buckaroo as a Payment Service Provider.
The full application consists of 2 seperate modules. Mod_ideal (this one) which shows a form on the frontend and 
creates a request to be send to the PSP to finalize the donation and adds a new row in a databasetable with data 
about the donation.
And the module called mod_idealresult which has functionality to receive and handle incoming post by the PSP
and show a custom statusmessage/ send custom email and add status to a databasetable.

Next steps are (and this is a dynamic list)
1. Upgrade security (SQL injection, etc...)
2. Add field validations (HTML5 or Javascript)
