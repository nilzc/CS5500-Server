# Express Server for CS5500 Project
## API Endpoint
### users
* GET ```/api/users``` Find all users
* GET ```/api/users/:uid``` Find user by id
* POST ```/api/users``` Create user
* PUT ```/api/users/:uid``` Update user
* DELETE ```/api/users/:uid``` Delete user

### tuits
* GET ```/api/tuits``` Find all tuits
* GET ```/api/users/:uid/tuits``` Find all tuits by user
* GET ```/api/tuits/:tid``` Find tuit by id
* GET ```/api/users/:uid/tuits-with-media``` Find tuits with media by user ID
* POST ```/api/users/:uid/tuits``` Create tuit by user, media content should be sent as **multipart/form-data**
* PUT ```/api/tuits/:tid``` Update tuit
* DELETE ```/api/tuits/:tid``` Delete tuit by id

