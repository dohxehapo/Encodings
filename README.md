# Encodings

Headers that contain different encoding methods:

1. Base64
2. MD5

## Base64

Base64 algorithm is implemented in the Base64.h header file. This file contains static encoding-decoding tables and encoding-decoding functions: Base64_Encode and Base64_Decode. These functions accept strings as an input and generate string as a result. To work with unsigned char in general additional (yet very simple) wrappers are required.

## Md5

Md5 algorithm is implemented in the Md5.h header file. This file contains static encoding tables used in calculations and encoding fuction: Md5_Encode. This function accepts vector of bytes as an input and returns the hex-formatted string as a result.

<br>
Anton Egorov, 2016<br>
dohxehapo@gmail.com
