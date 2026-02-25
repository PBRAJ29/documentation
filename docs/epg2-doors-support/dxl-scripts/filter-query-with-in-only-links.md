# Filter query with in Only links



1.  User requirement only required In links from modules
2.  We have DXL Script to get In links in module
3.  Script location[https://korvm029.apac.bosch.com/etctools/ETC5\_Repo/03\_Misc/XC-AS/DOORs/Scripts/PET-9790/](https://korvm029.apac.bosch.com/etctools/ETC5_Repo/03_Misc/XC-AS/DOORs/Scripts/PET-9790/) <!-- WARNING: Unmapped Confluence link - please update manually -->
4.  Once open script in notepad ++

         4.1. Changes needed are from line 20 to 23

         4.2. If "in Link Required" is set to "true" then add the module name to the attribute "in Link Module Name"

         4.3. Then this script will create a view with the requirements which has in links other than the module mentioned in line 23.



          **Once added to module name please save script**

















          **Please run the script in Module level click on load select script and run**

           **Once script run is successfully the in links file will generate**

           **Output excel file**
