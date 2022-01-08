# GenerateYearlyReport
UIPath project to download all the monthly reports for a specific vendor and generate a yearly report.

Step Short Description
1.1 Open the ACME System 1 web application.
1.2 Log in to System 1. Required input data: email and password.
1.3 Access the Dashboard - the central location, where the user can pick a specific menu item.
1.4 Access the Work Items Listing to view all the available tasks to be performed (Output data: list of tasks).
1.5 For each activity of the WI4 type perform the following steps:
1.5.A Open the Details page of the selected activity to retrieve the Vendor Tax ID (Outputdata: TaxID).
1.5.B Go back to the Dashboard and access the Download Monthly Report section in the Reports menu.
1.5.C Fill in the Vendor TaxID and download ALL the corresponding monthly reports for 2017.           
1.5.D Group all the downloaded monthly reports into a single Excel yearly report with the “Yearly-Report-2017- TAXID.xlsx” name.
1.5.E Upload the resulting Excel yearly report in the “Upload YearlyReport” section in the Reports menu.
1.5.F Fill in the Vendor TaxID, set the year as 2017, and select the file on your hard drive. This will return a unique upload ID. Out upload ID.
1.5.G Go back to the Work Item Details page and select Update Work Item.
1.5.H Set the status to “Completed”. Add the following comment: “Uploaded with ID uploadID”. 
1.6 Continue with the next WI4 activity.
