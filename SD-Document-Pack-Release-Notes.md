## SD Document Pack Releases

### 3.7.0

#### Enhancements
- AppSource App - The Work Instruction was added to the Sales Commercial Invoice - Invoice report.  

- AppSource App - The Work Instruction was added to the Sales Commercial Invoice - Shipment report.

- AppSource App - The Work Instruction was added to the SDY DP Sales Commercial Invoice report.  

- AppSource App - The Work Instruction was added to the Work Order report.  

- AppSource App - The Work Instruction was added to the Delivery Document report.  

- AppSource App - The Work Instructions were added to the Pick Instruction report. 

- AppSource App - The Work Instruction was added to the Proforma Invoice.  

- AppSource App - The Work Instruction was added to the Sales Credit Memo report.  

- AppSource App - The Work Instruction was added to the Sales Shipment report.  

#### Bug Fixes

- AppSource App - A fix was made to the Amount in Words Caption and Text which were floating and not anchored in the report layouts.

- AppSource App - A fix was made to the Total Including VAT in the Prepayment section of the Proforma Invoice. 

### 3.6.11

#### Bug Fixes

- AppSource App - Fix to Amount in Words Caption and Text floating and not anchored in the layout for Sales Quotes, Orders, and Invoices.

### 3.6.10

#### Enhancements

- AppSource App - The Work Instructions were added to the Sales Quote report ID 43006010.

- AppSource App - The Work Instructions were added to the Sales Invoice report ID 43006011.

- AppSource App - The Work Instructions were added to the Sales Order report ID 43006012.

- AppSource App - In the Brand Card, the AddPicture function (obsoleted) was replaced with the GetPicture function in the Camera codeunit.

### 3.6.9

#### Enhancements

- AppSource App - A change was made to pass the value of the Show Aging Band option in SD Bulk Mailer Jobs of Type Statement to the SD Document Pack Statement reports. 

- AppSource App - A change was made to limit the SD ISV Tenant Subscriptions page to display just our SD ISV AppSource Apps and not other SD PTE Apps.

#### Bug Fixes

- AppSource App - When selecting SD activity pages in the Tell Me/Search in a BCv22 environment, the activity pages were hanging. This was fixed and a new SD Document Activity page is now searchable from the Tell Me search.

### 3.6.8

#### Bug Fixes

- BCv21 App - The total Prepayment Amount on the Proforma Invoice, Sales Order, and the Commercial Invoice (based on the Sales Order) was showing the value of the first prepayment line only if the prepayment lines were not compressed.

- BCv21 App - The Proforma Invoice report was changed to limit the Sales Header records to Document Types of Sales Order and Sales Invoice.

- BCv21 App - The SD Document Pack Tenant Subscriptions page had an incorrect caption. This was fixed.

- BCv21 App - A change was made to the ISV Licence Notification procedure in SD Document Pack to fix an issue that would raise an error when the language is changed from English to another language.

### 3.6.7

#### Enhancements

- BCv21 App - A new SD Document Pack Report, 43006019, SDY DP Cust. Rcpt. with Alloc. was created to show Customer Payments and the allocations against the Invoices.

- BCv21 App - A change was made to the SD Document Pack reports to allow for flowfields to display in the Info Box.

### 3.6.6

#### Enhancements

- BCv21 App - A new SD Document Pack Commercial Invoice report (ID 43006037) based on the Sales Orders was created.

### 3.6.5

#### Enhancements

- BCv21 App - A change was made to the O/S Lodgements and the O/S Payments calculations in the SD Document Pack Bank Reconciliation report. 

### 3.6.4

#### Enhancements

- BCv21 App - A change was made to allow the addition of modified SD Document Pack reports saved in the custom range to the SD Document Pack Setup. 

- BCv21 App - The actions on the Process action group in the SD Document Pack Setup card were reordered to match that of our other ISV Apps.

- BCv21 App - The Licence Message displayed on first install of SD Document Pack was changed to prompt the user to activate a free trial with a link to the Product Activation page.

- BCv21 App - A change was made to the SD Document Pack Purchase Order as the Item Cross Reference table has been replaced with the Item Reference table.

- BCv21 App - The format of the SD Document Pack permission name was standardised to that of our other Apps.

### 3.6.3

#### Enhancements

- BCv20 App - A change was made to the SD Document Pack Bank Reconciliation report to set the property savevalues to false. Unnecessary fields were removed from the request page. 

- BCv20 App - A page was created to display all Simply Dynamics Apps and Subscription details for the tenant. 

- BCv20 App - The Licence Expiry Message/Notification was updated to display the App name. 

- BCv20 App - The Product Activation page was updated to point to the new URL to subscribe for a new licence. 

#### Bug Fixes

- BCv20 App - A fix was made to the code for licence key checks on the SD Document Pack Role Centre. 

### 3.6.2

#### Enhancements

- BCv20 App - Made a change to the Bank Account Reconciliation Statement - Test (43006026) to set the property savevalues as true.

#### Bug Fixes

- BCv20 App - Fixed an issue in the Bank Account Reconciliation Statement - Test report where O/S Lodgement Entries were not printing.

### 3.6.1

#### Bug Fixes

- BCv20 App - A change was made to insert a record in the SDY DP Document Pack RC Cue table when the licence check is first run. This was done to avoid an error being raised when running reports if the SD Document Pack Role Centre was not opened after product install.

### 3.6.1.0 

### Bug Fixes

- BCv14 App - The Branding Logo was not showing in the Branding Card.

### 3.6.0.3

#### Enhancements

- BCv14 App - The latest version of the licence controller was added to this BCv14 code base version of the product. The licence expiry message was updated to display the app name. This change was made to the BCv14 release only, released as v3.6.0.3  and was not applied to any future releases.

