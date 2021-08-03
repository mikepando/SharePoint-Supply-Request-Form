# Supply Request Form For SharePoint

<img src="/images/supply_submission_window.png" style='border:1px solid #555'>

This is a supply request form and workflow for SharePoint 2019. Originally designed as a form to allow users to request supplies from HQ and track changes from fulfillment. Different departments in the warehouse were responsible for supplying different items. Therefore, when a specific item is requested from the form, the respective department is notified. 

## Utilizes

* [Power Automate](https://flow.microsoft.com/en-us/)
* [SharePoint](https://www.microsoft.com/en-us/microsoft-365/sharepoint/collaboration)
* [Power Apps](https://powerapps.microsoft.com/en-us/)

## How it works

A user navigates to the supply requests SharePoint list and creates a new request using a custom PowerApps form. This form has different screens for the requester and for fulfillment. The user can select the items and quantity they want and submit the form. Depending on the requested items different departments are notified for fulfillment. Once the item has been fulfilled, the responsible department can go back to the form and update the sent quantity on the fulfillment page. The requester is then notified.  

## How to use
1. The stp file is a SharePoint template of the list created. Upload this to your SharePoint List Template Gallery.
2. Import the zipped flow folder into Power Automate.
3. Import the zipped forms folder into PowerApps.
4. Refer to the documentation file for user usage in SharePoint.
5. Comments have been added to most actions in Power Automate. 
