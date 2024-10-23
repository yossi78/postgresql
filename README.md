
# Project Information and Limitations

--------------------------------------------------------------------------------------------------
## INSTRUCTIONS

1. Download the Postman collection from the "resources" package.


--------------------------------------------------------------------------------------------------

## HOW TO RUN POSTGRESQL DATA BASE CONTAINER

1. Open a terminal in the root directory of the project.
2. Run the following command to start the MySQL container:
   ```bash
   docker-compose up



OPEN UI IN BROWSER
-------------------------------------------------------------------------------------------------------------
#) Open the browser in the following url:
http://localhost:8080/


--------------------------------------------------------------------------------------------------


## HOW TO CONFIG DATA BASE CLIENT

Name = users
Host = localhost
Port = 5432
Username =user
Password = password
Database = testdb


--------------------------------------------------------------------------------------------------

# HOW TO ADD NEW USER USING CURL

curl --location "http://127.0.0.1:8080/api/users" --header "Content-Type: application/json" --data "{\"firstName\": \"Yossi\", \"lastName\": \"Tal\"}"

curl --location "http://127.0.0.1:8080/api/users" --header "Content-Type: application/json" --data "{\"firstName\": \"Dani\", \"lastName\": \"Cohen\"}"

--------------------------------------------------------------------------------------------------

# HOW TO GET EXIST USER USING CURL

curl --location "http://127.0.0.1:8080/api/users/2"



--------------------------------------------------------------------------------------------------



