# FCC API Project: Timestamp Microservice

## About
This is my project of the [Timestamp microservice challenge](https://www.freecodecamp.org/learn/back-end-development-and-apis/back-end-development-and-apis-projects/timestamp-microservice) for the freeCodeCamp Back End Development and APIs certification. It was built based on the boilerplate available [here](https://github.com/freeCodeCamp/boilerplate-project-timestamp/).

## Technologies
- **Node.js** and **Express** to create the server and handle routes, requests and responses.

## Endpoints:

Endpoints | Description | Params
----------|-------------|-------------
GET `/api/:date?` | return unix and utc of date entered | date (via query)
GET `/api/1451001600000` | return `{ unix: 1451001600000, utc: "Fri, 25 Dec 2015 00:00:00 GMT" }`| date (via query)
GET `/api/` | Return current unix and utc | n/a

#### Example output:
* `{"unix":1142985600000,"utc":"Wed, 22 Mar 2006 00:00:00 GMT"}`
* `{"unix":1451001600000,"utc":"Fri, 25 Dec 2015 00:00:00 GMT"}`

## How to use:
```
npm install
npm start
```
