# FUTURE_CS_03 
# API Security Risk Analysis

## Overview

This project presents a basic API security risk analysis conducted on the **JSONPlaceholder** public testing API. The goal of the assessment was to identify common API security risks such as missing authentication, excessive data exposure, and lack of protective controls.

The analysis was performed using **Postman** through safe, read-only API requests. This exercise demonstrates how security analysts review APIs to identify potential risks without exploiting vulnerabilities.

## Tools Used

* Postman – API request testing
* Browser Developer Tools – Response inspection
* JSONPlaceholder API – Public testing API

## API Tested

Example endpoint tested:

```
GET https://jsonplaceholder.typicode.com/users
```

## Key Findings

* Public access to user data without authentication
* Ability to access individual users by modifying IDs
* Excessive data exposure in API responses
* No visible rate limiting controls


## Conclusion

This project demonstrates practical skills in identifying API security risks and documenting findings based on common industry frameworks such as the OWASP API Security Top 10.

## Author

Grace Wambui
