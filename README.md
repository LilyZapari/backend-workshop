# backend-workshop

Contains a postman collection that validates requests of the Square payments API https://developer.squareup.com/reference/square

## Execute the tests

run the following command:

npx newman run "test\API\collections\Square_API.postman_collection.json"                                                 

## Create test report 

run the following command:

npx newman run test\API\collections\Square_API.postman_collection.json -e test\API\env_variables\Payment_Sanbox.postman_environment.json -r htmlextra --reporter-htmlextra-export test\API\reports
