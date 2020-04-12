# Flask_Rest API

A REST API service which will:
* Authenticate user with JWT tokens
* Perform CRUD operations for a user’s list of favorite books.  
* Each book will have the following fields - title, amazon_url, author, genre

* Check for expired token and re-authenticate

## Installation

Use the POSTMAN for all the API calls.

```bash
pip install requirements.txt
```

## Usage
 * User can register and login and get their own JWT token and use it for CRUD operations
 * The individual token will be valid for 30 minutes.  
 * Admin is also a user but he can view all the user and user's book and can delete user's information.
 * incase of token Expired login to get a new token.

## TECHNOLOGY USED:  
![PYTHON](https://www.python.org/static/opengraph-icon-200x200.png)
![FLASK](https://hackr.io/tutorials/learn-flask/logo/logo-flask?ver=1557984169)
![JWT_TOKENS](https://vegibit.com/wp-content/uploads/2018/07/JSON-Web-Token-Authentication-With-Node.png)
![RESTFULL_API](https://snmpcenter.com/wp-content/uploads/2016/10/RESTful-API-logo-for-light-bg.png)
