![RSS-Bridge](static/logo_600px.png)
===

**HOW THIS WORKS** 
I forked this from the main branch for use in Heroku, a web app that builds Github apps as a website. 

**WHEN DEPLOYING AN UPDATE** 
Heroku is set to auto-deploy when the main branch I forked from is updated. This may mean that the whitelist-default.txt file gets overwritten. This file enables and disables bridges from view. I made a backup of the file next to the original. 

**WHITELISTING BRIDGES** 
If you deploy and it automatically overwrites the whitelist file, you'll have the default list of available bridges again. You'll need to update the original file from the backup (plus any new bridges, if they add new ones). Then re-deploy on Heroku.

**LINK TO HEROKU** 
https://dashboard.heroku.com/apps/rssy-bridge/deploy/github
