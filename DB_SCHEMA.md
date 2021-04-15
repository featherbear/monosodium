# USERS

> User-specific data and settings

* User[]
  * MSG_AUTH : {}
    * Username : string
    * Password : string
    * Sessions : unknown[]
  * FB_AUTH : {}
    * Username : string
    * Password : string
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