- BCv14 App - A page was created in this BCv14 code base version of the product to display all the Simply Dynamics Apps and subscription details for the tenant. This change was made to the BCv14 release only, released as v3.6.0.3  and was not applied to any future releases.

- BCv14 App - A change was made to allow addition of modified SD Document Pack reports saved in the custom range to the SD Document Pack Setup. This change was made to the BCv14 release only, released as v3.6.0.3  and was not applied to any future releases.

### 3.6.0.2

#### Enhancements

- BCv14 App - A change was made to the BCv14 v3.6.0.1 release to allow an Info Box extension for language code. This change was made to the BCv14 code base only, released as v3.6.0.2. and not applied to any future releases.

### 3.6.0.1

#### Enhancements

- BCv14 App - The BCv14 release 3.6.0 was translated to French FRA and released as 3.6.0.1. The translation was applied to this release only, released as v3.6.0.1 and was not applied to other future releases.

### 3.6.0

#### Enhancements

- BCv19 App - The SD Document Pack Delivery Docket was updated to allow the Description field on the lines to display longer descriptions. 

- BCv19 App - The SD Document Pack Sales Credit Memo was updated to allow the Description field on the lines to display longer descriptions. 

- BCv19 App - The SD Document Pack Sales Invoice was updated to allow the Description field on the lines to display longer descriptions. 

- BCv19 App - The SD Document Pack Sales Order Confirmation was updated to allow the Description field on the lines to display longer descriptions. 

- BCv19 App - The SD Document Pack Sales Quote was updated to allow the Description field on the lines to display longer descriptions. 

- BCv19 App - The SD Document Pack Sales Quote was updated to remove a large amount of blank space between where the lines were printing and where the VAT Info box and the Total Summary box were printing. 

- BCv14 App - The BCv19 App v3.6.0 code base was backported to a BCv14 code base and a v3.6.0 BCv14 App was released. 

#### Bug Fixes

- BCv19 App - Fixed an issue where on the SD Document Pack Sales Invoice if the report was printing over two pages, the VAT Info box was printing on the first page and the Total Summary box was printing on the second page. 

- BCv19 App - Fixed an issue in the SD Document Pack Delivery Docket where when a Quote and an Order exist with the same document number, the report was printing the incorrect details. 

### 3.5.0

#### Enhancements

- BCv19 App - Functionality was created to allow the Total Amount in words to pick up the currency description for all currencies in the database. 

- BCv19 App - An option was added to Print Foreign Currency VAT in LCY to the Sales Invoices and Credit Memo Reports. 

- BCv19 App - An option was added to SD Document Pack to print an area on the Sales Invoice report where an authorised signatory can sign the Document. 

- BCv19 App - An option was added to allow users print the Total Amount on the relevant documents as an Amount in Words. 

- BCv19 App - A new field was added to the SD Document Pack Setup called Registered Office. If there is a value in this field, the Registered Office caption and value are printed on all reports. 

- BCv19 App - Default footers were added to the overall SD Document Pack Setup. These default footers will populate the footers on the individual reports. Users can overtype the footers on the individual reports. 

- BCv19 App - The Address field on the Remittance Advice Report was showing extra space. 

- BCv19 App - The Value of the Registered Office was displayed in Bold Text it was changed to Normal Text as per the other values in the Footer. 

- BCv19 App - The option to display the amount in words was moved from the SD Document Pack General Setup to the relevant Report Cards. 

- BCv19 App - The outline of the Digital Signatory box was changed to the same font weight as that of the Report Info Box. 

- BCv19 App - The Digital Signature in the Credit Memo was right aligned to the Total Summary Box. 

- BCv19 App - In the Digital Signature page the Add Digital Signature Action was moved to the Top Most Level on the Menu. 

- BCv19 App - The Default Digital Signature picture was left aligned on the General FastTab of the SD Document Pack Setup. 

- BCv19 App - There was too much space between the Registered Office footer and the value of the field. Also the spaces between the lines in the report footers were not consistent. This was tidied up. 

- BCv19 App - The Registered Office Footer was added to some additional reports - SDY DP Remitt. Advice - Jrnl, SDY DP Remitt. Advice-Entries and SDY DP Manifest. 

- BCv19 App - The code behind the option to show the VAT Amount in LCY was reviewed.

- BCv19 App - In the Sales Order and Sales Quote Reports, when the VAT Box is hidden the Total Summary is printing to the left of the report. The position of the Total Summary should remain right aligned in the Report. 

- BCv19 App - The option to show the amount available in words was surfaced on the SD Document Pack Setup Card. 

- BCv19 App - Layout changes were made to the SD Document Pack Setup Card. 

- BCv19 App - The link on the Tool Tips on the SD Document Pack Pages was updated to our new website. 

- BCv19 App - A change was made to allow for the Bill-To Name on the Sales Invoice Report to wrap to a second line if name doesn't fit on the first line of the Address.

- BCv19 App - A change was made to issue a call to update the subscription expiry date in the product automatically from our licence server when the current expiry date has 5 days to go before expiry. 

- BCv19 App - An option was added to the relevant individual report setups to hide the VAT Information box on reports. 

- BCv19 App - Links in the About Page were updated to our new website. 

#### Bug Fixes

- BCv19 App - Fix to the Commodity Information Text printing on G/L and Comment Lines. 

- BCv19 App - The Delivery Docket Report was showing a blank value for the Registered Office when there was a value entered for the field in the SD Document Pack Setup. 

- BCv19 App - A number of reports were printing the header details with no body on one page and then the header and body on the second page. 

- BCv19 App - An error was raised when Sales Commercial Invoice Order was run. This was fixed. 

- BCv19 App - The Show VAT Info Box option was showing on the Report Card for Reports that don't have the VAT Info Box displayed on the report. 

- BCv19 App - The caption Registered Office was printing in the Report Footers even if there was no value in the field on the SD Document Pack Setup Card. 

