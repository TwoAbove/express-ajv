# express-ajv
Express middleware that helps validating user input

## What
A simple middleware for your expressjs routes that accepts JSON schemas and uses AJV under the hood to validate request payload (querystring, body, headers and params)

## Why
* Express validator is good for websites imho, not complex apis
* JSON schema is good and can model anything in your project, this is good for orgs where you have multiple services
* AJV is fast and it just works
