### Task2 - Polls
_Create 3 contact lists for polling purpose_

Read in xlsx file that includes 3 tabs - main, contacts, target_ssic.

Combine info in main and contact tabs into one dataframe.

Select rows that fulfills specified condition e.g. entity_status must be “Live” or “Live Company” and must match ssic in "target_ssic" tab.

Split into 3 smaller dataframes based on 'contact_status' groups: 'Not Contacted', 'Previously Contacted' and 'Repeat'. 

Randomise each of the 3 'contact_status' dataframes and split it further equally into 3 parts, e.g. 'Not Contacted' Part A, 'Not Contacted' Part B and 'Not Contacted' Part C.

Combine each of the dataframes such that the first recombined dataframe has all the Part As, similarly for Part Bs and Part Cs. Each of the recombined dataframes will have all the 3 randomised 'contact_status' groups.

Select required columns for output template.

Export to excel as 3 tabs.