- BCv19 App - In the Sales Invoice, the first VAT Line was printing in the second row of the VAT Info Box instead of in the first row. 

- BCv19 App - The Total Amount in Words was worded incorrectly for certain units. 

### 3.4.2

#### Enhancements

- BCv19 App - Removed an unused Action from the Setup Card. 

- BCv19 App - Added the Latest Version of the product and the AppSource URL to the About Page. 

- BCv19 App - Added the Latest ISV Licence Control with fix to Free Trials in Public Environments. 

- BCv19 App - The SD Document pack permission set was changed from an xml file to an extension object.

- BCv19 App - The Product Activation page was changed to disable the Activate button unless a Product Key is filled in order to avoid an error being raised.

### 3.4.1

#### Enhancements

- BCv17 App - A change was made to the branding filters to allow filtering on a specific field where the field is empty '', <> etc.

- BCv17 App - The latest version of the ISV Licence Controller was added to the product.

#### Bug Fixes

- BCv17 App - A fix was made to the SDY DP Statement Open Items where the currency loop was not summarising totals correctly if there was more than one currency in the report.

### 3.4.0

#### Enhancements

- BCv17 App - A change was made to print the QR Barcodes on the SD Document Pack Bank Account Reconciliation Statement Test Report.

- BCv17 App - A change was made to print the QR Barcode on the SD Document Pack Bank Account Reconciliation Statement Report.

- BCv17 App - The Default Data codeunit was removed from running at App installation and was surfaced on the Assisted Setup action in the SD Document Pack Setup Card as per our other ISV products.

- BCv17 App - The IBAN conversion logic as per the standard Dynamics 365 Business Central codeunit was applied to the SD Document Pack Branding functionality.

- BCv17 App - The Licence Controller message displayed when a user tries to activate a second trial licence for the product on the same site was amended.

- BCv17 App - The Fields in the Overdue Entries section of the SD Document Pack Statement Report were aligned to the fields in the Entries section of the report.

- BCv17 App - A change was made to the SD Document Pack Pro Forma Invoice to display the Standard Texts used to display the Packaging Info.  

- BCv17 App - The SD Document Pack Commercial Invoices Email Body names were updated to reflect the reports they were based on - Order, Shipment and Invoice.

- BCv17 App - The SD Document Pack Commercial Invoices report names were updated to reflect the reports they were based on - Order, Shipment and Invoice.

- BCv17 App - Field Captions were updated in the Company Info Formatting FastTab on the Setup Card.

- BCv17 App - Updated a field's caption and tooltip on the SD Document Pack Setup Card.

- BCv17 App - On import of setup data using the Assisted Setup action in the Setup Card, a message is displayed that Records have successfully imported.

- BCv17 App - The URLs in the About page were updated for consistency.

- BCv17 App - The Tax Caption field in the SD Document Pack Setup Card was limited to a length of 6 characters. 

- BCv17 App - The Bank Account No field on the SD Document Pack Setup Card and the Report Card was increased to 30 characters as per standard Dynamics 365 Business Central.

- BCv17 App - The Bank Account Name field on the Setup Card and the Report Card was increased to 100 characters as per standard Dynamics 365 Business Central.

- BCv17 App - On install the HttpClient option in the Extension Management page is now automatically enabled.

- BCv17 App - Changes were made to the SD Document Pack Trial Licensing validation - only one free trial licence per product per site is now permitted. 

- BCv17 App - Made a change to the following reports layouts to allow to "Use for Email Body" in Report Selection for SD Documents Pack's Sales Quote, Sales Invoice, Sales Order Confirmation, Sales Credit Memo, Sales Proforma Invoice, Customer Statement (Open Items), Customer Statement (Balance Forward), Purchase Order, Sales Commercial Invoice, Sales - Commercial Shipment and Sales - Commercial Invoice.

- BCv17 App - A "Disable Powered by www.DynamicsShop.com" was added to the Setup Card. This allows users that have a fully licenced (not a free trial licence) to hide this text on SD Document Pack documents and reports.

- BCv17 App - The TAX Array and Total Box grids on the reports were changed to 5 rows and were evenly aligned with each other.

- BCv17 App - Added a Company Info Formatting FastTab to the Setup Card. This allows the User to exclude fields from the Footer and to define the captions to display for the fields.

- BCv17 App - Added a Bank Info Formatting FastTab to the Setup Card. This allows the User to exclude fields from the Footer and to define the captions to display for the fields.

- BCv17 App - A TAX Caption was added to the SD Document Pack Setup which allows user to specify the Tax Caption to print on SD Document Pack documents and reports GST, VAT, TVA etc. If the field is blank then the Tax Caption defaults to VAT.

- BCv17 App - A Text option has been added to the Info Box to allow users to define text to print in the Info Box.

- BCv17 App - Added an option at Document Level to allow the option to print Sell To, Ship To or none on the documents and reports.

- BCv17 App - Changes were made to the Colours FastTab in the Setup Card - the FastTab was renamed from Colour FastTab to Logo FastTab, a text guide for optimal logo size was added and the Company Logo was displayed with a quick link to the Company Information page.

- BCv17 App - Code was reviewed to ensure that Licence Expiry Date prompts do not stop functionality before the licence has actually expired.

- BCv17 App - When choosing the Product Activation action prompt the user is prompted that that they need to ensure that they have allowed HttpClient Requests in the Extension Settings page for SD Document Pack.

- BCv17 App - The SD Document Pack Report Selection List is only populated when the Assisted Setup has been run. This Report Selection List is a temporary table populated from the SD Document Pack Reports List page.

- BCv17 App - The About page and the Activate your Product page were removed from the Tell Me.

- BCv17 App - The function to print the VAT Registration No. in the Company Info footer was inadvertently commented out. The function was re-instated.

- BCv17 App - A link to the standard Company Information page was surfaced on the Logo FastTab in the SD Document Pack Setup Card.

