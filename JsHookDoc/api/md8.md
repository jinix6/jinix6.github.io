# http

Used for making network requests. Requires the hooked application to have network access permissions.

## http.get(url, headers, function)

Performs a GET request to the specified URL.

**Parameters**:

`url`: string - URL to request.

`headers`: object - Headers as key-value pairs.

`function`: function - Callback function with `success` and `error` handlers.

### Example:

```javascript
http.get('http://example.com/api', {
    'Authorization': 'Bearer token123',
    'User-Agent': 'MyApp/1.0'
}, {
    success: function (result) {
        console.log(result);
    },
    error: function (err) {
        console.log(err);
    }
});
```

## http.post(url, data, headers, function)

Performs a POST request to the specified URL.

**Parameters**:

`url`: string - URL to request.

`data`: object | string - Data to send in the request body. If object, it's sent as form-urlencoded; if string, content-type must be specified in headers.

`headers`: object - Headers as key-value pairs.

`function`: function - Callback function with `success` and `error` handlers.

### Example:

```javascript
// POST with form-urlencoded data
http.post('http://example.com/api', {
    'user': 'me',
    'password': 'secret'
}, {
    'Authorization': 'Bearer token123',
    'Content-Type': 'application/x-www-form-urlencoded'
}, {
    success: function (result) {
        console.log(result);
    },
    error: function (err) {
        console.log(err);
    }
});

// POST with JSON data
http.post('http://example.com/api', JSON.stringify({
    'user': 'me',
    'password': 'secret'
}), {
    'Authorization': 'Bearer token123',
    'Content-Type': 'application/json'
}, {
    success: function (result) {
        console.log(result);
    },
    error: function (err) {
        console.log(err);
    }
});
```

## Notes:

- Keys and values in `headers` must both be of type `string`.
- When `data` is an object, the request defaults to `application/x-www-form-urlencoded` content-type unless explicitly set to `application/json` in `headers`.