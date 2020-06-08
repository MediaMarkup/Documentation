# Authentication

The api is a REST based API that uses a Bearer token Authorization.

Each API endpoint for Users and Approvals requires an Authorization header containing the Bearer access token. Calls to endpoints without a valid token will result in a 401 Unauthorized http status code.

An access token is obtained by calling the _**/connect/token**_ using the _ClientId_ and _ClientSecret_ for a registered account.

Once the access token is obtained this is used for all subsequent calls to the other available API endpoints.

See the list of endpoints here: [https://api.mediamarkup.com/docs/index.html](https://api.mediamarkup.com/docs/index.html)

