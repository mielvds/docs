# Errors

## HTTP Status Code Summary

* **200 OK** - Everything worked as expected.
* **400 Bad Request** - Often missing a required parameter.
* **401 Unauthorized** - No valid authorization header provided.
* **403 Forbidden** - The authenticated user isn't activated yet, suspended or banned.
* **404 Not Found** - The requested item doesn't exist.
* **405 Method Not Allowed** -  A request was made using a request method not supported by that resource.
* **500, 502, 503, 504 Server errors** - something went wrong on the DataTank's end.