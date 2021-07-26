# Salesforce Zimlet

This is an updated version of the Salesforce Zimlet that works on Zimbra 8.8.15/Zimbra 9 and Salesforce Summer '21 (API version 52.0).

Zimlet automatically checks if the current mail has any Salesforce information and displays them in a Bar. Note that this zimlet requires access to Salesforce api's which are available only for Salesforce Enterprise or Performance editions. So this zimlet will work only with&nbsp;Salesforce Enterprise or Performance editions.

Salesforce Bar Provides:

- Salesforce Context (Contact, Lead, Cases, Account & Opportunities) information.
- Provides links to quickly edit/view/clone various Salesforce Objects
- Provides toolbar buttons to perform various operations like: Add Notes, Email2Case
- Provides Salesforce Search capabilities.

On your Zimbra server as user `zimbra` allow connections to Salesforce:
 
      zmprov mc default +zimbraProxyAllowedDomains *.salesforce.com
