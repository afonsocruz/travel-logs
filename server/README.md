# Full Stack Travel Log

Aplicação fullstack pra você guardar ou listar os lugares que você viajou.
A full stack application to store / list places you have traveled.

### TODO 

* [x] Setup Server
  * [x] Install Dependencies
  * [x] Install / Setup Linter
  * [x] Setup Express App
  * [x] Setup Not Found and Error Middlewares
* [x] Model DB
  ### What data will we store?
  #### Log Entry
  * Title - text
  * Description - text
  * Comments - text
  * Rating - scale of 1 - 10
  * Image - text- url
  * Start Date - DateTime
  * End Date - DateTime
  * Latitude - Number
  * Longitude - Number
  * Created At - DateTime
  * Updated At - DateTime
* [X] Setup Mongoose Model(s)
* [x] POST / logs
  * Create a new log entry
* [x] GET / logs
  * List all log entries
* [ ] Setup Client
* [ ] Create Form to add a new entry
* [ ] Setup Map SDK on client
* [ ] List all log entries on map