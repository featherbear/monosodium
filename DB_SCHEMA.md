# USERS

> User-specific data and settings

* User[]
  * MSG_AUTH : {}
    * username : string
    * password : string // crypt
    * sessions : unknown[]
  * FB_AUTH : {}
    * user ID : number // store this
    * username : string // maybe don't need this
    * password : string // maybe don't need this
    * session : unknown
  * SETTINGS : {}
  * QUEUE : unknown[]

# THREADS

> Messages and media of a user

* UserThread[]
  * user : User
  * threads : Thread[]
    * id : unknown
    * name : unknown
    * members : unknown[]
    * messages : Message[]
      * from ?: unknown
      * to ?: unknown
      * timestamp : Date (number)
      * data : unknown[]
