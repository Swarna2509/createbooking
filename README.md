Booking-REST-API-Testing
How to run this project
Clone this project
Open with Postman / Command Shell

##Run Command:

newman run Createbooking.postman_collection.json -e Createbooking.postman_environment.json -r cli,html

Run Command for Report:

newman run Createbooking.postman_collection.json -e Createbooking.postman_environment.json -r cli,htmlextra

Technology used

Postman
Newman
Prerequisite
Jdk
Node Js
Newman
Html Report Library

Newman and Report Installation Process

Newman Install Command:

npm install -g newman

Newman Html Report Install Command:

npm install -g newman-reporter-htmlextra

API Documentation
https://documenter.getpostman.com/view/27187339/2s93eVWZDJ

Test case list

Create Booking
In this section we created dataset using the dynamic random variables.

Get Booking
In this section we tested wether we can get the details of the particular searched id which we got in the create booking section's response and also validated the following field values:

First Name

Last Name

Total Price

Deposit Paid

Check In

Check Out

Additional Needs

Create Token
In this section we generated a token that'll be needed to update the booking, partially update the booking and delete the booking.

Update Booking
In this section we updated the following field values:

First Name

Last Name

Total Price

Check In

Check Out

Additional Needs

Get Updated Booking
In this section we tested wether the updated field values successfully added ot not and validated the following field values:

First Name

Last Name

Total Price

Check In

Check Out

Additional Needs

Newman Report Summary

[Screenshot (280)](https://github.com/Swarna2509/createbooking/assets/72212832/16a16f4a-5f9a-453d-8e20-8036958c56a9)

![Screenshot (281)](https://github.com/Swarna2509/createbooking/assets/72212832/1761df14-9424-41ab-bfe6-4530ea93ac81)
![Screenshot (279)](https://github.com/Swarna2509/createbooking/assets/72212832/0431c04b-ca0f-4fe0-a250-b2ebda55eaf4)

