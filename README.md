# ms-jwt-security

JSON Web Token
JSON Web Token (JWT) defines a compact and self-contained way for securely transmitting information between parties as a JSON object.

Scenarios where JSON Web Tokens are useful:

Authorization: the most common scenario for using JWT. Single Sign On is a feature that widely uses JWT
Information Exchange: Because JWTs can be signed, JSON Web Tokens are a good way of securely transmitting information between parties.
JSON Web Tokens consist of 3 parts:

Header
Payload
Signature
-> JWT looks like Header-Base64-String.Payload-Base64-String.Signature-Base64-String

Header consists of two parts:

token type.
hashing algorithm.
