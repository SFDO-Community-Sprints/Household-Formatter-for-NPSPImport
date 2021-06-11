# Household Formatter for NPSP Data Import
This Community Sprint project is to market, distribute and improve an Excel tool that helps group contacts into Households in a format ready for NPSP Data Import.

## Project Overview
When it’s time to migrate data from a legacy system, how do we get Contacts into the same Household together? In order to use NPSP's Data Import records to group contacts into Households, the input file must be in a format with two contacts in the same row, while source datasets typically come with one contact per row. We have developed an Excel spreadsheet with an embedded VisualBasic program that makes it easier to get contact data into import-ready format. Help spread the word about this tool, support and standardize its distribution and improve its functionality. [View a demo of the tool.](https://youtu.be/NGU43QEsObE)

### Who is this tool for?
Anyone who needs to bring external data into NPSP and who wants to take advantage of the [NPSP Data Importer](https://powerofus.force.com/s/article/NPSP-How-the-Import-Process-Works)'s ability to create Contacts, Accounts and other related objects, complete with their relationships. Without the Data Importer, it may be necessary to create the relationships by sequentially importing a spreadsheet for each kind of object, then exporting the newly created records with their Salesforce IDs, then using XLOOKUPs or VLOOKUPs to associate the IDs with related records in the next spreadsheet. 

### What's the problem?
When data is exported from an external system, it usually comes with one contact per row. However, for households having more than one contact, the NPSP Data Importer template requires that two household members be in the same row. Columns designated as "Contact1" contain data from the primary contact and columns designated as "Contact2" contain data from the other household members. To get the data from the external system into the required format typically requires significant data manipulation involving multiple XLOOKUPs or VLOOKUPs - the same situation the the Data Importer is designed to avoid. 

### Why use this tool?
-  The tool allows the user to map input columns to output columns and control which input rows are copied to Contact1 columns or to Contact2 columns.
-  When the source dataset includes a household identifier column, the tool can use it to group the Contacts into households in the NPSP Data Importer Template format without needing to use XLOOKUPs or VLOOKUPs.
-  Primary contacts can be flagged in the source dataset, otherwise the first contact encountered in the file is considered the primary contact for its household.
-  The tool can be configured to flexibly handle different source datasets.
-  Columns may contain custom fields.

## Join our Hub Group 
https://powerofus.force.com/s/group/0F97y00000007fpCAA/sprint-project-household-formatter



# Project Resources and Documentation
Download instructions

Demo video goes here



# Current Project Team                   
Kathy Olney           (Group Leader)    
Dodi Friedenberg      (Group Leader)     
Sheeba Thukral    
Mechelle Norton  
Rohne Sathianarayanan  
Sowmya Bhat  


# Project History
This project began in December 2020 when [Dodi Friedenberg](https://www.linkedin.com/in/dodifriedenberg/), a Salesforce consultant specializing in nonprofits, needed to do a data migration and asked [Kathy Olney](https://www.linkedin.com/in/kathy-olney-acton-ma/), a new Salesforce admin with programming experience, to help with the problem of preparing a spreadsheet for the NPSP Data Importer. Kathy wrote a VisualBasic program to do the job, and Dodi successfully used it to load her data. After demonstrating the tool at a [Salesforce Saturday](https://www.linkedin.com/groups/12476927/) and at the February 2021 Community Sprint, a number of people requested copies. With the intention that more people could take advantage of the tool if there was a standardized way to distribute it and a strategy for spreading the word, the project debuted at the June 2021 Community Sprint. 

## Sprint (June 9-10 2021)

- Chose a name for the tool
- Set up this GitHub repository 
- Wrote a project description and download instructions
- Discussed strategies for spreading the word about the tool



# Next Steps
- Network to find consultants or users who use the Data Importer and encourage them to try the tool
- Listen for feedback on how the tool can be improved
- Post to blogs or community groups
