# Inventory-Management-System
Introduction:
An inventory management program I wrote, a lot more work have to be done to build onto it. 

Description:
- There are two kinds of staff access level, staff and manager.
- The staff suggests a purchase order which requires approval by a manager.
- The staff then purchase from the supplier through other sources and can mark as done on the dashboard.
- Both staff and manager are allowed to check purchase orders, sales orders, goods receive, supplier, and SKU information.
- Upload date button is for uploading special dates that have discount. It is used for sales prediction (unfinished function).

System requirement:
- This system uses sqlite3, please have sqlite3 installed
- Please have Python3 interpreter installed

Author's note:
- I am currently working on implementing neural network using PyTorch to monitor stock level, but it is not working well.
- alldata.db is all test data. They are not actual data.
- 太陽油集團（國際）有限公司 is a fake company name. If there exists such company, please note that this program has nothing to do with this company.
- Please use accounts aturing(staff) and anobel(manager) for testing purposes.
- An OTP is required for the system, you can change the staff email in alldata.db Staff table to your own email to receive the otp and log into the system.
- Please run this line on sqlite3 to update the staff table to your email:
- UPDATE Staff SET email = 'your email';


