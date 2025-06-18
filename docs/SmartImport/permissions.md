# Permissions Requirements in Business Central

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

