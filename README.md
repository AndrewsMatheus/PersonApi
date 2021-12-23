# PersonApi

Basic API for people management with the add, remove and query operations.

## Running the API

For Execute the API run the follow command in the PersonAPI folder in the bash

>$ mvn spring-boot:run

## People attributes 

The API stores the following attributes:

- ID;
- First Name;
- Last Name;
- CPF;
- Birthdate;
- Contact phone (Can be more than one!).

## Manipulating database 

For use the REST API is necessary pass the information through the following HTML methods:
 
 ### Create a new people 
 
 > [POST HTTP METHOD] [url/api/v1/people] [Elements in JSON]
 
 ### Found a certain people for ID
 
  > [GET HTTP METHOD] [url/api/v1/people/ID]
 
 ### Show a list with all people
 
 > [GET HTTP METHOD] [url/api/v1/people]
 
 ### Update an existing people with ID
 
  > [PUT HTTP METHOD] [url/api/v1/people/ID] [Elements in JSON]
  
  ### Delete an existing people with ID
  
   > [DELETE HTTP METHOD] [url/api/v1/people/peopleID]
  
