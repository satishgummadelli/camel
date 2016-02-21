
#Player Sign in

###Flow

 - ####[x] First Time Sign in
 
 	- [ ] validate access token with facebook
 	- [ ] add player and access token records to the database
 	- [x] send email notification if email field exists in the request
 	- [x] send player id, status as REGISTERED in response

 - ####[x] Already Signed in
 	- [ ] validate access token against facebook
 	- [x] add token record in database if not exist
 	- [x] send player id, status as Already registered in response
 
 
 ###Possible Errors
 
  - Invalid Access token
  - Invalid player id
 
 
 
