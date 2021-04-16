# USERS

> User-specific data and settings

* User[]
  * MSG_AUTH : {}
    * Username : string
    * Password : string // crypt
    * Sessions : unknown[]
  * FB_AUTH : {}
    * User ID : number // store this
    * Username : string // maybe don't need this
    * Password : string // maybe don't need this
    * Session : unknown
  * Settings : {}
  * Queue : unknown[]

# THREADS

> Messages and media of a user

* UserThread[]
  * User : User
  * Threads : Thread[]
    * ID : unknown
    * Name : unknown
    * Participants : unknown[]
    * Messages : Message[]
      * From ?: unknown
      * To ?: unknown
      * Timestamp : Date (number)
      * Data : unknown[]
