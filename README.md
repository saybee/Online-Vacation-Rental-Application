# CMPE273-10
This Repository contains
1)Calculator code
2)Homeaway Application Prototype Application code

Technologies Used:
React JS,Node JS,Express,MySql


LAB 2

1) Homeaway Prototype

Technologies Used:
React JS, Node JS,Express, MongoDB,Redux, Kafka.
JWT, Passport for Authentication.
Mocha and Jmeter for Testing.



Hosted the Application on AWS Linux AMI

Node Backend and Kafka Backend on 1 EC2 instance.
React Frontend on other EC2 instance.











****************************************************************************************************************************************
Introduction:
Make HomeAway application prototype using ReactJS, Node JS, Express,Kafka,Redux,Passport,JWT, MongoDB. In this application we are demonstrating REST web Services and Redux.
Features Demonstrated in this application are:
1)Basic User Functionality:
•	Sign Up new user(First Name, Last Name, Email and Password which is encrypted using Bcrypt maintained using Passportjs and JWT token )
•	Login existing user.
•	Logout.

2) Profile:
•	User Profile is displayed.
•	User should be able to update profile.
•	User’s Profile picture is displayed and updatable.

3) Search and Book Property:
•	Traveler should be able to search property after logging in.
•	Should be able to book the property.
•	Should be able to see previous Trip Details.
•	Owner can see booked property details in owner dashboard.
•	Pagination and filtering and search available in Listing Page and Dashboards.

4) Post Property:
•	Owner should be able to post Properties after logging in.
•	Should be able to see previous booking of his properties.
•	Should be able to update the Property details.
•	Should be able to Add Multiple photos of the property.

5) Messaging:
•	Traveler can ask owner a question.
•	Owner can Reply back to traveler.
•	Messages can be seen in Inbox for both






Homeaway Main Page
 


Login as a Traveler
 




Traveler Login Page
 

Sign up for Homeaway
 





All the Fields are mandatory while signing up
 
Email ID  should be  in correct format while Signing Up
 







Password field is mandatory
 
 






If Sign Up Successful
 

Login Page
 





Email and Passport Fields are mandatory
 






Correct email ID  Format should be Entered
 




Enter Valid Credentials if Wrong Entered 
 


Trying to Register for already Existing Email
 
Login with Correct Credentials
 


















Login As Owner
 

Signup if you don’t have an account
 

 
If SignUp Successful
 
 

 
If Trying to Sign Up with Existing User(Should not allow)
 

If Entering Invalid Credentials
 





Email ID format should be correct
 

Password and Email Field is Mandatory
 
 



















After Successful Login
 
 
 






Owner Can New Properties

 

Click On Add New Property
 

 





Enter All the Details of Property (Locations, Major Details, Photos, Pricing, Availability, Rental Rates)

 

















Enter Details and Save

 
 

 

Describe Property and Click on Next

 
 
 






Add Multiple Photos and Click on Next
 
 







Enter Availability for your Property and Click on Next

 

Enter Rental Rates and Click on Save

 



Property Saved 
Property available for Update on home page
 

















Login as a Traveler
 
 







Sign up as Traveler for Homeaway
 

All the Fields are mandatory
 







Email ID should be correct format
 
















All the Signup fields are mandatory

 
 






If Sign Up Successful
 




Login Page
 


Email and Password Fields are mandatory
 

Correct email ID should be Entered
 





Enter Valid Credentials if Wrong Entered 
 


Trying to Register for already Existing Email
 




Login with Correct Credentials
 


















Traveler can Update his Profile
 
 Change Profile Photo
 

 

 

 




Traveler Can Search For a Property All Fields are Mandatory
 




Arrival and Departure Dates must be in Future
Traveler should not be able to Book Property for Past Dates
 



Departure Date must be greater than Arrival Date
 


Search is Case Insensitive(Search by City)
 



Click on Search 
 

If no results are found for those particular dates or Location
 






Traveler will get the below message.
He can go back and search with new criteria.

 


Traveler Can Search with correct dates (All the properties which are booked for the those dates will not show in search result .One property should be booked only once)
 


Traveler will be Redirected to Property Results Display page
 
 
 


 






Traveler Can Filter based on Price and Bedroom both and Click on Apply Filter
He can Reset the Filter and check other properties
 
 
 
 
 



Click on Apply Filter
 
 








Traveler Clicks on the Property he likes
 
 







Traveler can Send Message to Owner
 
 






Traveler can Search for his sent messages in INBOX
 



Traveler’s Inbox
 




Click on the message he wants to View
 
 











Owner can view the Message under Inbox and Reply to Traveler
 

 
 
 






Traveler Can Click on the Book Button and the property will be booked for the Traveler
 
 








Traveler can view his Trips details (Pagination+ Filter )
 
 

 

Filter Properties based on Property Headline(Case Insensitive)
 






Filter based on Dates less than or equal to Entered Date
 

Pagination(8 Results) 5+3 
 





Property Booking Details for Owner
 

Filter Based on property headline( Case Insensitive )
 

Filter Based on Date (Less than or equal to entered date) 



















MOCHA TEST Cases:
√ Should check if Chat Message are being returned 
  √ Should check if Booked Properties is being returned
  √ Should check Requested Property is returned 
  √ Should check for Profile if it is returned 
  √ Should check for property listing if it is returned 
 
