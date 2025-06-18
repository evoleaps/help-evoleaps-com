# Getting Started

## Overview of Smart Excel Import
This app simplifies and accelerates the process of importing data from Microsoft Excel into Dynamics 365 Business Central — no predefined templates or manual setup required.

Powered by advanced AI recognition, the app intelligently maps Excel columns to journal fields based on their names — even when the labels aren’t an exact match. It automatically identifies and aligns the correct fields, reducing manual effort and minimizing the risk of errors.

Just upload your Excel file, and the app will:  
- Detects relevant columns  
- Matches them to the appropriate fields  
- Ensures data accuracy and consistency

![Excel import](Assets/ImportExcel.png)

## Installation from AppSource
To install Smart Import for Excel, follow these steps:

Go to the official Microsoft AppSource page:
[**Smart Import for Excel on AppSource**](https://appsource.microsoft.com/en-us/product/dynamics-365-business-central/PUBID.evoleaps-doo%7CAID.smart-import%7CPAPPID.28e9415c-2540-4574-aa13-f22b4919437b?tab=Overview)

Complete the installation wizard. The app will be automatically deployed to your selected environment.

Once installed, open Business Central, and navigate to the Smart Import for Excel pages via the Tell Me search.

Note:
No additional configuration is required. The app is ready to use immediately after installation.




## Licensing & Free Trial
**Smart Import for Excel** is available with a free trial period so you can explore its features before committing to a subscription.

## Free Trial

- A fully functional **free trial** is available for new users.
- No setup is required to start the trial.

## Licensing

After the trial ends, a valid license is required to continue using the app. Licensing is based on:

- **Per Business Central environment** (production or sandbox).
- Subscription can be purchased directly through **AppSource** or by contacting the publisher.

For pricing and licensing details, visit the app page [Pricing](https://www.evoleaps.com/pricing).

If you need a custom plan or have any licensing questions, please contact our support team.


## Permissions Requirements in Business Central
**Smart Import for Excel** does not require any special permissions to run the app itself.

If a user has permission to read or modify a specific table in Microsoft Dynamics 365 Business Central (e.g., General Journal, Customer, Vendor, Item), they can use the app to import data into that table.

## Key Points

- There is no dedicated permission set required for the app.
- The app respects existing user permissions defined in Business Central.
- A user will only be able to import data into tables they already have access to.

## Examples

| Table | Required BC Permission |
|-------|-------------------------|
| General Journal | Permission to read/write journal lines |
| Customer | Permission to insert/modify Customer records |
| Vendor | Permission to insert/modify Vendor records |
| Item | Permission to insert/modify Item records |

## Notes for Admins

To ensure a user can use Smart Import effectively, simply verify that the user has the correct standard permissions for the target table they’re importing into. The app will not override or bypass Business Central’s permission system.


