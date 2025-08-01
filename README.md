# Rhode Island Food Bank Donation Data Format Template
## Background Information
- Every week Tapin receives a donation of non-monetary goods from the Rhode Island Food Bank.
- Every month, a spreadsheet is provided that documents a variety of information about the goods donated.
- This data is reformatted and reused by Tapin for record keeping purposes.

This spreadsheet acts as a template for volunteers to easily format data and submit it into the CRM.
## Instructions
1. Make a copy of the template sheet somewhere on your computer.
2. In the RI Food Bank spreadsheet, delete all rows that do not contain information about an item donated.
3. Select all rows in the spreadsheet (**Ctrl + A**, **Cmd + A**).
4. Copy these selected rows (**Ctrl + C**, **Cmd + C**).
5. Once a copy of the template spreadsheet is made, navigate to the **Data Insert** page located in the bottom of the Excel window.
6. Click into cell **B2**, the first box underneath the header titled, **Food Bank Reference**.
7. Paste the previously copied data into the new spreadsheet (**Ctrl + V**, **Cmd + V**).
8. Navigate to the right of this table and correct the prerequisite information in the large boxes (food rate and date [MM/01/YYYY]).
9. Click on the **Formatted Data** page located in the bottom of the Excel window.
10. Export the entire spreadsheet as a **.xlsm** file, with the naming convention: **Food Bank Report - MMM YYYY**. Insert it into the Food/'Food Bank Monthly Reports' directory in SharePoint.
11. Click on the **Salesforce Import Data** page located in the bottom of the Excel window.
12. Press the hotkey **Alt + F8** on your keyboard to open the excel Macro window.
13. Click the highlighted **Run** button.
14. As prompted, drag select the entire table in the sheet, including the headers.
15. Click the highlighted **OK** button.
16. Select a good temporary storage place for the file in the windows explorer pop-up.
17. Navigate to Salesforce in your web browser.
18. In the **Goods** app, navigate to the **Acquisitions** tab, then select the **Import** button in the top-right corner of the table.
19. Click the **Acquisitions** button, select **Add new records**, and then insert the file titled **SalesforceUpload** that was just created with the macro.
20. Click the **Next** button, the click the **Next** button again.
21. Click the **Start import** button.

 All of the data from the RI Food Bank spreadsheet will now be nicely formatted in both SharePoint and Salesforce.
 If there are any issues with this spreadsheet, or the process of using it, please contact [techdirector@tapinri.org]().
