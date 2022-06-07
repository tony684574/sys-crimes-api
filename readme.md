# sys-crimes-api
Designed to securely add crimes and retrieve crimes. 
## Usage
- endpoints: /crimes
- methods: GET, POST
- protocol: HTTP
- responses: 200, 201 only atm

## Tools
- MongoDB
- APIKit
- Mule Standalone Runtime ver. 4.3
- Anypoint Studio
- Anypoint Platform
- Secure Properties Tool
- Postman Collection
- Git
  
## POST /crimes
```
{
    "name": "nameOfCrime",
    "sentenceLength": int, // in days
    "dateSubmitted": "yyyy-MM-dd",
    "Active": boolean
}
```
_Under Construction_
