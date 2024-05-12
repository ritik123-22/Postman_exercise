# Postman_exercise

The attached JSON file is a Postman collection export file. Postman is a popular API development and testing tool. This file defines a collection of HTTP requests, along with their associated metadata, that can be used for testing an API.


In this specific Postman collection, there are two requests defined:

Address - Verify: A POST request to the EasyPost API to verify an address. The request body contains the address details, and the authorization header includes an API key. The event script for this request includes two tests: one to check for the absence of errors in the response body, and another to verify the ZIP code in the response data.
Get - Shipment details: A GET request to the EasyPost API to retrieve shipment details. The request URL includes a shipment ID. The event script for this request includes two tests: one to verify the retail rate, and another to compare the retail and list rates.