- BCv17 App - The Product Info URL link in the About page was updated.

- BCv17 App - The prompt that the licence needs to be validated was displaying twice on selecting the Setup Action. The prompt now displays once.

- BCv17 App - A change was made to the Assisted Setup to setup default data in the current company only. Also a prompt is now displayed and a message is displayed on insert of default data.

- BCv17 App - The Commercial Invoice FastTab was removed from the Setup Card. The Packaging Information Standard Text field was moved to the General FastTab, was recaptioned and the tooltip on this field was updated.

- BCv17 App - The About action was removed from the SD Document Pack Role Centre to keep the Role Centre standardised with the Role Centres of our other ISV products.

- BCv17 App - A number of visual changes were made to the SD Document Pack Setup Card to standardise with the Setup Cards in our other ISV products - menu groups were regrouped and renamed and actions were moved.

- BCv17 App - Functionality was added to allow for easy update to the default report selection settings.

- BCv17 App - A quick link was added to the standard Dynamics 365 Business Central Company Information page on the Setup Card to allow for easy Company logo load.

- BCv17 App - The licence key controller was added to the product. A change was made that if the licence is not a free trial licence then the Powered by www.DynamicsShop.com text on the reports can be disabled.

- BCv17 App - The SD Document Pack Purchase Order report was updated to show detail lines.

- BCv17 App - The SD Document Pack Pro-Forma Invoice was updated to show detail lines.

- BCv17 App - The SD Document Pack Sales Order was updated to show detail lines. 

- BCv17 App - Brexit changes from C/AL release 3.3.7 of SD Document Pack were added to the BCv17 code base. 3 Commercial Invoices were created - new variants of the Sales Invoice Report, Sales Shipment Report, and Sales Order Confirmation Report. 

- BCv17 App - The Barcode API was replaced.

- BCv17 App - Changes were made to the code for AppSource Validation.

- BCv17 App - The functionality in SD Document Pack Reports and Documents was updated to replace the Cross Reference No with the Item Reference feature as per standard Dynamics 365 Business Central.

- BCv17 App - AppSource warnings were fixed in the SD Document Pack code base.

- BCv14 App - The BCv17 v3.4.0 code base was backported to BCv14 and a BCv14 v3.4.0 version of SD Document Pack was released.

#### Bug Fixes

- BCv17 App - Fixed an issue where the Barcode type c39 was not printing on the SD Document Pack Bank Account Recon. Statement Report.

- BCv17 App - An error that was raised when the SD Document Pack Purchase Order Report was run was fixed.

### 3.3.7

#### Enhancements

- NAV 2016 C/AL - A new field was added to the SD Document Pack Setup to allow users to specify the Standard Text field that should appear on the Commercial Invoices. On print of the report SD Document Pack raises an info message if the Standard Text specified in the Setup doesn't appear on the Sales Lines. Users manually insert and update the Standard Texts on the Sales Lines. 

- NAV 2016 C/AL - A new field was added on the Setup card to allow users to specify the field to use as the EORI Number for the Customer. This field can then be added to the InfoBox on the Commercial Invoice Reports. 

- NAV 2016 C/AL - A change was made to remove VAT calculations from the Commercial Invoice on the Sales Shipment Report. 

- NAV 2016 C/AL - A new variant of the Sales Invoice Report was created for Brexit. 

- NAV 2016 C/AL - A new variant of the Sales Shipment Report was created for Brexit. 

- NAV 2016 C/AL - A new variant of the Sales Order Confirmation Report was created for Brexit. 

### 3.3.6

#### Enhancements

- BCv16 App - The test licensing was removed from the product.

- BCv16 App - The Publisher name was updated.

- BCv16 App - The barcode text was sharpened.

- BCv16 App - The product logo was changed.

- BCv16 App - The order of the Actions in the Setup Card was changed.

- BCv16 App - Name and Description fields were increased from a length of 50 to 100 as per standard D365BC.

- BCv14 App - A fix was made to an error raised when running the Statement reports from the Tell Me.

- BCv14 App - Name and Description fields were increased from a length of 50 to 100 as per standard D365BC.

- BCv14 App - The colour picker component was removed from the code.

#### Bug Fixes

- BCv16 App - Fixed an issue where the Proforma Invoice report was not printing details in the Report Info Box.

- BCv16 App - A fix was made to a character length error in the Remittance Advice Report ID 43006022.

- BCv16 App - Fixed an issue where a warning message was raised when the user chooses the SD Document Pack Role Centre. 

- BCv14 App - Fixed an issue where the Proforma Invoice report was not printing details in the Report Info Box.

- BCv14 App - A fix was made to a character length error in the Remittance Advice Report ID 43006022.

- BCv14 App - A fix was made to the Open Items Customer Statement. The currency loop was not summarizing totals correctly when the Ignore Zero Amount Lines option was switched on and there were multiple currencies on the report. 

### 3.3.5

#### Enhancements

- BCv14 App - "BACS Ledger Entry" references were removed from the GB App.

- BCv14 App - Name and description fields were increased from 50 to 100 characters as per standard D365BC.

### 3.3.4

#### Enhancements

- BCv16 App - Report names were changed from SDY UL to SDY DP.

- BCv16 App - Test codeunits were created.

- BCv16 App - A new logo was added to the product.

- BCv16 App - Changes were made to SD Document Pack Role Centre. KPIs were surfaced.

- BCv16 App - Fixed an issue where the Proforma Invoice details were not printing details in the Info Box.

- BCv16 App - The VAT Reg Entry Update Report was removed from the Release.

- BCv16 App - The colour picker component was removed from the code.

- BCv16 App - SD Utilities Launch Documents were rebranded to SD Document Pack.

- BCv16 App - Objects were readied for App Source Submission.

- BCv16 App - The code base for D365BCv14 was converted to D365BCv16.

- BCv14 App - Report Request pages were reviewed and the "No. of Copies" filter was removed as per standard D365BC reports.

