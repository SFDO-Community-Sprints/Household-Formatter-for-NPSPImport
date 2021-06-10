# NPSPImport-Excel-Formatter
This Community Sprint project is to market, distribute and improve an Excel tool that helps group contacts into households in a format ready for NPSP Data Import.

# Project Overview
When it’s time to migrate data from a legacy system, how do we get Contacts into the same Household together? In order to use NPSP's Data Import records to group contacts into households, the input file must be in a format with two contacts in the same row, while source datasets typically come with one contact per row. We have developed an Excel spreadsheet with an embedded VisualBasic program that makes it easier to get contact data into import-ready format. Help spread the word about this tool, support and standardize its distribution and improve its functionality. Here is a demo of the tool: https://youtu.be/NGU43QEsObE

## Elevator Speech: Use Cases for the NPSPXX Tool
When might I use this tool?
- I have external data containing Household members that I want to bring into NPSP.
There is a tool available called the NPSP Data Importer which will create Contacts, Households other relationships automatically using the Data Import Object as input.

### What's the problem?
When exporting data from external systems, we usually get a dataset with one row per contact. However, for Households having more than one contact, the NPSP Data Importer template requires that two Household members be in the same row. Columns designated as "Contact1" contain data from the primary contact and columns designated as "Contact2" contain data from the other Household members. Without the XX tool, getting the data from the external system into the required format requires significant data manipulation invovling XLOOKUP or multiple VLOOKUPs. 

### What's the solution?
-  The tool allows the user the flexibility to map input columns to output columns and controls which input rows are copied to Contact1 columns or to Contact2 columns.
-  When the source dataset contains a Household identifier in each input row, the tool will group the contacts into Households and format the data according to the NPSP Data Importer Template without the need for using XLOOKUP or multiple VLOOKUPs.
-  Primary contacts can be flagged in the input dataset otherwise the first row in the Household defaults to primary.
-  Once custom fields are defined in the Data Import Object, the tool supports inclusion of these fields, too.

## Vision & Goals
Mission statement: 
- What do we do?
- Whom do we serve?
- How do we serve them?

Or 

- Key market: the target audience.
- Contribution: the product or service.
- Distinction: what makes the product unique or why the audience should buy it over another.

Vision statement
Your vision statement gives the company direction. It is the future of the business, which then provides the purpose.
The vision statement is about what you want to become. It’s aspirational.

## Project Vertical
Please replace with Nonprofit, Education, or Other (if Other, explain further)

## Hub Group Link
https://powerofus.force.com/s/group/0F97y00000007fpCAA/sprint-project-household-formatter

# Current Project Team & Accomplishments

Full Name            | Team Role     | Github Username                                    |Role
------------         | ------------- | -------------                                      |-------------   
Kathy Olney          | Group Leader  | https://github.com/KathOlney)                      | Developer
Dodi Friedenberg     | Group Leader  |                                                    | Chief Evangelist

## Sprint (June 9-10 2021)

### Project Team Accomplishments
Please replace with the tasks you team was able to accomplish during the Sprint event.


# Project Resources and Documentation
Documentation can be found in the repository [wiki] (URL for wiki where docs are stored)

Demo video goes here

Markdown cheat sheet: https://www.markdownguide.org/basic-syntax/

# Future Contributions (AKA what were you unable to finish at the Sprint)
Replace with the goals your team would like to continue working on next time.

