# Global Functions

## toast(message)

**Parameters**:

- `message`: string

Displays a toast message.

## alert(message)

**Parameters**:

- `message`: string

Displays an alert with the specified message.

## confirm(message, callback)

**Parameters**:

- `message`: string
- `callback`: function

Displays a confirmation dialog with the given message. The `callback` object should include:

- `ok`: Function to execute when the user confirms.
- `cancel`: Function to execute when the user cancels.

Example:

```javascript
confirm('is ok?', {
    ok: function () {
        //...
    },
    cancel: function () {
        //...
    }
})
```

## uuid()

Returns a 32-character lowercase UUID.

**Returns**: string