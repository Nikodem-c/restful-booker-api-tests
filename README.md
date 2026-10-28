# Restful Booker API Testing

An API testing project built with Postman using the public Restful Booker API.

### Project Overview

The goal of this project is to practice API testing, HTTP methods, request configuration, and authentication.

**API:** Restful Booker

**Tools:** Postman

### Test Coverage

The Postman collection currently includes requests for:

 - GET — Retrieve booking IDs and booking details

 - GET — Filter bookings using supported query parameters

- POST — Create a new booking

- PUT — Update an existing booking

- PATCH — Partially update a booking

- DELETE — Delete a booking

### Setup

1. Download the Postman collection JSON file from this repository.

2. Import the collection into Postman.

3. Configure the baseUrl environment variable:
https://restful-booker.herokuapp.com

4. Send the requests using the appropriate request configuration and authentication where required.

### To Do

 - Add automated test assertions

- Add positive and negative test scenarios

- Automate authentication token handling

- Improve test data management

- Add collection execution reports

### Notes

Restful Booker is a public demo API. Its data may be reset periodically, so booking IDs and test data can change.

This project is being developed incrementally, with new test scenarios and automation features added over time.
