# ADW
Active Data Warehouse for Electric Cooperatives

The purpose of this project is to collaborate on a unified data warehouse schema for use by electric cooperatives. The initial seed of this project is provided by LCEC (Lee County Electric Coop) in Southwest Florida. The schema attached can be leveraged by other cooperatives to jump start their data warehouse goals by providing a working schema. 

Once you have installed this schema to your Oracle database, the next step is for your team to develop ETL scripts to populate data from your source systems to this schema. The zipped schema on GitHub does not include any actual data. Lastly, your Business Intelligence team could leverage standard BI tools to pull data from your new data warehouse. Your business community can also leverage the ADW from Microsoft software such as Excel and Power BI.


Why do you call it an "Active" data warehouse?
The database scheme is design to facilitate near real-time updates from the source OLTP databases. This can be achieved via Service-Oriented Architecture (SOA) tools, ETL (Extract-Transform-Load) tools, or various data sync tools. 


How to Install
The zip file contains the initial version of the active data warehouse for electric cooperatives schema. To install, download, unzip, and use the Oracle database import utility. If someone completes these steps and wishes to contribute, please send us the detailed steps and we can add it to this readme file. 
