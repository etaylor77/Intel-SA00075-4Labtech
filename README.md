# Intel-SA00075-4Labtech
Repo for deploying the Intel SA00075 Detection tool and populating EDF's in Labtech


# Beta release v0.3 1/13/2018

v0.3 Changes

 - Added delete function for the Deskop link installed by the tool (Thanks Jeremy Roe)
 - Fixed AMT EDF not being populated by the script
 - Added Intel SA00075 Monitor

# Setup Instructions

 - Import the xml file in Labtech folder into your Labtech Server
   - This should put two scripts in your root scripts folder
   - This should add EDF's in the info section of your agent's computer screen
 - Import the sql file in Monitors folder to create the monitor
   - This is just to monitor the "status" EDF
   
   
# Still Working On

 - Customize the monitor from the default LT to more informative
 - A monitor to alert and create a ticket based on the EDF's populated
 - Adding remediation EDF's and scripts to resolve this issue
 - Adding monitor to remove application on any vm guest
 
 
 # Update History
 
v0.2 Changes

 - Added exit if 'VM Machine' flag is set in the database
 - Fixed spelling error on 'Unpacking Tool' script log
 


