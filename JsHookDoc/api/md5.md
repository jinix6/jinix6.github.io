# crypto

Used for string encryption, decryption, and hashing.

## crypto.encrypt(key,data,enctype,transformation)

Encrypts data using specified encryption algorithm and transformation.

**Parameters**:

`key`: string - Encryption key.

`data`: string - Data to encrypt.

`enctype`: CRYPTO_AES | CRYPTO_DES - Encryption type.

`transformation`: string - Transformation name (e.g., `DES/CBC/PKCS5Padding`).

**Returns**: string - Encrypted data.

## crypto.encryptBytes(key,data,enctype,transformation)

Encrypts byte array using specified encryption algorithm and transformation.

**Parameters**:

`key`: byte[] - Encryption key.

`data`: byte[] - Data to encrypt.

`enctype`: CRYPTO_AES | CRYPTO_DES - Encryption type.

`transformation`: string - Transformation name (e.g., `DES/CBC/PKCS5Padding`).

**Returns**: byte[] - Encrypted data as byte array.

## crypto.decrypt(key,data,enctype,transformation)

Decrypts data using specified encryption algorithm and transformation.

**Parameters**:

`key`: string - Decryption key.

`data`: string - Data to decrypt.

`enctype`: CRYPTO_AES | CRYPTO_DES - Encryption type.

`transformation`: string - Transformation name (e.g., `DES/CBC/PKCS5Padding`).

**Returns**: string - Decrypted data.

## crypto.decryptBytes(key,data,enctype,transformation)

Decrypts byte array using specified encryption algorithm and transformation.

**Parameters**:

`key`: byte[] - Decryption key.

`data`: byte[] - Data to decrypt.

`enctype`: CRYPTO_AES | CRYPTO_DES - Encryption type.

`transformation`: string - Transformation name (e.g., `DES/CBC/PKCS5Padding`).

**Returns**: byte[] - Decrypted data as byte array.

## crypto.rc4Encrypt(key,data)

Encrypts data using RC4 encryption algorithm.

**Parameters**:

`key`: string - Encryption key.

`data`: string - Data to encrypt.

**Returns**: string - Encrypted data.

## crypto.rc4EncryptBytes(key,data)

Encrypts byte array using RC4 encryption algorithm.

**Parameters**:

`key`: byte[] - Encryption key.

`data`: byte[] - Data to encrypt.

**Returns**: byte[] - Encrypted data as byte array.

## crypto.rc4Decrypt(key,data)

Decrypts data using RC4 encryption algorithm.

**Parameters**:

`key`: string - Decryption key.

`data`: string - Data to decrypt.

**Returns**: string - Decrypted data.

## crypto.rc4DecryptBytes(key,data)

Decrypts byte array using RC4 encryption algorithm.

**Parameters**:

`key`: byte[] - Decryption key.

`data`: byte[] - Data to decrypt.

**Returns**: byte[] - Decrypted data as byte array.

## crypto.md5(data)

Generates MD5 hash of the input string.

**Parameters**:

`data`: string - Input data.

**Returns**: string - MD5 hash.

## crypto.md5Bytes(data)

Generates MD5 hash of the input byte array.

**Parameters**:

`data`: byte[] - Input data.

**Returns**: string - MD5 hash.

## crypto.sha1(data)

Generates SHA-1 hash of the input string.

**Parameters**:

`data`: string - Input data.

**Returns**: string - SHA-1 hash.

## crypto.sha1Bytes(data)

Generates SHA-1 hash of the input byte array.

**Parameters**:

`data`: byte[] - Input data.

**Returns**: string - SHA-1 hash.

## crypto.sha256(data)

Generates SHA-256 hash of the input string.

**Parameters**:

`data`: string - Input data.

**Returns**: string - SHA-256 hash.

## crypto.sha256Bytes(data)

Generates SHA-256 hash of the input byte array.

**Parameters**:

`data`: byte[] - Input data.

**Returns**: string - SHA-256 hash.