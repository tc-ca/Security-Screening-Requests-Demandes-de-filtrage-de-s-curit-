# Security-Screening-Requests-Demandes-de-filtrage-de-s-curit-
This is the source code for the Security Screening Request App developed using Dataverse for Teams (formerly known as project Oakdale).

## Installation / Setup
To deploy this app to your environment, follow the steps below.
1. Import the unmanaged zip solution file found in ```./Solution Zip``` from your [solutions tab](flow.microsoft.com)
2. Use the excel files found in ```./data``` to import the requried translation data into the soltuion's data tables
3. Upload the provided ```Applications_Static.xlsx``` file to your desired SharePoint Site. This is the excel file where new requests will be visible (in addition to the underlying databse)
4. Update the cloud flow ```Dataverse -> Excel``` found in the cloud flows tab of your solution.
   You will need to update each Excel online connector (there are 6 in total). To update these connnectors, your must change the Location, Document Library, and File to point to wherever you decided to upload the excel file
