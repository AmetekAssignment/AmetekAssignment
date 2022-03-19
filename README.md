Users App Assignment

Prerequisite :
Refer to https://gorest.co.in/ for API requests & response format
Bearer Token: c6c0d7598d4d00392844a8a8be680834995c26482becec12474cc9ac2e2234af


Tasks to perform 
Task 1 :
 Launch the webapp with /home (http://localhost:4200/home) route as default home page
Home page should contain “Navigate to users” button
Refer below screenshot

 

Task 2 : 
On click of “Navigate to users” button-> url should be routed to users route http://localhost:4200/users
In users page display the list of users  
Consume api https://gorest.co.in/public/v2/users and display the users info in table as shown below.

Get users : curl -i -H "Accept:application/json" -H "Content-Type:application/json" -XGET "https://gorest.co.in/public/v2/users"

Headers : 
•	Id
•	Name
•	Email
•	Gender
•	Status
•	Delete button in last column

 


Task 3 :
On click of “Delete” button in last column, record should be deleted and refresh the UI with the updated users
Delete user
curl -i -H "Accept:application/json" -H "Content-Type:application/json" -H "Authorization: Bearer ACCESS-TOKEN" -XDELETE "https://gorest.co.in/public/v2/users/123"

 
 