- BCv14 App - On the SD-UL Manifest report, a blank line in the Footer was removed.

- BCv14 App - The barcode image quality on the SD_UL Sales Quote report was improved.

- BCv14 App - The Colour Preview displays were removed from the D365BCv14 code base.

- BCv14 App - The Simply Dynamics Launch dll files were removed from the D365BCv14 code base.

- BCv14 App - The image component of the info box was removed from the D365BCv14 code base and the info box is now presented as an array.

- BCv14 App - Objects to upgrade SD Launch from C/AL objects to AL were developed.

- BCv14 App - Created an installation codeunit to hardcode report setup values on a fresh install of SD Launch for D365BCv14 App.

- BCv14 App - Added all the changes that were made to reports in the C/AL objects to the BCv14 extensions code base.

- A Payment Services Panel was added to the  SD-UL Pro-Forma Invoice (issued as a separate NAV2018 fob).

- A Payment Services Panel was added to the SD-UL Sales Order Confirmation (issued as a separate NAV2018 fob).

- BCv14 App - The GB Bank Reconciliation Reports were converted to D365BCv14 extensions.

- Additional filters were added to the Request page on the SD-UL Manifest Report.

- Changes were made to the SD-UL Manifest report to allow more orders to fit on the report page.

- A Payment Services Panel was added to the SD-UL Invoice (issued as a separate NAV2018 fob).

- A number of fields were added to the SD-UL Manifest Report.

- The Ship-to Address field on the SD-UL Manifest Report line was left aligned.

- A number of fields and new groupings were added to the SD-UL Manifest Report.

- BCv14 App - A change was made to the SD-UL Sales Quote document to repoint to the new Archive Quotes and Archive Order fields in D365BC.

- BCv14 App - A non-standard D365BC virtual sorting key was removed from the SD-UL Delivery Docket Report.

- BCv14 App - A non-standard D365BC virtual sorting key was removed from the SD-UL Manifest Report.

- BCv14 App - The barcode option types were reviewed and reworked.

#### Bug Fixes

- BCv14 App - A fix was made to correct balances on the SD-U Open Item Statement report when run from SD Bulk Mailer.

- A fix was made to correct balances on the SD-U Open Item Statement report when run from SD Bulk Mailer.

- BCv14 App - A fix was made to a  publishing error raised when the Bank Reconciliation reports were published.

- BCv14 App - Reviewed and reworked the QR barcode printing.

- BCv14 App - The barcode image on the SD-UL Reports was resized.

- BCv14 App - Added a filter fix to the SD-UL Statement Balance report to fix an issue when the SD-UL Statement Balance is run from SD Bulk Mailer.

- Added a filter fix to the SD-UL Statement Balance report to fix an issue when the SD-UL Statement Balance is run from SD Bulk Mailer.

- Fixed an error that was raised  in the Launch Setup card when the ellipse button on the barcode background and foreground colour fields was chosen.

- BCv14 App - Fixed an issue in the Launch Setup where the first report in the Report Setup page was opening no matter what report was chosen from the list.

- BCv14 App - Fixed an issue where a message was raised when a new report was added to the Reports Setup page.

- BCv14 App - Fixed an issue where a barcode was printing on the reports even if no barcode was set to print in the SD Launch Setup.

- BCv14 App - Fixed an error that was raised  in the Launch Setup card when the ellipse button on the barcode background and foreground colour fields was chosen.

- BCv14 App - Fixed an issue where an error was raised when the About Action was selected.

- BCv14 App - Visual changes were made to the Launch Setup Card.

- A fix was applied to the VAT calculations on the SD-UL Sales Credit Memo report when printing copies of the report.

- Fixed an issue in the VAT Panel in the SD-UL Sales Credit Memo Report.

### 3.3.3

#### Enhancements

- A change was made to the calculation of Gross Weight and Net Weight to the reports that display the commodity code information.

- Removed references in the Colour Picker Dialog page to the Simply Dynamics Colour Picker dll.

- A change was made to the commodity info option list on the Launch Setup to allow for a <blank> option.

- The SimplyD.SD Utilities - Launch.AddIn.Installer.exe was removed from the release bundle.

- The SD Utilities Launch - Proforma Invoice report was modified to display commodity code information.

- The SD Utilities Launch - Sales Invoice report was modified to display commodity code information.

- The SD Utilities Launch - Delivery Docket report was modified to display commodity code information.

- The SD Utilities Launch - Sales Shipment report was modified to display commodity code information.

- The SD Utilities Launch - Sales Order Confirmation report was modified to display commodity code information.

- New functionality was added to provide an option to display commodity code information on certain reports.

- A change was made to the calculation of Gross Weight and Net Weight to the reports that display the commodity code information.

- Removed references in the Colour Picker Dialog page to the Simply Dynamics Colour Picker dll.

- A change was made to the commodity info option list on the Launch Setup to allow for a <blank> option.

- The SimplyD.SD Utilities - Launch.AddIn.Installer.exe was removed from the release bundle.

- The SD Utilities Launch - Proforma Invoice report was modified to display commodity code information.

- The SD Utilities Launch - Sales Invoice report was modified to display commodity code information.

- The SD Utilities Launch - Delivery Docket report was modified to display commodity code information.

- The SD Utilities Launch - Sales Shipment report was modified to display commodity code information.

- The SD Utilities Launch - Sales Order Confirmation report was modified to display commodity code information.

- New functionality was added to provide an option to display commodity code information on certain reports.

#### Bug Fixes

- Fixed an error that was raised when the SD-UL Sales Shipment report was run.

### 3.3.2

#### Enhancements

- Changed the product name in the About Card to "SD Utilities - Launch Documents".

#### Bug Fixes

- Fixed the group name of the About Action in the SD Launch Setup Card.

