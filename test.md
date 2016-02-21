

#Player Sign in

###Flow

 - [ ] validate game code
 - [ ] validate Point of sale
 - [ ] validate access token with Source Social Networking
 - [x] check is player exists in DB

  - ####First Time Sign in, if player not exists
   	- [ ] add player and access token records to the database
   	- [x] send email notification if email field exists in the request
   	- [x] send player id, status as REGISTERED in response

   - ####Already Signed in, if player exists
    - [x] add token record in database if not exist
    - [x] send player id, status as Already registered in response


###Possible Errors

  - Invalid Access token
  - Invalid player id
  - Invalid Game code
  - Invalid POS
