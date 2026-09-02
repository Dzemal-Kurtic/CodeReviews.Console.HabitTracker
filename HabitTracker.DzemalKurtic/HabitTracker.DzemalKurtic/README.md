**Project requirements:**



* Logging occurrence of a habit (by quantity)
* Users need to be bale to input the date of the habit
* App should use a real database
* Users should be able to insert, delete, update and view their habit
* All input errors should be handled
* Only ADO.NET should be used



**How the App works?**



When a user starts the app, he sees a menu with options:



0 - close the app

1 - view all records

2 - insert a record

3 - delete a record

4 - update a record



&#x20;

Clicking 1 will show him all the habits that are recorded in the database.



Clicking 2 will open another screen where he will be able to enter a date in dd-mm-yy format. 

Clicking 1 will enter today's date.

After that he will be able to enter the quantity.



Clicking 3 will bring up a new screen where a use will be able to delete the habits that are already recorded. 

You must use Id of the record that exists in the database.



Clicking 4 will bring up a new screen where a user will be able to update an existing record.

You must use Id of the record that exists in the database. 

After choosing an Id user will be able to enter a new date  for the habit. 



**What was hard:**



Working with Sqlite was a new experience for me since I never worked without an ORM. 

Update functionality was the hardest one. 