- Fixed an issue where the ignore Zero Amount Lines option was showing the incorrect total on SD-U Statement Open Items.

### 3.3.1

#### Enhancements

- Repositioned the fields on Colours FastTab in the Launch Setup.

- Made a change to the column alignment on the Sales Shipment Report - 43006013.

- Made a change to allow users to manually enter the HTML colour code for Header and Footer Background and Text colours on the Launch Setup.

- Updated the logic in the report to display the details of the VAT Analysis on the Purchase Return Order.

- Updated the logic in the report to display the details of the VAT Analysis on the Sales Return Order.

- Layout changes made to the Sales Shipment Report – 43006013.

#### Bug Fixes

- Fixed an issue in the Bank Reconciliation Reports where the reports were including historical/posted transactions when printing by statement.

### 3.3.0

#### Enhancements

- Made user improvements for adding reports and fields to the Brand Triggers.

- Added the Report Name to the Barcode drill down on the Launch Setup.

- Added the Report Selection as a flowfield without drilldown capability to the Launch Setup.

- Added the Enforce Release Test functionality to the SD-UL Proforma Invoice, SD-UL Pick Instruction, SD-UL Purch. Order, SD-UL Delivery Docket, SD-UL Sales Return Order, and the SD-UL Purchase Return Order.

- Removed the Bank Reconciliation GB Reports from the SD-Utilities Launch fob.

- Made a number of user interface changes to the SD-UL Launch Setup Card. Regrouped and renamed Actions and Groups in the Ribbon.

- Made a change in the SD-UL Launch Setup Card to auto refresh the Bank Account Name and Bank Account No. when the Bank Account is chosen

- The data rows in the VAT Footer and Total Footer in the SD-UL Sales Return Order and the SD-UL Purchase Return Order were centered.

- The Direct Unit Cost on the SD-UL Purchase Order Report was aligned as per the other numeric columns on the report.

- Added the functionality to include the Company Country in the Company Address.

- Added the standard NAV Email functionality used in Document Layouts to the SD-UL Statement Reports.

- If the Enforce Released checkbox is selected on the SD-UL setup for a report, when printing the report for a range of records an error was thrown and the report printing was exited. A change was made that when running for a range of records to exclude the unreleased records rather than raise an error.

- The objects in the SD-U Bank Acc. Recon. Reports.fob fix for NAV 2018 were stamped with the correct version and the modified flag was set to false.

- The SD Utilities - Launch Footer Messages, Bank and VAT Reg lines were removed from the SD-UL Work Order Report.

- The data rows and captions on the VAT Footer and Total Summary Footer were centered on the SD-UTLA Documents.

- The Expected Receipt Date was added to the SD-UL Purchase Order Report.

- New functionality was added to allow Company Address setup to include or exclude as per the Report Address formatting.

- Branding Logic was applied to Report SD-UL Purchase - Receipt.

- Branding Logic was applied to Report SD-UL Customer Payment Receipt.

- Branding Logic was applied to Report SD-UL Statement Balance Fwd.

- Branding Logic was applied to Report SD-UL Purchase Return Order.

- Branding Logic was applied to Report SD-UL Sales Return Order.

- Branding Logic was applied to Report SD-UL Manifest.

- Branding Logic was applied to Report SD-UL Delivery Docket.

- Branding Logic was applied to Report SD-UL Remitt. Advice - Entries.

- Branding Logic was applied to Report SD-UL Remitt. Advice - Journal.

- Branding Logic was applied to Report SD-UL Purch. Order.

- Branding Logic was applied to Report SD-UL Cheque with Advice.

- Branding Logic was applied to Report SD-UL Statement Open Items.

- Branding Logic was applied to Report SD-UL Proforma Invoice.

- Branding Logic was applied to Report SD-UL Sales Credit Memo.

- Branding Logic was applied to Report SD-UL Sales Shipment.

- Branding Logic was applied to Report SD-UL Sales Order Confirm.

- Branding Logic was applied to Report SD-UL Sales Invoice.

#### Bug Fixes

- Fixed an issue where removing a record in the SD-UL Brand table did not delete the associated records in the SD-UL Brand Trigger table.

- Fixed an issue where the Branding Bank Details were not printing on the SD-UL Open Items Statement when Branding was defined for the report.

- Fixed an intermittent issue raised when adding report fields to the branding triggers.

- Fixed an issue where, if Branding was set up for the SD-UL Sales Order Report, the Branding Logo was printing on the SD-UL Sales Order irrespective of the defined Branding Triggers.

- Fixed an issue where the SD-UL Delivery Docket displayed the contact name when the contact name was set to not print.

- Fixed an error raised when choosing the Add All Launch Reports in the SD-UL Brand Card.

- Fixed an issue where selecting the Card Action in the Reports FastTab List of the Launch Setup did not open the card for the current record.

### 3.2.1

#### Enhancements

- Made a change to display the Phone Number for the Brand on the report.

- Made a change to display the Bank Details for the Brand on the Report.

#### Bug Fixes

- Fixed an issue where there was a fieldsize error raised on preview of the Launch Sales Quote report.

- Fixed an error raised when choosing the Add All Launch Reports Action on the SD-UL Brand Card.

### 3.2.0

#### Enhancements

- Minor visual change made to the Role Centre.

- Lot reference and lot quantity were added to the Sales Invoice and Delivery Docket.

- Fixed an issue in the Customer Payment Report where Customer details were not appearing on the Report Header when a customer payment was not allocated.

- Removed redundant Action on the Launch Setup Page.

- Added an About Action to the SD-UL Launch Setup Page.

- Fixed a compile issue in the SD-UL VAT Entry Reg Update Report.

- Removed Standard NAV OneNote, Notes, and Links from the Launch Setup Pages.

- Added the About Page to the SD-UL Launch Setup Page.

- Made minor visual mods to the Launch Role Centre. Added all Launch Reports and Documents to the Role Centre.

