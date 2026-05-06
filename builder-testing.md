# Builder Testing on Rebax App
## Builder Register
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|App should take Pan Card from Builder and Verify |||
|2|App should take email id from Builder and Verify |||
|3|App should take phone no from Builder and Verify |||
|4|App should take Representative name from Builder |||
|5|App should take Representative phone number |||
|6|App should take GST number from Builder |||
|7|App should take TAN number from Builder |||
## Builder Forgot Password
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Verify if the given email id is getting an OTP |||
|2|Verify if the OTP is Validating |||
|3|Verify if the New Password is saving |||
|4|Verify if the New password is working to login |||
## Builder Login
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|As soon as you login for 1st time app will navigate you to packages page. |||
|2|Check if you are able to add users and if the amount is changing as you add users to the package. |||
|3|Click on Upgrade Package/Buy and check if it is navigating to payment gateway and check if name on top is Rebax Solutions Private Limited. |||
|4|After adding packge from admin pannel, Logout and login and check if you are able navigate through the app normaly |||
## Builder CRM Page
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
|21|Click on lead and expand the lead, Check if you are able to see source and Interested Project. If the lead is registered by Agent/Agency you should see registered by with Agent/Agency Name |Issue|When a lead is registered by staff members of Agency, Registered by is not showing. |
|22|Check search box by typing lead names and it is showing appropriate results |||
|23|Click filter button and check if all filters are working correctly |||
|24|Click on download button after changing the filters and check if you are able to download only filtered leads |Issues|Need to edit the fields in the downloaded excel file|
|25|Click on download sample excel link and download it and add all the details in fields marked with '*' and upload it and check if its uploading and adding leads in CRM correctly  |Issue|Need to change '*' fields and make fields changes|
||**Test Cases after accepting Agent Registered leads**||| 
|26|Agent/Agency Tab - Search inputbox, check if you are able to search leads and lead requests using Lead Name and Agent/Agency Name. |||
|27|Leads Tab in Agent/Agency Tab - Check if you are able to see Only Agent/Agency leads in this tab. |||
|28|Requests Tab in Agent/Agency Tab - Check if you are able to see pending Agent/Agency lead registration requests. |||
|29|Invoices Tab - check if all the invoices received are showing here |||
|30|Check if all the invoices are expandable and shows Lead name, lead phone number, Invoice Date, Sent by Name, Project name, Invoice Stage and commission amount |||
|31|Check if the download button fo invoice is working |Issue|Invoice is different from what Agent/Agency is generating. Invoice should be same for Both Agent/Agency and Builder. Use Agent generated invoice template for all modules. |
## Builder Editing Leads in Open Lead Page
### Builder Customer Details
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Check if you can edit full name and save and check it is saving |||
|2|Check if you can edit Email ID and save and check it is saving |||
|3|Check if you can edit Phone number and save and check it is saving |||
|4|Check if you can add and edit alternative phone number and save and check it is saving |||
|5|Check if you can add address and save and check it is saving |||
||**Test Cases after accepting Agent Registered leads**|||
|6|All these fields should be uneditable and greyed out |||
|7|Check if you are able to see TAT Time with remaining days below the section. |||
### Builder Property Type
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
### Builder Lead Management
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Check if lead status dropdown is working |||
|2|Check if all 6 Default status's (New, Active, Prospect, Site Visit, Booked and Dead) are selectable |||
|3|Check when site visit status is selected, if site visit popup is populating |||
|4|Fill the form and check if Select Date and Time are working |||
|5|Check if it is showing error when you try to add visit without selecting any project |||
|6|Check if select project search box is populating projects when entered 2 or more letters |||
|7|Check if the Search Project is only showing Builder projects. If it is showing other projects report issue. |||
|8|Check if it is saving when selected a project and added visit |||
|9|Check if the site visit log is updated in site visit logs |||
|10|Check if the Site visit is showing in Dashboard in Unique Site Visits [make sure you refresh (refresh by changing This month to previous month and come back to this month tab) dashboard while checking] |||
|11|Check if Lead source dropdown is working. If it is Agent Registered lead it should directly show the source as Agent |Issue|When Agent registered lead the source is editable. It should be locked/uneditable/grayed out until the TAT is completed |
|12|Check if the Lead owner dropdown is working |||
|13|Check in Interested projects section if "+ Add Projects" is working, When Clicked on it all builder projects must be displayed here. |||
|14|Check if we can select multiple project from the list and being added when clicked on done |||
|15|check if everything saving by clicking on save changes button and go back to CRM and come back to open lead page to verify |||
||**Test Cases for Agent Registered Leads**|||
|16|Come back to open lead page and into leads management section and check if you can see Marked as dropdown. By default Active is selected. |||
|17|Check when you change lead status dropdown to booked you are able to see a popup asking "Update Marked as Status" with Yes or No Options. check if when clicked on yes it is changing, and when when clicked on no it should not change. |Feature Change|Instead of asking, Directly change the marked as when status is changed to booked. If Builder is changing marked as status manually, populate caution box, "Are you sure you want to change the marked as status from "Whatever it is earlier" to "Whatever option he chooses". |
|18|Check the "Registered by:" section is should not be editable. |||
|19|After "Registered by:" section you should see "Created:" & "Last Modified:" ||| 
### Builder Upcoming Tasks
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Check if all tasks are showing and able to edit those tasks and save them |||
### Builder Registered Projects
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Check if the Agent registered Leads are showing Registered Projects are showing with images |||
|2|Check if when clicked on the project it is navigating to project page |||
### Builder Site Visit Logs (Shows only after adding Site Visit)
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Check if all the site visits are logging in this sections with Project name, Builder name and Time & Date  |||
### Builder Feedback & History
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Check if add feedback is working |||
|2|Check if the feedback is showing in the feedback tab |||
|3|Check if the lead history is logging everything doing in the open lead page |Issue|When Site visit is added, it shows as Site Visit Scheduled, Instead change it to Site Visit Updated. Also When site visit is added it is creating 2 History items 1 with project name and other without project name. Remove without project name item. |
### Builder Delete Lead
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Check when clicked on Delete button, a popup opening to confirm action and when clicked in Delete button it should delete lead |Issue|Agent registered leads shouldn't be able to be deleted from builder module unless the TAT time is completed. Also when builder deletes Agent registered lead after TAT is completed the lead is being deleted in Agent module also, which it shouldn't. |
### Builder Add Task Button
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1| click on add task button and create a call reminder task and add task |||
|2|Check if the call task is created in the Upcoming tasks section and also in Tasks page and the icon for it is call icon |||
|3| click on add task button and create a site visit reminder task and add task |||
|4|Check if the site visit task is created in the Upcoming tasks section and also in Tasks page and the icon for it is apartment icon |||
### Builder Call and Whatsapp Buttons
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
## Builder Push Notifications Page
### Builder Send Notification Tab
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Check if you able to see available credits and Add credits button |||
|2|Click on Add credits button and check if you are getting popup to add credits and "Buy now" button |||
|3|Click on Buy now button and check if it is navigating to payment gateway with Rebax Solution Private Limited name on top. |||
|4|Come back to the send notifications tab, Check if select state dropdown working and select telangana |||
|5|Check if select city dropdown is working and you are able to select multiple cities. Select Hyderabad |||
|6|Check if select project dropdown is working and showing Builder Profile and all existing Builder projects, re-check after you add a project to the builder. Select any option |||
|7|Add Notification Title |||
|8|Add Notification Body |||
|9|In Send to section, check when selecting between All agents, Registered Agents and Non-Registered Agents the total is changing. Select any option|||
|10|Upload Horizontal image provided and check if it is uploading or not |||
|11|Upload Vertical image provided and check if it is uploading or not |||
|12|Click on Send Notification, check if popup is appearing and showing how many credits will be used and asks to confirm send. |||
|13|After confirming another popup should appear saying that the notification was sent to "x" no of agents and "x" no of credits consumed. |Not Working|Notification is not being sent to any users. It should only send notifications to user who are active and subscribed members. |
### Builder Notification Reports Tab
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Check if you are able to navigate between This month, Previous month and This Year tabs. |||
|2|Check if you are able to click on filter icon and filter custom dates to find reports |Missing|Filter and functionality missing. |
|3|Click on this month, and check if the No of pushes, Credits Used, Total Delivered, Total Opened, Total Clicked and Total Registrations are visible or not |||
|4|In Reports Breakdown, Check if the resently sent report is visible or not, Expand the report and see if it is showing Pushes Sent, Credits Used, Delivered, Opened, Clicked and Registrations numbers |||
## Builder Contacts Page
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|In Contacts Tab - Check if all the registered agents/Agencies are visible with their status's |||
|2|Check if the registered since date and no of your leads registered by the Agent/Agency are shown correctly |||
|3|Check call feature if working and showing options to select Builder and City Manager |Issue|Call Feature not working while the app is closed|
|4|Expand the Agent/Agency and check if able to download partnership agreement |Issue|In Downloaded Partnership we need to add builder phone number and email id|
|5|In Registered Leads check if all the leads are showing, if more then 3 leads are registered it should have view all leads button |||
|6|Click on View all leads button and check if it is navigating the leads page |||
|7|Every lead should have, lead name, Leads status, Phone number, Project name, Builder name and Registered date |||
|8|When clicked on the lead it should navigate to open lead page |||
|9|Check if search feature is working |||
|10|Check if Filter button and all its filters are working |||
|11|In Registration History - we should have Registered date, Accepted Date and Last activity date |||
|12|Activity History - See if there are Activity Logs |||
|13|Status Management - We should be able to Activate and Disable Agent/Agency from here |||
|14|When Deactivating Agent/Agency it should mandatorily ask for reason for Disabling Agent/Agency |Issue|When Disabling it is not asking for reason, It is mandatory to ask and show that reason in Builders notification along with the disabled notification |
|15|Check if search feature is working |||
|16|In Call Logs Tab - Check if all the call logs are tracked with date and time |||
|17|When expanded the log it should show call type, status and contact type |||
|18|Check if search feature is working |||
## Builder Tasks Page
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
## Builder Dashboard
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click on this month and check if it is displaying correct stats in 1st numbers section and then check lead analytics section and source analytics sections |Issue|In Source analytics sections it is showing all available sources but it should only display source which are mentioned in leads |
|2|Click on previous month tab and check if it is displaying correct stats in 1st numbers section and then check lead analytics section and source analytics sections |Issue|New Sources added in the configuration section are not displaying in the Lead Status Bar Graph|
|3|Click on this Year tab and check if it is displaying correct stats in 1st numbers section and then check lead analytics section and source analytics sections |||
|4|Click on filter button and add custom dates and check if it is showing correct analytics and Bar Graphs |Issue|Not Showing bar graphs when using custom filters|
|5|Check if filter by user in the filters is working |||
|6|Click on download report icon and check if it is downloading ||| 
## Builder Notification Tab
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Check if all notifications are working and navigating to correct pages |||
|2|On top right corner click on 3 dots button and check if mark as all read button is working |Issue|change color to white |
|3|Click on new agent registration request notification and check if you are able accept or reject with a reason |||
|4|Click on new lead registration notification and check if it is opening a popup with semi-masked phone number and email id. check if you are able to accept or reject with a reason. Also check when clicked on view profile it is navigating to agent/agency profile. |||
|5|Check if you are unable to accept lead without checking I agree check box. check if the terms & Conditions link is navigating to terms and conditions page. |||
|6|When you accept the new lead check if it opens another popup which shows lead information and asks to assign the lead to a staff member |||
|7|Check if you are getting notifications for subscription payment reminder from 10 days remaining everyday until the subscription is expired. |Not working|We are not getting notifications for this. |
## Builder Profile Settings Page
### Builder Profile Edit
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click Edit button on top right and check if you are able to change Profile Image, Cover image, Experience, About Me, State and City. Also Name and Agent ID should be un-editable |Issue|Unable to scroll the popup|
|2|Check if you are able to modify item in edit page and save them |||
### Builder Upgrade Package
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click Upgrade Package and if it is navigating to Subscription packages page, check if you are able to navigate between monthly and yearly tabs |||
|2|Check when clicked on upgrade now/modify it is showing to add users |||
|3|Check if + and - buttons are working |||
|4|Check if the total amount is changing when adding users |||
|5|Check when clicked on upgrade package it is navigating to payment gateway with Rebax solutions private limited name on top |||
### Builder Billing Summary
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click on Billing summary, Click Upgrade Package and if it is navigating to Subscription packages page, check if you are able to navigate between monthly and yearly tabs |||
|2|In billing summary page, check if you are able to navigate between This Year and Previous Year tabs |||
|3|Click on filter and check if you are able to filter dates and check if working |Missing|Filter and functionality is missing need to add |
|3|Click on an invoice and then click on download invoice and check if the invoice is downloading |||
### Builder Configuration
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click on configurations and go to the page, Click "+" icon in leads status and add a new lead status and click on save and check if it is saving |||
|2|Go to the CRM page, open feedback popup and check if you are able to see and select newly added status in the feedback popup |||
|3|Go to the open lead page, go to lead management section and check if you are able to see and select newly added status in the lead status dropdown |||
|4|Click on configurations and go to the page, Click "+" icon in leads source and add a new lead source and click on save and check if it is saving |||
|6|Go to the open lead page, go to lead management section and check if you are able to see and select newly added source in the lead source dropdown |||
### Builder Manage Projects
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Open Manage Projects page, Click on "+ Add Project" button |||
||- Check if you are able to Add Project Name |||
||- Check if you are able to Add Agent commission and Payout after. |||
||- Check if you are able to upload payment terms pdf file |||
||- Check if you are able to add project overview and the max input is 900 words. |||
||- Check if you are able to add USP Title and Usp Content and max title limit is 60 words and content limit is 120 words |||
||- Check after adding first USP, you are able to see "+ Add more" button and by clicking it you are able to add additional USP's and Max USP's you can add are 6 USP's |Issue|Add Max title limit to be 60 words. |
||- Check if you are able to select project type |||
||- Check when you select Apartments in project type the below should be changed: |||
||* In Select Project community the dropdow should only consist, 1. Gated Community, 2. Semi-Gated Community, 3. High-Rise Apartments, 4. Standalone Apartment |Fixes|Change High-Rise Towers to High-Rise Appartments and Standalone Building to Standalone Apaertment |
||* Price per SFT/SQYD should be SFT |||
||* Floor Plan Section there should be no "No of Floors" dropdown |||
||- Check when you select Villas in project type the below should be changed: |||
||* In Select Project community the dropdow should only consist, 1. Gated Community, 2. Semi-Gated Community, 3. Villa Township, 4. Standalone |||
||* In Property Specifications section No of floor and No of Towers should be hidden |||
||* In Floor Plans section No of Floors should appear |||
||- Check when you select Commercial in project type the below should be changed: |||
||* In Select Project community the dropdow should only consist, 1. IT Park, 2. Business Park, 3. Mall?Retail Complex, 4. Standalone Building |||
||* In Property Specifications section No of Towers should be hidden |||
||* In Floor Plans section Type should be hiiden and No of Floors should appear |||
||- Check when you select plots in project type the below should be changed: |||
||* In Select Project community the dropdow should only consist, 1. Gated Layout, 2. HMDA Layout, 3. DTCP Layout, 4. Open Layout |||
||* In Property Specifications section price per SFT/SQYD should SQYD no of Floors and No of Towers should be hidden |||
||* In Floor Plans section Type and No of floors should be hidden and Size should be SQYD |||
||- Check if you are able to change Project status |||
||- Check if you are able to add posesssion date |||
||- Check if are able to add total Project area |Issue|Change name to Total Project Area |||
||- Check if you are able to price per SFT/SQYD |||
||- Check if you are able to add No of Floors |||
||- Check if you are able to add No of Units |||
||- Check if you are able to add No of Towers |||
||- Check if you are able to add RERA ID |Issue|Make in Optional, Also check for duplicate RERA ID's and show an error when someone entires RERAID of a project which already exists in our Database. |||
||- In Property Pricing - Check if you are able to add From and To budgets and it is showing in words below. |||
||- Check if you are able to add Amenities Cost |||
||- Check if you are able to add Car Parking Cost |||
||- Check if you are able to add extra car parking cost |||
||- Check if you are able to select facing Direction multi select |||
||- Check if you are able to add facing charges after selecting facing direction |||
||- Check if you are able to add Corner charges |||
||- Check if you are able to add Floor rise charges |||
||- Check if you are able to add Floor rise from floor |||
||- Check if you are able to add corpus fund amount |||
||- Check if you are able to add maintenanace per year |||
||- Check if you are able to upload floor plan |||
||- Check if you are able to add Title |||
||- Check if you are able to add Size |||
||- Check if you are able to add Type |||
||- Check if you are able to add No of Floors |||
||- Check if you are able to add Facing |||
||- Check if you are able to add floor plan |Issue|after adding floor details and selecting facing the "Add Floor Plan" button is becoming invisible |
||- Try adding another floor plan and check if you are able to |||
||- Check if you are able to navigate all Amenities tabs and able to add amenities and note down in a book what all you have selected to cross check in future. |||
||- Check if you are able to pick location by searching in search bar, and check if you are able to add a pin point by long pressing in the map, Click on done button and check if it is saving |||
||- Check if the Area name is auto populated or not and it should be editable |||
||- Check if you are able to add project thumbnail |||
||- Check if you are able to add multiple images in gallery |Issue|Make it multi select in gallery |||
||- Check if you are able to upload Payment Plan. |||
||- Check if you are able to click on upload button, And it say that project is sent to verification |||
||- Check if the tabs in the manage projects page, All, Active, Pending, Rejected and Deactive tab as working |||
||- Once project is approved check if you are able to edit project and the RERA ID is uneditable if RERA ID is given when creating a project |Issue| Make the RERA ID uneditable once it is verified by admin team. |
||- Check if you are able to deativate the project by clicking on the 3 dots on the project tile. |||
||- Check if the search is working |||
### Builder Builder Information
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click on Builder info and go to the page, only representative Name, Representative phone no, address, State, city and pincode should be editable rest should un-editable, Check if the editable fields are saving |||
### Builder Professional ID's
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click on professional ID's and go to the page, PAN should not be editable, If GST and TAN are given when registering these are also should be uneditable, If not they can add GST and TAN and save and once saved they shouldn't be able to edit it. |||
### Builder Manage Users
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click on Manage Users and go to the page, check if you are able to switch between City Managers, Managers and Sub-users tab |||
|2|Click on "+ Add City Manager" in City manager tab and check. If the remaining user count is "0" it should show a popup saying no City managers remaining |||
|3|If the count is "0", In the popup click "buy more" and check if it is navigating to subscriptions page. |||
|4|If the users available, Click on "+ Add City manager" and fill the form and select manager in drop down if available and save |||
|5|Click on edit button on created user and check if you are able to edit all the fields. |||
|6|Click on Delete Button on created user and check if you are able to delete the user |||
|7|Add 2 City manager users for testing |||
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
|20|In City Manager tab add 1st manager to 1st City manager by clicking on the edit button and check if it is adding and saving |||
|21|In City Manager tab try adding 1st manager again to 2nd City manager by clicking on the edit button, ideally it should show an error saying Not available as the user is already assigned to other City manager. |||
|22|In City Manager tab add 2nd manager to 2nd City manager by clicking on edit button and check if it is adding and saving |||
|23|In Manager tab add 1st sub-user to 1st manager by clicking on the edit button and check if it is adding and saving |||
|24|In Manager tab try adding 1st sub-user again to 2nd manager by clicking on the edit button, ideally it should show an error saying Not available as the user is already assigned to other manager. |||
|25|In Manager tab add 2nd sub-user to 2nd manager by clicking on edit button and check if it is adding and saving |||
|26|In Sub Users tab and check if you are able to change Assigned Manager to user by clicking on edit button |||
### Builder Achievements
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click on Achievements and go to the page, Click on add button and open popup, Entire Tile and add an image and save it and check if it is working |||
|2|Click on 3 dots on the added achievement and check if you are able to edit it |||
|3|Click on 3 dots on the added achievement and check if you are able to delete it |||
### Builder Agents Partnerships (Need to change name)
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click on Builder Partnerships and go to the page, check if all the tabs (Active, Pending, Rejected and Disabled) are working properly |||
|2|Check if all the registered Agents/Agencies are visible with their status's |Issue|Its is showing differently, Replicate the Contacts page here without call logs and everything should work correctly |
|3|Check if the registered since date and no of your leads registered to builder are shown correctly |||
|4|Check call feature if working and showing options to select Builder and City Manager |||
|5|Expand the Agent/Agency and check if able to download partnership agreement |||
|6|In Registered Leads check if all the leads are showing, if more then 3 leads are registered it should have view all leads button |||
|7|Click on View all leads button and check if it is navigating the leads page |||
|8|Every lead should have, lead name, Leads status, Phone number, Project name, Lead email ID and Registered date |||
|9|When clicked on the lead it should navigate to open lead page |||
|10|Check of search feature is working |||
|11|Check if Filter button and all its filters are working |||
|12|In Registration History - we should have Registration Activated date, Accepted Date and Last activity date |||
|13|Activity History - If the Registration Activated date and Accepted date are different we should see some activity logs in here |||
|14|Status Management - We should be able to Activate and Disable Agent/Agency from here |||
|15|When Deactivating Agent/Agency it should mandatorily ask for reason for Disabling Agent/Agency |||
### Builder Agents Ratings & Reviews
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click on Ratings & Reviews and go to the page, check if all the reviews are showing |||
|2|Click on thumbs down button and check if it is only showing thumbs down reviews and click on thumbs up button and check if it is only showing thumbs up reviews. |||
### Builder Change Password
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Click on Change Password and go to the page, check if you are able to change the password |||
|2|Click on forgotten your password and check if the functionality is working |Need To Check|As the email id are all dummy need to check with a real email ID|
### Builder Registration Settings
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Check if Auto accept agents is working |Need to test||
|2|Check if Auto Reject agents is working |Neet to test||
|3|Check if Only Accept RERA Registed Agents is working |||
|4|Check if Partnership Terms & Conditions is working and showing by downloading the partnership agreement from contacts page |||
### Builder Help & Support
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Check if FAQ's are showing correctly |||
|2|Check if Terms & Conditions, Privacy policy, cookies and Refund Policy pages are displaying correctly |Issue|Cookies Page is not showing|
|3|Click on contact support page and go to the chat, text in chat and check if it is working |||
### Builder Logout
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Check if the logout button is working |||
## Builder Users login
### Builder Sub User Login
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Go to Builder Login and try to login using the Builder sub-user user details |||
|2|Go to CRM Page and create 2 new leads and check if you are able to create |||
|3|Add dummy feedback and dummy Call and Site visit tasks |||
|4|Go to tasks and check if the created tasks are visible and correct |||
|5|Add site visit in lead management section check if it is working correctly. |||
|6|In Dashboard page, Check if the lead count and graphs are showing correct data. |||
|7|Check lead history if it is working |||
|8|Go to Contacts Page, The Contacts tab and call logs tab should be empty. |Issue|Call logs tab is displaying call logs. It should not |
|9|Go to Profile page, It should only show User Name and role, Email id, Phone no, State, City and Organization (Builder Name). Nothing should be editable |||
|10|Click on logout and check if it is working |||
### Builder Manager Login
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Go to Builder Login and try to login using the manager user details, which the earlier sub user is assigned to |||
|2|Go to CRM Page and create 2 new leads and check if you are able to create |||
|3|Add dummy feedback and dummy Call and Site visit tasks |||
|4|Go to tasks and check if the created tasks are visible and correct |||
|7|Add site visit in lead management section check if it is working correctly. |||
|8|Check lead history if it is working |||
|9|Check if the sub-user (only assigned sub-user) leads are shown along with his leads in the CRM Page. |||
|10|Check if the sub-user (only assigned sub-user) tasks are shown along with his tasks in the Tasks page. |||
|12|In Dashboard page, Check if the lead count and graphs are showing correct data. The count and graphs should include leads of the sub-users assigned to him. |||
|13|Go to Contacts Page, The Contacts tab and call logs tab should be empty. |Issue|Call logs tab is displaying call logs. It should not |
|14|Go to Profile page, It should only show User Name and role, Email id, Phone no, State, City and Organization (Builder Name). Nothing should be editable |||
|15|Click on logout and check if it is working |||
### Builder City Manager Login
| S.No | TestCase | Status | Notes |
|:--:|:--|:--:|:--|
|1|Go to Builder Login and try to login using the city manager user details, which the earlier manager is assigned to |||
|2|Go to CRM Page and create 2 new leads and check if you are able to create |||
|3|Add dummy feedback and dummy Call and Site visit tasks |||
|4|Go to tasks and check if the created tasks are visible and correct |||
|5|Add site visit in lead management section check if it is working correctly. |||
|6|Check lead history if it is working |||
|7|Check if the manager and sub-user (only assigned managers and sub-user) leads are shown along with his leads in the CRM Page. |||
|8|Check if the manager and sub-user (only assigned managers and sub-user) tasks are shown along with his tasks in the Tasks page. |||
|9|In Dashboard page, Check if the lead count and graphs are showing correct data. The count and graphs should include leads of the managers and sub-users assigned to him. |||
|10|Go to Push Notifications Page and check if you are able to send push noifications |Issue|Push Notifications not working|
|11|Go to Contacts Page, The Contacts tab and call logs tab should be visible. |Issue|Contacts tab is not displaying Agent/Agency partnerships. |
|14|Go to Profile page, Click on edit button, city manager should be able to see and edit Builder profile image, cover image, Builder experience, Builder about me |||
|15|City Manager should be able to access Upgrade package, Available Credits, Billing Summary, Configurations, Manage Project, Manage Users, Builder Partnerships and Builder Ratings and Reviews |Issue|Unable to access builder Partnerships, He should only be able to manage projects located in his city. |
|16|Click on logout and check if it is working |||