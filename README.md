- 👋 Hi, I’m @akhila4-dev
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
akhila4-dev/akhila4-dev is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
 USER STORY - 2
 "1-Users should have option to select their role option - user/Admin
2-Admin should select the Admin option. 
2-Admin's User id and password should be pre-loaded in the database, which can be used to log in.
===========================================================================================================
create database testdb;
use testdb;
CREATE TABLE ADMIN(USER_ID VARCHAR(45) NOT NULL, PASSWORD VARCHAR(15) NOT NULL)
engine=InnoDB default charset=utf8 collate=utf8_unicode_ci;
insert into ADMIN values("admin@gmail.com","Abc@1234");


USER STORY -4


"1-When the Vendor/User clicks on the registration link, it should re-direct to registration form.
2-Vendor/User needs to fill some of the basic attributes/fields.
The appropriate fields should be displayed based on the role selected.
Below are some of the fields:
 First Name, Last Name, DOB, Gender, Contact Number, Vendor Id/User Id, Password, Address, Map location (for vendor only)
Clicking ‘Submit’ should validate the datatype constraints for each field

Name should be in range 4-50
DOB should be entered and the age should not be less than 18. DOB is not required for Vendor.
Contact number should be of 10 digits
Password should be of minimum 6 letters with special characters included.
Note - Trainees can add/neglect fields that will be appropriate and validations should be handled for all fields
3-Vendor failing to provide information on the mandatory fields be provided with an alert message – ‘Please update the highlighted mandatory field(s).’ Also, highlight the missed out field in red
4-Post-successful field level validation, save the information in the database
5-Upon saving the information in the database, display the message ‘Your details are submitted successfully’.
7-Admin should be able to view the New Vendor registration
8-Admin should approve / reject theVendor Request.
9-If rejected, the Manager should not be allowed to login with the registered credentials
10-Vendor should be notified upon approval/rejection while trying to enter the application.
"
============================================================================================================