- Included a demo config package in the release.

- Removed the Barcode and Footer list pages from the Launch Setup. Added the Report List page to the Launch Setup.

- Added new flowfields to the Launch Setup Table and Page.  Drill down available on Info Box Items.

- Made modifications to the SD-UL Statement Bal Fwd. Report layout.

- Made modifications to the SD-UL Manifest layout.

- Made modifications to the SD-UL Delivery Docket  layout.

- Made modifications to the SD-UL Purchase Order layout.

- Created a new SD Utilities Launch variant of the standard Works Order Report.

- Made modifications to the SD-UL Pick Instruction layout.

- Made modifications to the SD-UL Statement Open Items layout.

- Made modifications to the SD-UL Proforma Invoice layout.

- Added an Import Config Package Action to the Launch Setup Page.

- Made modifications to the SD-UL Sales Credit Memo layout.

- Added a Test Print Action to allow users to print the report for the report line.

- Made modifications to the SD-UL Sales Shipment layout.

- Made modifications to the SD-UL Sales Order Confirm layout.

- Made visual and layout modifications to the SD-UL Sales Invoice document.

- Made minor layout changes to the SD-UL Sales Quote.

- Created a new Support About Page.

- Made a change to the Purchase Order Report to display the Vendor Item Cross Reference No. on the Report. If a Cross Reference doesn't exist, then display the Vendor Item No. from the Item table.

#### Bug Fixes

- Fixed an issue in the SD-UL Sales Credit Memo VAT Panel.

### 3.1.0

#### Enhancements

- Created a NAV 2018 fix for SD-U Bank Acc. Recon. Reports. Attached to release as a separate fob.

### 3.0.0

#### Enhancements

- Applied new branding functionality to the SD-UL Sales Quote.

- Added new functionality to allow document branding by applying filters.

### 2.3.3

#### Enhancements

- In the SD-U Customer Payment Receipt report the heading 'Payer' as per Remittance Advice was added to keep layouts standard across all documents.

- Added a separator line on the footer of the Launch Customer Payment Receipt as per the Launch Remittance Advice to keep the layout standard.

- Made changes to the functionality of the Info Box to allow for increased standard NAV header table field sizes in future NAV versions.

#### Bug Fixes

- Applied the Include/Exclude Address formatting as specified on the Launch Setup Page to the Launch Customer Payment Receipt.

### 2.3.2

#### Enhancements

- Refactored DLL from Cebuella to Simply Dynamics.SD Utilities - Launch split into own project.

#### Bug Fixes

- Fixed an issue where "Printed By" was showing on the Launch Customer Payment Receipt when not setup in the settings to print on the report.

- Added a separator line on the footer of the Launch Customer Payment Receipt as per the Launch Remittance Advice to keep the layout standard.

- Added heading 'Payer' on the Launch Customer Payment Receipt as per the Launch Remittance Advice to keep the layout standard.

- Applied decimal formatting to the quantity fields on the Launch Purchase - Receipt report as per our other Launch documents.

- Fixed an issue where the Receipt No. is not printing in the Header of the Launch Purchase Receipt. It appears to be incorrectly printing the Order No of the receipt (where it exists), or printing blank.

- Removed the bank details section from the Launch Purchase - Receipt Report.

- Fixed an issue in the Launch Customer Payment Receipt where the report was printing header details, skipping the rest of the page and then printing the full report on the second page.

- Fixed an issue whereby the Report Copies were not collating by Document.

- In the SD-U Sales Order Confirmation, the VAT ID caption was left-aligned to the column.

- In the SD-U Sales Order Confirmation, space was added between the Qty and UOM columns, and the Qty caption was aligned to the column.

- In the SD-U Sales Shipment, space was added between the Qty and UOM columns.

- In the SD-U Proforma Invoice, the Qty column caption was left-aligned to the field.

- In the SD-U Proforma Invoice, the VAT ID column caption was left-aligned to the field.

- For each Launch report, a space was added after each comma (,) in the Company Address field.

### 2.3.1

#### Enhancements

- Linkbox: 

- Add a setup field to specify document checkout to a default Drop Point check out path.

### 2.3.0

#### Enhancements

- Linkbox: 
- Created check in/check out functionality for Linkbox Version Control. 
- Added Edit Permission to Linkbox. 
- Cleaned up code. Launch: 
- Upgrade Launch to use Control Suite.

#### Bug Fixes

- Linkbox: 
- Fixed Error Message raised when viewing a file in the Drop Point or Versions List. 
- Fixed situation where the View Option was always displaying the same file.

### 2.1.2

#### Enhancements

- Updated readme.txt file. 
- Launch - applied Launch standardised document layouts to the Posted Purchase receipt report.
- Linkbox - enhanced Linkbox file overwrite confirmations.

#### Bug Fixes

- Linkbox - fixed a bug in the scrolling functionality when selecting an Icon for a Drop Point in the Drop Point Card. 
- Linkbox - fixed an issue where when choosing to Edit certain files from the Dropped Files Factbox an error is raised. 
- Linkbox - fixed an issue where Delete Permission on Dropped Files Fact Box not taken into account when you right-click on the Dropped Files Fact Box.
- Launch - fixed alignment issue on the SD-U Customer Payment Receipt Document.

### 2.1.1

#### Enhancements

- Linkbox - enhanced the Icon Scoller picker.
- Linkbox - enhanced the Template functionality - allow users to choose to push out the Templates to the Linked tables and select the template they want to attach to the records. 
- Launch - surface filters on SD-U Bank Acc. Recon. Stmt Document. 
- Launch - surface filters on the SD-U Bank Acc. Recon. Smt Test Document. 
- Launch - improvement in code to allow for barcode record type value. 
- Launch - optimised the image preview generation. 
- Launch - surfaced the newly added Documents to the Role Center. 
- Launch - applied Launch standardised document layouts to the SD-U Customer Payment Receipt Document.

