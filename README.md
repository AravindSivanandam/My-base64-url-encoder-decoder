# My-base64-url-encoder-decoder
For Encoding and Decoding base64-url !



In contrast to base64 RFC3548 , In base64 url, the 62nd character ('+') is replaced with '-', the 63rd character ('/') is replaced with '_'.
Furthermore, the encoder does not fill the string with trailing '='.
The resulting encoded strings comply to the regular expression pattern '[A-Za-z0-9_-]' and thus are safe to use in URLs or for file names.



