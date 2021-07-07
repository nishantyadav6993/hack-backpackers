# hack-backpackers
Create/Retrieve product detils


## Running

```
mvn clean install
mvn spring-boot:run
```
When the application is first built, it will create a database file in the directory specified in the ```application.properties``` file. 

## * Testing *

### Curl Tests

```
POST: curl -X POST -d @sample.json -H "Content-Type: application/json" http://localhost:8090/saveDetails
GET:  curl -i -H "Accept: application/json" -H "key:PRODUCT" http://localhost:8090/getsummary
```