#### Bug Fixes

- Launch - fixed alignment issue on SD-U Sales Return Order Document. 
- Launch - fixed alignment issue on SD-U Purchase Return Order Document.
- Launch - changed the Launch Documents to use the document currency code rather than customer/vendor currency code when deciding the bank details to use on the footer.
- Linkbox - fixed a bug in the auto linking functionality of a Template File to a record.
- Linkbox - fixed a bug in the Version History of Dropped Files Linked to a record. 
- Linkbox - fixed a bug in the Version History of auto-created Template Files. 
- Linkbox - fixed a bug where an error was raised on creation of a new record when a Drop Point (with Versioning turned on) is added to a Card Page. 
- Linkbox - fixed a bug where the Icon Scroller images were not updating. 
- Power BI - fixed an issue where the Return Sales Order as raising an error if there was no BI Setup.

### 2.1.0

#### Enhancements

- Launch: 
- All Launch Documents and Reports underwent a code clean up. 
- A Delivery Docket was added to Launch. 
- A Manifest Report was added to Launch. 
- A Bank Account Reconciliation Statement (Posted Entries) was added to Launch. 
- A Bank Account Reconciliation Statement (UnPosted Entries) was added to Launch.
- A Stock Take Report was added to Launch.
- A Sales Return Order was added to Launch.
- A Purchase Return Order was added to Launch. 
- A Balance Forward Statement was added to Launch. 
- A standardised layout was applied across all Launch Documents and Reports. 
- All Field Names and abbreviations were standardised. 
- Decimal formatting was standardised across all Launch Documents and Reports. 
- A new Footer totalling layout and a VAT Grid layout was applied and standardised across the Launch Documents. 
- Positioning of Logos was made consistent across all Launch Documents and Reports. 
- A standard Header and Footer layout and banner, for portrait and landscape layouts, was applied across all Launch Documents and Reports. 
- An enhancement was made to allow users to choose the Background and Foreground Header and Footer Banner Colours that would print on all Launch Documents and Reports using a Colour Picker.
- Enhancements were made to the Remittance Advice Reports in Launch. Captions were changed, fields were resized. 
- Functionality to define and display a Barcode on all Launch Documents and Reports was added to Launch. 
- A Report Info Box was applied to the layout of all Launch Documents and Reports.
- Functionality was added to allow users to dynamically add the fields to print in the Report Info Box. 
- Minor layout changes were made to existing individual Launch Documents and Reports.
- New functionality was added to allow users to select the Background and Foreground Header and Footer Banner Colours by using a colour picker. 
- Improved the resolution of the Report Info Box. 
- Fields and FastTabs for new functionality were added to the Launch Setup Card.

Linkbox: 
- New functionality added to Linkbox to Security Filter Tables and Pages enabling permissions to be set. 
- Updated the Linkbox Setup to include Security Filters 
- New Security Filters for Dropped Files applied. 
- New Security Filters for Drop Areas applied.
- Added Company to membership lookup in Linkbox Security Filters. 
- New Version Control functionality added to Linkbox. 
- Provided Version Edit functionality. 
- When viewing a file in the Drop Area, the file is set to read only. 
- Coded increments for Dropped File Entry No. 
- Created a new Table and Page to list, and provide, Dropped File Version functionality. 
- Created Template functionality for Linkbox.
- Changed functionality to retain the SD Linkbox - Orphan Link Files. 

Profiler: 
- An XMLPort was created to export and import Profile Select List. 

PowerBI: 
- Added Sales Quote Tracking Functionality to PowerBI. 
- Added functionality to provide for CSV Import/Export for BI Date data. 
- Added the PowerBI Setup Page to the SD Utilities Role Centre

#### Bug Fixes

- Launch: 
- Fixed bug where the Statement report overwrites any Date Filters that are passed into the report. 
- Fixed bug where colour choices picked using the colour picker were being re-set. 
- Fixed bug where the QR Barcode was not displaying correctly in the Report Information box. 
- Fixed bug in the Launch Report Setup whereby when a new record was added to the Report Info Box Fields for a specific report, the Field No. was not appearing in the order as specified but rather in the order as input. 
- Fix was made to the barcode generation to display as per Launch Report Setup. 
- Minor layout changes were made to existing individual Launch Documents and Reports.
- Fixed bug which allowed a Barcode to be setup on the Launch Report Setup with a DPI of zero. 
- Fixed bug where the List of Reports showing in the Launch Setup was being hard code filtered on an earlier version release. 
- Fixed bug where the InfoBox and Barcode were not being updated. 

Linkbox: 
- Drop Point Icons on List Pages are intermittently not displaying when the List Page is loaded from within the Role Centre.
- Fixed bug where a link is being created to records with no file attached when a record for a Template File that has no File Imported (a blank Filename field) is created. 
- Fixed error raised when an empty file is dragged and dropped into a Drop Point.

Profiler: 
- Remove irrelevant Actions from the Profile Selection List.

### 1.1.0

#### Enhancements

- Linkbox - created XMLPorts for Upgrade to NAVW19.00 - V2.1.0 
- Profiler - created Profiler Date export 
- Power BI - created BI Date XML PortXML Port

#### Bug Fixes

- Launch - fixed bug where statement report overwrites passed in Date Filter

### 1.0.2

#### Enhancements

- Linkbox - Drop Area was not displaying on the Role Center.
- Launch - Unable to run statement when specified from report selection.

### 1.0.1

#### Enhancements

-  Documentation fixes.

### 1.0.1

#### Enhancements
- Linkbox - Created an XmlPort for setting up control Add-in. 
- Profiler - Refactored the object selection. Rewrote the reports to loop on the questions and do basic formatting of them. 
- Profiler - Renumbered and reordered the Tables and Pages. 
- Cleaned up the objects. 
- Code upgraded to 2016.
