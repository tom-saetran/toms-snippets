## toms-snippets
### by Tom-Lennart Sætran
#### Creative Commons Zero v1.0 Universal
###### Code snippets by yours truly

&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;

# httpCodes.js

Useful for checking what the response code means in your crud before it get muteted through .json().  
Works with all fetch methods as it only correlates the status code as a key and returns the value from the httpCodes object.

- Example:

```js
let httpCode = 404
console.log(httpCodes[httpCode])
```
- Output:

```js
{
    number: "404",
    type: "Client Error Response",
    name: "Not Found",
    description: "The server can not find the requested resource. In the browser, this means the URL is not recognized. In an API, this can also mean that the endpoint is valid but the resource itself does not exist. Servers may also send this response instead of 403 to hide the existence of a resource from an unauthorized client. This response code is probably the most famous one due to its frequent occurrence on the web."
}
```

&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;

# toms-bootstrap-extensions.css

CSS classes to extent bootstrap, written to feel like bootstrap.











