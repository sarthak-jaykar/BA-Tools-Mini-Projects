**Objective**



A small standalone Postman project demonstrating basic REST API testing skills relevant to BA/DA roles.



**API Used**



JSONPlaceholder — public test REST API.



**Tests Performed**

Request	Purpose	Result

GET Posts	GET request + \_limit query parameter	200 OK

GET Single Post	Path parameter + response validation	200 OK

POST Create Post	POST + JSON body + Content-Type header	201 Created

GET Invalid Post	Negative/error testing	404 Not Found

Validations

Status-code validation

Required response fields

Response data/content validation

Generated ID validation

Negative/error response validation

**Postman Concepts Demonstrated**

Collections

GET \& POST requests

Query/path parameters

JSON request body

HTTP headers

Response validation using Postman tests

Positive and negative API testing

**Evidence**


Screenshots are included in the screenshots/ folder:



Collection overview

POST request and validations

Negative test and validations

**BA/DA Relevance**



APIs are commonly used for system integration and data exchange. A BA can use API testing to verify that systems send/receive the expected data and that error scenarios are handled correctly.



**Interview Explanation**



“I created a small Postman API testing project using JSONPlaceholder. I tested GET and POST endpoints, used query/path parameters, JSON request bodies and headers, and added response validations for status codes and required fields. I also included a negative test for a non-existent resource and organized everything into a Postman collection.”

