# json

Used for encoding and decoding JSON strings.

## json.toGsonString(data)

Converts an object to a JSON string using Gson.

**Parameters**:

`data`: object - Data to be converted to JSON.

**Returns**: string - JSON string representation of the data.

### Example:

```javascript
const obj = {
    name: 'John',
    age: 30,
    city: 'New York'
};

const jsonStr = json.toGsonString(obj);
console.log(jsonStr);
```

## json.gsonStringToClass(data, class)

Converts a JSON string to a class instance using Gson.

**Parameters**:

`data`: string - JSON string data.

`class`: class - The class type to convert the JSON into.

**Returns**: class - Instance of the class populated with JSON data.

### Example:

```javascript
const jsonStr = '{"name":"John","age":30,"city":"New York"}';
const MyClass = Java.use('com.example.MyClass'); // Replace with your actual class name
const instance = json.gsonStringToClass(jsonStr, MyClass);
console.log(instance);
```

## json.toJSONString(data)

Converts an object to a JSON string.

**Parameters**:

`data`: object - Data to be converted to JSON.

**Returns**: string - JSON string representation of the data.

### Example:

```javascript
const obj = {
    name: 'Alice',
    age: 25,
    city: 'London'
};

const jsonStr = json.toJSONString(obj);
console.log(jsonStr);
```

## json.parseObject(data)

Parses a JSON string into a JSONObject.

**Parameters**:

`data`: string - JSON string data.

**Returns**: JSONObject - Parsed JSON object.

### Example:

```javascript
const jsonStr = '{"name":"Alice","age":25,"city":"London"}';
const jsonObj = json.parseObject(jsonStr);
console.log(jsonObj.name); // Output: Alice
```

## json.parseArray(data)

Parses a JSON string into a JSONArray.

**Parameters**:

`data`: string - JSON string data representing an array.

**Returns**: JSONArray - Parsed JSON array.

### Example:

```javascript
const jsonStr = '[{"name":"Alice","age":25},{"name":"Bob","age":30}]';
const jsonArray = json.parseArray(jsonStr);
console.log(jsonArray.length); // Output: 2
```