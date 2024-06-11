# SalesforceCaseStudy

Created a service request and incident request web page in Salesforce.
Created an App named ABC Limited.
Created Accounts, Contacts, Products and Assets.
Created Business Admin profile and gave full access (CRUD) to all service cloud objects.
Created Support Agent profile and gave read access on all Service cloud objects and Full access (i.e., CRUD capabilities) on Case Object.
Configured a hierarchy where Business Admin and Support Agent are at the same level.
Configured Entitlement Process with above milestones which will be active once Case is created and should exit once Case is closed.

1. Incident Type- For incident type: Standard page layout is used. I used lookup filter to create lookup for the account name related to 
contacts and entitlements.
2. Service Request Type- Created a custom service request page using aura component.

Case Assignment Rule- Case assignment should be automated with members being notified once a case is assigned.
Created a Validation rule where an owner must take the ownership before starting working on a case.
Created an action button to Take Ownership before starting to work on a case using apex class.
Created a trigger on case object to update the milestone.
Created an apex class to calculate the milestone completion time.
Created an apex class to count the number of cases per account.
Created a trigger on Case object to update the count of total number of Cases per Account.
