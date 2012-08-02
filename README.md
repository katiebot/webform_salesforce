Drupal 7 Webform Salesforce integration
=======================================

Salesforce integration for the Webform module suitable for when your Salesforce account doesn't support the Salesforce API

There is no admin interface for this module, you will need to edit webform_salesforce.module and enter the following:
- Your Salesforce ID
- Your Webform node ID
- The CIDs for the Webform fields you wish to send to Salesforce
- The return URL
- Your email address (if required, for debugging purposes)

TODO:
- Could create an admin settings page for entering Salesforce ID, return URL and email address
- Could look into hooking into the Webform module and selecting a Webform and fields