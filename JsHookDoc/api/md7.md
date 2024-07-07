# file

Used for file-related operations.

## file.isFile(path)

Checks if the specified path is a file.

**Parameters**:

`path`: string - File path.

**Returns**: boolean - `true` if the path is a file, `false` otherwise.

## file.isDir(path)

Checks if the specified path is a directory.

**Parameters**:

`path`: string - Directory path.

**Returns**: boolean - `true` if the path is a directory, `false` otherwise.

## file.isExists(path)

Checks if the specified path exists.

**Parameters**:

`path`: string - File or directory path.

**Returns**: boolean - `true` if the path exists, `false` otherwise.

## file.read(path)

Reads the contents of a file as a string.

**Parameters**:

`path`: string - File path.

**Returns**: string - Contents of the file as a string.

## file.readBytes(path)

Reads the contents of a file as byte array.

**Parameters**:

`path`: string - File path.

**Returns**: byte[] - Contents of the file as byte array.

## file.write(path, content)

Writes string content to a file.

**Parameters**:

`path`: string - File path.

`content`: string - Content to write.

## file.writeBytes(path, content)

Writes byte array content to a file.

**Parameters**:

`path`: string - File path.

`content`: byte[] - Content to write.

## file.append(path, content)

Appends string content to the end of a file.

**Parameters**:

`path`: string - File path.

`content`: string - Content to append.

## file.appendBytes(path, content)

Appends byte array content to the end of a file.

**Parameters**:

`path`: string - File path.

`content`: byte[] - Content to append.

## file.copy(path, topath)

Copies a file from `path` to `topath`.

**Parameters**:

`path`: string - Source file path.

`topath`: string - Destination file path.

## file.move(path, topath)

Moves/rename a file from `path` to `topath`.

**Parameters**:

`path`: string - Source file path.

`topath`: string - Destination file path or new name.

## file.rename(path, newname)

Renames a file.

**Parameters**:

`path`: string - File path.

`newname`: string - New name for the file.

## file.delete(path)

Deletes a file or directory.

**Parameters**:

`path`: string - File or directory path.

## file.getName(path)

Gets the name of the file or directory from the path.

**Parameters**:

`path`: string - File or directory path.

**Returns**: string - Name of the file or directory.

## file.getSize(path)

Gets the size of the file in bytes.

**Parameters**:

`path`: string - File path.

**Returns**: long - Size of the file in bytes.

## file.zip(path, topath, passwd?)

Creates a zip archive from the specified path.

**Parameters**:

`path`: string - Source directory path to zip.

`topath`: string - Destination zip file path.

`passwd`: string (optional) - Password for encryption.

## file.unzip(path, topath, passwd?)

Extracts a zip archive to the specified path.

**Parameters**:

`path`: string - Source zip file path to unzip.

`topath`: string - Destination directory path.

`passwd`: string (optional) - Password for decryption.