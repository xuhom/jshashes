# jsHashes

## About

jsHashes is a pure JavaScript implementation of the most extended hash algorithms.
It's goal is to provide a easy solution for hash algorithms both for client-side and server-side JavaScript.
The code is full compatible with the ECMAScript language specification and was tested in all major browsers (client-side) and Node.js 6.x.x (server-side).   

## Supported hash algorithms

* MD5 <http://www.ietf.org/rfc/rfc1321.txt>
* SHA1 <http://homes.esat.kuleuven.be/~bosselae/ripemd160.html>
* SHA256 <http://csrc.nist.gov/publications/fips/fips180-2/fips180-2.pdf>
* SHA512 <http://csrc.nist.gov/publications/fips/fips180-2/fips180-2.pdf>
* HMAC <http://www.ietf.org/rfc/rfc2104.txt>
* RIPEMD-160 <http://homes.esat.kuleuven.be/~bosselae/ripemd160.html>

## Usage
TODO...

### Client-Side

### Server-Side (Node.js)

## Public methods
All the hash algorithms include the following public methods:

* hex(string) - Hexadecimal hash calculation from string 
* b64(string) - Base64 hash calculation from string
* any(string,encoding) - Any method with encoding
* hex_hmac(string,key) - Hexadecimal hash with HMAC key
* b64_hmac(string,key) - Base64 hash with HMAC key 
* any_hmac(string,key,encoding) - Any method with HMAC support
* vm_test() - Simple self-test to see is working

## Encoding hash supported

* Hexadecimal (most extended)
* Base64
* HMAC encryption

## Benchmark
TODO...

## Notes

* Don't support checksum hash for files on the server-side, only text-based inputs are supported.
* Not has been planned to add support for more hash algorithms.
* The goal is to provide the same JavaScript code in both server and client side. 

## Version

* 1.0b - First release: the code is stable, but the library is still beta and must be improved and documented.

## Authors 

### Library author

* Tomas Aparicio <https://github.com/h2non/>

### Original code author and algorithms implementation

* Paul Johnston <http://pajhome.org.uk/crypt/md5/>
* Angel Marin
* Jeremy Lin

### Other contributors

* Greg Holt
* Andrew Kepert
* Ydnar
* Lostinet

## License

jsHashes is released under New BSD license <http://www.opensource.org/licenses/BSD-3-Clause>.
See LICENSE.txt

## Issues

Feel free to report any issue you experiment via Github <https://github.com/h2non/jsHashes/issues>.
