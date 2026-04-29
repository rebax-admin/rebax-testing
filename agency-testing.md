# Agency Testing on Rebax App
## Agency Register
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|App should take Pan Card from Agency and Verify |||
|2|App should take email id from Agency and Verify |||
|3|App should take phone no from Agency and Verify |||
|4|App should take Representative name from Agency |||
|5|App should take Representative phone number |||
|6|App should take rera id from Agency and create task in Admin |||
|7|App should take GST number from Agency |||
## Agency Forgot Password
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Verify if the given email id is getting an OTP |||
|2|Verify if the OTP is Validating |||
|3|Verify if the New Password is saving |||
|4|Verify if the New password is working to login |||
## Agency CRM Page
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click on Add lead button and fill the form and verify if it works or not. Also check if the lead count is updating in Dashboard [make sure you refresh (refresh by changing This month to previous month and come back to this month tab) dashboard while checking] |||
|2|Click call button and check if it is navigating to dialer app |||
|3|Click call button and check if the add feedback popup is populating |||
|4|Enter Feedback in the add feedback popup and save and check if the feedback is updating in open lead page and CRM page |||
|5|Enter Feedback in the add feedback popup and select another status and save and check if the feedback and status is updating in open lead page and CRM page |||
|6|Enter Feedback in the add feedback popup and select another status and click on add task button and close the task popup to check if the feedback popup is still open and same |||
|7|Open feedback popup from call button and click on add task button and create a call reminder task and add task and check if the feedback popup is still open and same |||
|8|Check if the call task is created in the Tasks page and the icon for it is call icon, Also check if tasks are created in open lead page in Upcoming tasks section |||
|9|Open feedback popup from call button and click on add task button and create a site visit reminder task and add task and check if the feedback popup is still open and same |||
|10|Check if the site visit task is created in the Tasks page and the icon for it is apartment icon, Also check if tasks are created in open lead page in Upcoming tasks section |||
|11|Click lead and expand the lead and click on feedback button and check if the add feedback history popup is populating |||
|12|Click on Add New Feedback button and check if the add feedback popup is populating |||
|13|Enter Feedback in the add feedback popup and save and check if the feedback is updating in open lead page and CRM page |||
|14|Enter Feedback in the add feedback popup and select another status and save and check if the feedback and status is updating in open lead page and CRM page |||
|15|Enter Feedback in the add feedback popup and select another status and click on add task button and close the task popup to check if the feedback popup is still open and same |||
|16|Open feedback popup from feedback button and click on add task button and create a call reminder task and add task and check if the feedback popup is still open and same |||
|17|Check if the call task is created in the Tasks page and the icon for it is call icon, Also check if tasks are created in open lead page in Upcoming tasks section |||
|18|Open feedback popup from feedback button and click on add task button and create a site visit reminder task and add task and check if the feedback popup is still open and same |||
|19|Check if the site visit task is created in the Tasks page and the icon for it is apartment icon, Also check if tasks are created in open lead page in Upcoming tasks section |||
|20|Check if Whatsapp button is navigating to whatsapp app |||
|21|Check search box by typing lead names and it is showing appropriate results |||
|22|Click filter button and check if all filters are working correctly |||
|23|Click on download button after changing the filters and check if you are able to download only filtered leads |Issues|Need to edit the fields in the downloaded excel file|
|24|Click on download sample excel link and download it and add all the details in fields marked with '*' and upload it and check if its uploading and adding leads in CRM correctly  |Issue|Need to change '*' fields and make fields changes|
|25|Invoices Tab - check if all the invoices received are showing here |||
|26|Check if all the invoices are expandable and shows Lead name, lead phone number, Invoice Date, Builder name, Project name, Invoice Stage and commission amount |||
|27|Check if the download button fo invoice is working |||
## Agency Editing Leads in Open Lead Page
### Agency Customer Details
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Check if you can edit full name and save and check it is saving |||
|2|Check if you can edit Email ID and save and check it is saving |||
|3|Check if you can edit Phone number and save and check it is saving |||
|4|Check if you can add and edit alternative phone number and save and check it is saving |||
|5|Check if you can add address and save and check it is saving |||
### Agency Property Type
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Check if the dropdown for Property Type is working |||
|2|Check in the property type all 4 types (Apartments., Villas, Commercial and Plots) are available if the dropdown for Property Type is working |||
|3|Check when you select Apartments in this section the Community section is updating with all 4 dropdowns (Gated Community, Semi-Gated Community, High-Rise Towers and Standalone Building)|||
|4|Check when you select Villas in this section the Community section is updating with all 4 dropdowns (Gated Community, Semi-Gated Community, Villa Township and Standalone Building)|||
|5|Check when you select Commercial in this section the BHK section should be hidden and the Community section is updating with all 4 dropdowns (IT Park, Business Park, Mall/Retail Complex and Standalone Building)|||
|6|Check when you select Plots in this section the the BHK section should be hidden and Community section is updating with all 4 dropdowns (Gated Layout, HMDA Layout, DTCP Layout and Open Layout) and check the area selector if it is shift from SFT scale to SQYD scale |Not Working|The Area scale is not shifting from SFT to SQYD|
|6|Check if the area scale is working correctly |||
|7|Check if the budget scale is working correctly |||
|8|Check if the location input box is populating locations when typed 3 or more letters |||
|9|Check if all the sections are saving |||
|10|Check if the property search is populating correct search results according to selected property type (Make sure there are properties available in the preferred range before testing) |||
### Agency Advanced Transportation Preferences
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Enable and Disable is working and not effecting property search |||
|2|Enter office location and check if the locations are populating when typed 3 or more letters |||
|3|Enter School/College location and check if the locations are populating when typed 3 or more letters |||
|4|Click add location button and check if popup is working |||
|5|Enter Label and office location and check if the locations are populating when typed 3 or more letters |||
|6|Click on Done button and check if the location is adding |||
|7|Check if you can edit and delete these locations |||
|8|Click on Preferred Travel Time dropdown and check if all the 5 items (Under 15 mins, Under 30 mins, Under 45 mins, Under 1 hour and Over 1 hour) are selectable or not |||
|9|Check the Distance Range Slider is working |||
|10|Check if all the sections are saving |||
|11|Check if the property search is populating correct search results according to selected Advanced Transportation Preferences (Make sure there are properties available in the preferred range before testing) |||
### Agency Lead Management
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Check if lead status dropdown is working |||
|2|Check if all 6 Default status's (New, Active, Prospect, Site Visit, Booked and Dead) are selectable |||
|3|Check when site visit status is selected, if site visit popup is populating |||
|4|Fill the form and check if Select Date and Time are working |||
|5|Check if it is showing error when you try to add visit without selecting any project |||
|6|Check if select project search box is populating projects when entered 2 or more letters |||
|7|Check if it is saving when selected a project and added visit |||
|8|Check if the site visit log is updated in site visit logs |||
|9|Check if the Site visit is showing in Dashboard in Unique Site Visits [make sure you refresh (refresh by changing This month to previous month and come back to this month tab) dashboard while checking] |||
|10|Check if Lead source dropdown is working |||
|11|Check if the Lead owner dropdown is working |||
|11|Check if Interested projects search box is working and showing projects when typed 2 or more letters |||
|12|Check if we can select multiple project from the list and being added when clicked on done |||
|13|check if everything saving by clicking on save changes button and go back to CRM and come back to open lead page to verify |||
#### Agency Property Search
##### Unpaid user
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Check if agent is not a payed user and if so, check if property listings have Images, Agent Commission and View Details buttons are visible and everything else is blurred and we should have a sticky floating button asking to "Subscribe to unlock" |||
|2|When Clicked on "Subscribe to unlock" button it should navigate to subscription packages page and verify everything is working, like when clicked on Monthly and yearly tabs is it navigating or not and when clicked on upgrade now button is it navigating to payments page. |Not Working|Subscribe to unlock is not navigating |
|3|From search page click on View details button and check if apart from Builder Profile image, Project name, Builder name, likes and dislikes, Images, and Agent Commission everything should be blurred and we should have a sticky floating button asking to "Subscribe to unlock" |||
|4|When Clicked on "Subscribe to unlock" button it should navigate to subscription packages page and verify everything is working, like when clicked on Monthly and yearly tabs is it navigating or not and when clicked on upgrade now button is it navigating to payments page. |||
|5|Check search by typing in projects name and check if it is working |||
|6|Click filter button and check if all filters are working correctly |||
##### Paid users
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|After clicking property search in open lead page, Check if agent is payed user and if so, check if property listings have Images, Project Name, Project Location, Budget range, Property Type, Community, Area Range, Agent commission and View details button |||
|2|From search page click on View details button and check everything is showing and working |||
||- Project Name |||
||- Builder Name |||
||- Like and dislike Buttons |||
||- Images |||
||- Agent Commission |||
||- Able to download View Terms |||
||- Register to Builder Button |||
||- If agent doesn't have rera id are the unable to register to builder with RERA ID restrictions |||
||- When clicked able to register to builder |||
||- After Registration are we getting notification |||
||- After Builder Accepting are we getting Notification |||
||- After Builder Rejecting are we getting notification with reason |||
||- Try registering same lead again to the builder and check that we are getting a message saying we already register this lead |||
||- Try registering other lead and check if that lead is able to registered |||
||- Try registering the same lead to other builder's project and check if it is registering |||
||- Travel Information |||
||- Project Over View |||
||- USP Highlights |||
||- Property Specifications - Property Type, Community, Location, Project Status, Possession Date, Project Area, No of Towers, Total Floors, Total Units, Available Facings and RERA ID |Issue|RERA ID is missing|
||- Property Pricing - Budget Range, Price per SFT, Car Parking Cost, Extra car Parking cost, West Facing, Corner Premium, Amenities Cost, Floor rise charges, Corpus fund and Maintenance |||
||- Floor Plans - Check if we are able to see all floor plans and all buttons are working dynamically and check if we are ale to see images and Title of floor plan, Size, Type, and Facing. Also check if the share button is working when shared through whatsapp and check we are only sharing Floor plan title, Location, Type, Size and Facing only |||
||- Amenities - Check it is showing only selected amenities |||
||- Location - Check when clicked on share or on the location itself it is navigating to maps |||
||- Downloads - Check if all the items are downloading |||
||- Similar Properties - Check if we are able to navigate when clicked on view details button to the shown property correctly |||
|3|Check if when the like button is clicked it turns to read and then got CRM page and come back to property search page and check the Liked project is displaying on top |||
|4|Check search by typing in projects name and check if it is working |||
|5|Click filter button and check if all filters are working correctly |||
|6|Come back to open lead page and into leads management section and check select Builder and Marked as items are visible after builders accepted your lead registrations |||
|7|Check in select builder dropdown is showing 2 builder's the lead has been registered to |||
|8|Check if when selected the builder the Marked as status showing as same as the builders marked as status, change status in builder marked as status and check |||
|9|Check when builder marked the lead as booked are we getting notification and is it navigating to same leads open lead page and check "Generate Invoice" buttons is visible now |||
|10|change the builder from select builder dropdown and check that only when selected the builder with marked as booked status is showing "Generate Invoice" |||
### Agency Upcoming Tasks
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Check if all tasks are showing and able to edit those tasks and save them |||
### Agency Registered Builders
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Check if it is showing all the builders who registered the lead are showing ||
|2|Check if it showing the registered date |||
|3|Check if you can go to Builder profile by clicking on builder and check everything is fine in the builder profile page |||
### Agency Registered Projects
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Check if the all the Registered Projects are showing with images |||
|2|Check if when clicked on the project it is navigating to project page |||
### Agency Site Visit Logs
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Check if all the site visits are logging in this sections with Project name, Builder name and Time & Date  |||
### Agency Feedback & History
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Check if add feedback is working |||
|2|Check if the feedback is showing in the feedback tab |||
|3|Check if the lead history is logging everything doing in the open lead page |||
### Agency Delete Lead
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Check when clicked on Delete button, a popup opening to confirm action and when clicked in Delete button it should delete lead |||
### Agency Add Task Button
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1| click on add task button and create a call reminder task and add task |||
|2|Check if the call task is created in the Upcoming tasks section and also in Tasks page and the icon for it is call icon |||
|3| click on add task button and create a site visit reminder task and add task |||
|4|Check if the site visit task is created in the Upcoming tasks section and also in Tasks page and the icon for it is apartment icon |||
### Agency Call and Whatsapp Buttons
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click call button and check if it is navigating to dialer app |||
|2|Click call button and check if the add feedback popup is populating |||
|3|Enter Feedback in the add feedback popup and save and check if the feedback is updating in open lead page and CRM page |||
|4|Enter Feedback in the add feedback popup and select another status and save and check if the feedback and status is updating in open lead page and CRM page |||
|5|Enter Feedback in the add feedback popup and select another status and click on add task button and close the task popup to check if the feedback popup is still open and same |||
|6|Open feedback popup from call button and click on add task button and create a call reminder task and add task and check if the feedback popup is still open and same |||
|7|Check if the call task is created in the Tasks page and the icon for it is call icon, Also check if tasks are created in open lead page in Upcoming tasks section |||
|8|Open feedback popup from call button and click on add task button and create a site visit reminder task and add task and check if the feedback popup is still open and same |||
|9|Check if the site visit task is created in the Tasks page and the icon for it is apartment icon, Also check if tasks are created in open lead page in Upcoming tasks section |||
|10|Check if Whatsapp button is navigating to whatsapp app |||
## Agency Property Search Page
### Unpaid user
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Check if agent is not a payed user and if so, check if property listings have Images, Agent Commission and View Details buttons are visible and everything else is blurred and we should have a sticky floating button asking to "Subscribe to unlock" |||
|2|When Clicked on "Subscribe to unlock" button it should navigate to subscription packages page and verify everything is working, like when clicked on Monthly and yearly tabs is it navigating or not and when clicked on upgrade now button is it navigating to payments page. |Not Working|Subscribe to unlock is not navigating |
|3|From search page click on View details button and check if apart from Builder Profile image, Project name, Builder name, likes and dislikes, Images, and Agent Commission everything should be blurred and we should have a sticky floating button asking to "Subscribe to unlock" |||
|4|When Clicked on "Subscribe to unlock" button it should navigate to subscription packages page and verify everything is working, like when clicked on Monthly and yearly tabs is it navigating or not and when clicked on upgrade now button is it navigating to payments page. |||
### Paid users
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|After clicking property search in open lead page, Check if agent is payed user and if so, check if property listings have Images, Project Name, Project Location, Budget range, Property Type, Community, Area Range, Agent commission and View details button |||
|2|From search page click on View details button and check everything is showing and working |||
||- Project Name |||
||- Builder Name |||
||- Like and dislike Buttons |||
||- Images |||
||- Agent Commission |||
||- Able to download View Terms |||
||- Register to Builder Button |||
||- If agent doesn't have rera id are the unable to register to builder with RERA ID restrictions |||
||- When clicked able to register to builder |||
||- After Registration are we getting notification |||
||- After Builder Accepting are we getting Notification |||
||- After Builder Rejecting are we getting notification with reason |||
||- Try registering same lead again to the builder and check that we are getting a message saying we already register this lead |||
||- Try registering other lead and check if that lead is able to registered |||
||- Try registering the same lead to other builder's project and check if it is registering |||
||- Travel Information |||
||- Project Over View |||
||- USP Highlights |||
||- Property Specifications - Property Type, Community, Location, Project Status, Possession Date, Project Area, No of Towers, Total Floors, Total Units, Available Facings and RERA ID |Issue|RERA ID is missing|
||- Property Pricing - Budget Range, Price per SFT, Car Parking Cost, Extra car Parking cost, West Facing, Corner Premium, Amenities Cost, Floor rise charges, Corpus fund and Maintenance |||
||- Floor Plans - Check if we are able to see all floor plans and all buttons are working dynamically and check if we are ale to see images and Title of floor plan, Size, Type, and Facing. Also check if the share button is working when shared through whatsapp and check we are only sharing Floor plan title, Location, Type, Size and Facing only |||
||- Amenities - Check it is showing only selected amenities |||
||- Location - Check when clicked on share or on the location itself it is navigating to maps |||
||- Downloads - Check if all the items are downloading |||
||- Similar Properties - Check if we are able to navigate when clicked on view details button to the shown property correctly |||
|3|Check if when the like button is clicked it turns to read and then got CRM page and come back to property search page and check the Liked project is displaying on top |||
|4|Check search by typing in projects name and check if it is working |||
|5|Click filter button and check if all filters are working correctly |||
## Agency Contacts Page
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|In Contacts Tab - Check if all the registered builders are visible with their status's |||
|2|Check if the registered since date and no of your leads registered to builder are shown correctly |||
|3|Check call feature if working and showing options to select Builder and City Manager |Issue|Call Feature not working while the app is closed|
|4|Expand the builder and check if able to download partnership agreement |Issue|In Downloaded Partnership we need to add builder phone number and email id|
|5|In Registered Leads check if all the leads are showing, if more then 3 leads are registered it should have view all leads button |||
|6|Click on View all leads button and check if it is navigating the leads page |||
|7|Every lead should have, lead name, Leads status, Phone number, Project name, Builder name and Registered date |||
|8|When clicked on the lead it should navigate to open lead page |||
|9|Check of search feature is working |||
|10|Check if Filter button and all its filters are working |||
|11|In Registration History - we should have Registration Activated date, Accepted Date and Last activity date |Issue|Last Activity date is not working|
|12|Activity History - If the Registration Activated date and Accepted date are different we should see some activity logs in here |||
|13|Status Management - We should be able to Activate and Disable Builder from here |||
|14|When Deactivating builder it should mandatorily ask for reason for Disabling builder |Issue|When Disabling it is not asking for reason, It is mandatory to ask and show that reason in Builders notification along with the disabled notification |
|15|In Call Logs Tab - Check if all the call logs are tracked with date and time |||
|16|When expanded the log it should show call type, status and contact type |||
|17|Check if the registered since date and no of your leads registered to builder are shown correctly |||
|18|Check of search feature is working |||
## Agency Tasks Page
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click call button and check if it is navigating to dialer app |||
|2|Click call button and check if the add feedback popup is populating |||
|3|Enter Feedback in the add feedback popup and save and check if the feedback is updating in open lead page and the task is moved to completed tab |||
|4|Create another task from CRM page and come back to tasks page and click call button and enter Feedback in the add feedback popup and select another status and save and check if the feedback and status is updating in open lead page and the task is moved to completed tab |||
|5|Click on Lead name and check if it is navigating to open lead page |||
|6|Create another task from CRM page and come back to tasks page and click call button and enter Feedback in the add feedback popup and select another status and click on add task button and close the task popup to check if the feedback popup is still open and same |||
|7|Open feedback popup from call button and click on add task button and create a call reminder task and add task and check if the feedback popup is still open and same |||
|8|Check if the call task is created in the Tasks page and the icon for it is call icon, Also check if tasks are created in open lead page in Upcoming tasks section |||
|9|Open feedback popup from call button and click on add task button and create a site visit reminder task and add task and check if the feedback popup is still open and same |||
|10|Check if the site visit task is created in the Tasks page and the icon for it is apartment icon, Also check if tasks are created in open lead page in Upcoming tasks section |||
|11|Check if Whatsapp button is navigating to whatsapp app |||
|12|Click on calls tab and check if all the task in there are call tasks |||
|13|Click on Site Visits tab and check if all the task in there are Site Visits tasks |||
|14|Click on completed tasks and check all the tasks in there are completed tasks |||
## Agency Dashboard
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click on this month and check if it is displaying correct stats in 1st numbers section and then check lead analytics section and source analytics sections |Issue|In Source analytics sections it is showing all available sources but it should only display source which are mentioned in leads |
|2|Click on previous month tab and check if it is displaying correct stats in 1st numbers section and then check lead analytics section and source analytics sections |Issue|New Sources added in the configuration section are not displaying in the Lead Status Bar Graph|
|3|Click on this Year tab and check if it is displaying correct stats in 1st numbers section and then check lead analytics section and source analytics sections |||
|4|Click on filter button and add custom dates and check if it is showing correct analytics and Bar Graphs |Issue|Not Showing bar graphs when using custom filters|
|5|Check if filter by user in the filters is working |||
|6|Click on download report icon and check if it is downloading ||| 
## Agency Notification Tab
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Check if all notifications are working and navigating to correct pages |||
|2|Check if Push notifications are working and are displayed on the mobile screen when notifications received |||
|3|On top right corner click on 3 dots button and check if mark as all read button is working |Not Working|It is not marking all notifications as read in one go|
## Agency Profile Settings Page
### Agency Profile Edit
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click Edit button on top right and check if you are able to change Profile Image, Cover image, Experience, About Me, State and City. Also Name and Agent ID should be un-editable |Issue|Unable to scroll the popup|
|2|Check if you are able to modify item in edit page and save them |||
### Agency Upgrade Package
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click Upgrade Package and if it is navigating to Subscription packages page, check if you are able to navigate between monthly and yearly tabs |||
|2|Check when clicked on upgrade now/modify it is showing to add users |||
|3|Check if + and - buttons are working |||
|4|Check if the total amount is changing when adding users |||
|5|Check when clicked on upgrade package it is navigating to payment gateway with Rebax solutions private limited name on top |||
### Agency Billing Summary
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click on Billing summary, Click Upgrade Package and if it is navigating to Subscription packages page, check if you are able to navigate between monthly and yearly tabs |||
|2|In billing summary page, check if you are able to navigate between This Year and Previous Year tabs |||
|3|Click on filter and check if you are able to filter dates and check if working |Missing|Filter and functionality is missing need to add |
|3|Click on an invoice and then click on download invoice and check if the invoice is downloading |||
### Agency Configuration
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click on configurations and go to the page, Click "+" icon in leads status and add a new lead status and click on save and check if it is saving |||
|2|Go to the CRM page, open feedback popup and check if you are able to see and select newly added status in the feedback popup |||
|3|Go to the open lead page, go to lead management section and check if you are able to see and select newly added status in the lead status dropdown |||
|4|Click on configurations and go to the page, Click "+" icon in leads source and add a new lead source and click on save and check if it is saving |||
|6|Go to the open lead page, go to lead management section and check if you are able to see and select newly added source in the lead source dropdown |||
### Agency Business Information
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click on personal info and to the page, only representative Name, Representative phone no, address, State, city and pincode should be editable rest should un-editable, Check if the editable fields are saving |||
### Agency Professional ID's
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click on professional ID's and go to the page, only RERA ID should be editable if it is not already added, If already added it should also be un-editable |Issue|GST number is editable |
|2|If the RERA ID field is empty, type text and check if it is asking to verify the ID |||
|3|Add a Random ID and click on verify RERA button |||
|4|Check after admin rejects the verification and you can add other id and click on verify RERA button |Not Working|Verify RERA button is not appearing after it is rejected 1st time by admin|
|5|After verification check if it is un-editable after approval |||
|6|Check if you are able to save |||
### Agency Banking Information
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click on Banking Information and go to the page, All the input boxes should be editable and check if it is saving |||
### Agency Manage Users
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click on Manage Users and go to the page, check if you are able to switch between Agency Managers, Managers and Sub-users tab |||
|2|Click on "+ Add Agency Manager" in agency manager tab and check. If the remaining user count is "0" it should show a popup saying no agency managers remaining |||
|3|If the count is "0", In the popup click "buy more" and check if it is navigating to subscriptions page. |||
|4|If the users available, Click on "+ Add agency manager" and fill the form and select manager in drop down if available and save |||
|5|Click on edit button on created user and check if you are able to edit all the fields. |||
|6|Click on Delete Button on created user and check if you are able to delete the user |||
|7|Add 2 agency manager users for testing |||
|8|Click on "+ Add Manager" in manager tab and check. If the remaining user count is "0" it should show a popup saying no managers remaining |||
|9|If the count is "0", In the popup click "buy more" and check if it is navigating to subscriptions page. |||
|10|If the users available, Click on "+ Add manager" and fill the form and select sub-user in drop down if available and save |||
|11|Click on edit button on created user and check if you are able to edit all the fields except State and City. |||
|12|Click on Delete Button on created user and check if you are able to delete the user |||
|13|Add 2 manager users for testing |||
|14|Click on "+ Add Sub User" in Sub Users tab and check. If the remaining user count is "0" it should show a popup saying no sub users remaining |||
|15|If the count is "0", In the popup click "buy more" and check if it is navigating to subscriptions page. |||
|16|If the users available, Click on "+ Add sub users" and fill the form and select manager in assign to manager dropdown in drop down and save |||
|17|Click on edit button on created user and check if you are able to edit all the fields except state and city. |||
|18|Click on Delete Button on created user and check if you are able to delete the user |||
|19|Add 2 sub users for testing |||
|20|In Agency Manager tab add 1st manager to 1st agency manager by clicking on the edit button and check if it is adding and saving |||
|21|In Agency Manager tab try adding 1st manager again to 2nd agency manager by clicking on the edit button, ideally it should show an error saying Not available as the user is already assigned to other agency manager. |||
|22|In Agency Manager tab add 2nd manager to 2nd agency manager by clicking on edit button and check if it is adding and saving |||
|23|In Manager tab add 1st sub-user to 1st manager by clicking on the edit button and check if it is adding and saving |||
|24|In Manager tab try adding 1st sub-user again to 2nd manager by clicking on the edit button, ideally it should show an error saying Not available as the user is already assigned to other manager. |||
|25|In Manager tab add 2nd sub-user to 2nd manager by clicking on edit button and check if it is adding and saving |||
|26|In Sub Users tab and check if you are able to change Assigned Manager to user by clicking on edit button |||
### Agency Achievements
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click on Achievements and go to the page, Click on add button and open popup, Entire Tile and add an image and save it and check if it is working |||
|2|Click on 3 dots on the added achievement and check if you are able to edit it |||
|3|Click on 3 dots on the added achievement and check if you are able to delete it |||
### Agency Builder Partnerships
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click on Builder Partnerships and go to the page, check if all the tabs (Active, Pending, Rejected and Disabled) are working properly |||
|2|Check if all the registered builders are visible with their status's |Issue|Its is showing differently, Replicate the Contacts page here without call logs and everything should work correctly |
|3|Check if the registered since date and no of your leads registered to builder are shown correctly |||
|4|Check call feature if working and showing options to select Builder and City Manager |||
|5|Expand the builder and check if able to download partnership agreement |||
|6|In Registered Leads check if all the leads are showing, if more then 3 leads are registered it should have view all leads button |||
|7|Click on View all leads button and check if it is navigating the leads page |||
|8|Every lead should have, lead name, Leads status, Phone number, Project name, Builder name and Registered date |||
|9|When clicked on the lead it should navigate to open lead page |||
|10|Check of search feature is working |||
|11|Check if Filter button and all its filters are working |||
|12|In Registration History - we should have Registration Activated date, Accepted Date and Last activity date |||
|13|Activity History - If the Registration Activated date and Accepted date are different we should see some activity logs in here |||
|14|Status Management - We should be able to Activate and Disable Builder from here |||
|15|When Deactivating builder it should mandatorily ask for reason for Disabling builder |||
### Agency Builder Ratings & Reviews
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click on Ratings & Reviews and go to the page, check if all the reviews are showing |||
|2|Click on filter button and check if the filter are working |||
### Agency Change Password
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click on Change Password and go to the page, check if you are able to change the password |||
|2|Click on forgotten your password and check if the functionality is working |Need To Check|As the email id are all dummy need to check with a real email ID|
### Agency Help & Support
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Check if FAQ's are showing correctly |||
|2|Check if Terms & Conditions, Privacy policy, cookies and Refund Policy pages are displaying correctly |Issue|Cookies Page is not showing|
|3|Click on contact support page and go to the chat, text in chat and check if it is working |||
### Agency Logout
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Check if the logout button is working |||
## Agency Users login
### Agency Sub User Login
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Go to Agency Login and try to login using the agency sub-user user details |||
|2|Go to CRM Page and create 2 new leads and check if you are able to create |||
|3|Add dummy feedback and dummy Call and Site visit tasks |||
|4|Go to tasks and check if the created tasks are visible and correct |||
|5|Go to open lead and test if the property search is working or not. |||
|6|Register Lead to a builder and check if it is working |||
|7|Add site visit in lead management section check if it is working correctly. |||
|8|In Dashboard page, Check if the lead count and graphs are showing correct data. |||
|9|Check lead history if it is working |||
|10|Check if you are able to register lead to a builder. |||
|11|Go to Contacts Page, The Contacts tab and call logs tab should be empty. |Issue|Call logs tab is displaying call logs. It should not |
|12|Go to Profile page, It should only show User Name and role, Email id, Phone no, State, City and Organization (Agency Name). Nothing should be editable |||
|13|Click on logout and check if it is working |||
### Agency Manager Login
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Go to Agency Login and try to login using the manager user details, which the earlier sub user is assigned to |||
|2|Go to CRM Page and create 2 new leads and check if you are able to create |||
|3|Add dummy feedback and dummy Call and Site visit tasks |||
|4|Go to tasks and check if the created tasks are visible and correct |||
|5|Go to open lead and test if the property search is working or not. |||
|6|Register Lead to a builder and check if it is working |||
|7|Add site visit in lead management section check if it is working correctly. |||
|8|Check lead history if it is working |||
|9|Check if the sub-user (only assigned sub-user) leads are shown along with his leads in the CRM Page. |||
|10|Check if the sub-user (only assigned sub-user) tasks are shown along with his tasks in the Tasks page. |||
|11|Check if you are able to register lead to a builder. |||
|12|In Dashboard page, Check if the lead count and graphs are showing correct data. The count and graphs should include leads of the sub-users assigned to him. |||
|13|Go to Contacts Page, The Contacts tab and call logs tab should be empty. |Issue|Call logs tab is displaying call logs. It should not |
|14|Go to Profile page, It should only show User Name and role, Email id, Phone no, State, City and Organization (Agency Name). Nothing should be editable |||
|15|Click on logout and check if it is working |||
### Agency Agency Manager Login
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Go to Agency Login and try to login using the agency manager user details, which the earlier manager is assigned to |||
|2|Go to CRM Page and create 2 new leads and check if you are able to create |||
|3|Add dummy feedback and dummy Call and Site visit tasks |||
|4|Go to tasks and check if the created tasks are visible and correct |||
|5|Go to open lead and test if the property search is working or not. |||
|6|Register Lead to a builder and check if it is working |||
|7|Add site visit in lead management section check if it is working correctly. |||
|8|Check lead history if it is working |||
|9|Check if the manager and sub-user (only assigned managers and sub-user) leads are shown along with his leads in the CRM Page. |||
|10|Check if the manager and sub-user (only assigned managers and sub-user) tasks are shown along with his tasks in the Tasks page. |||
|11|Check if you are able to register lead to a builder. |||
|12|In Dashboard page, Check if the lead count and graphs are showing correct data. The count and graphs should include leads of the managers and sub-users assigned to him. |||
|13|Go to Contacts Page, The Contacts tab and call logs tab should be visible. |Issue|Contacts tab is not displaying builder partnerships. |
|14|Go to Profile page, Click on edit button, Agency manager should be able to see and edit Agency profile image, cover image, Agency experience, Agency about me |||
|15|Agency Manager should be able to access Upgrade package, Billing Summary, Configurations, Manage Users, Builder Partnerships and Builder Ratings and Reviews |Issue|Banking Information should not be accessable to Agency Manager, Unable to access builder Partnerships |
|16|Click on logout and check if it is working |||