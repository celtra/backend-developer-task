# Notes API

Create REST API that allows users to manage their notes.  
Notes can be organized into folders for easier management.  
API should allow user authentication through basic HTTP authentication (username and password).  
The goal is to build a simple but secure and easily scalable service.  

### Entities
* Basic user info (name, username, password) should be stored in the database
* Users own multiple folders that can be named
* Folders contain multiple notes that can be named
* Notes can be shared (visible to all users and unauthenticated viewers) or private (visible only to the creator)
* Notes can be of 2 different types
  * Text note - has text body
  * List note - has list items that contain text body

### API
* API for users is not needed, data can be seeded into the database
* Should support CRUD actions for folders
* Should support CRUD actions for notes
* Implement at least 2 out of 3
  * Pagination should be supported
  * Sorting should be supported
    * By note shared option (public/private)
    * By note heading
  * Filtering should be supported
    * By note folder
    * By note shared option (public/private)
    * By note text

### Directions
* You can use any programming language/framework for REST API
* All data should be saved in database of your choice
* No frontend is needed, only API
* Users are authenticated via username and password. Users authentication data (usernames/passwords) can be generated and seeded in the provided database since API for users is not required.

### Submission
* Commit the code into the provided repository
  * Add [instructions](instructions/README.md)
  * Add [database seed](database/README.md)
  * Add [credentials](credentials/README.md)


