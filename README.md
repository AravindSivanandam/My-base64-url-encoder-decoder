# My-base64-url-encoder-decoder
For Encoding and Decoding base64-url !

Base64URL is a modification of the main Base64 standard, the purpose of which is the ability to use the encoding result as filename or URL address.

The Base64URL is described in RFC 4648 ยง 5, where it is mentioned that the standard Base64 alphabet contains invalid characters for URLs and filenames.

In contrast to base64 RFC3548 , In base64 url, the 62nd character ('+') is replaced with '-', the 63rd character ('/') is replaced with '_'.
Furthermore, the encoder does not fill the string with trailing '='.
The resulting encoded strings comply to the regular expression pattern '[A-Za-z0-9_-]' and thus are safe to use in URLs or for file names.

๐๐๐ฌ๐๐๐ ๐ฎ๐ซ๐ฅ ๐๐ง๐ ๐๐๐ฌ๐๐๐ ๐๐ก๐๐ซ๐๐๐ญ๐๐ซ๐ฌ


Uอpอpอeอrอcอaอsอeอ Lอeอtอtอeอrอsอ


Index	                : 0 1 2 3 4 5 6 7 8 9 10  11  12  13  14  15  16  17  18  19  20  21  22  23  24  25  
	
Base64 url Character  : A B C D E F G H I J K   L   M   N   O   P   Q   R   S   T   U   V   W   X   Y   Z

Base64 Character      : A B C D E F G H I J K   L   M   N   O   P   Q   R   S   T   U   V   W   X   Y   Z

Lอoอwอeอrอcอaอsอeอ Lอeอtอtอeอrอsอ


Index	                : 26 27 28 29 30  31  32  33  34  35  36  37  38  39  40  41  42  43  44  45  46  47  48  49  50  51
	
Base64 url Character  : a  b  c  d  e   f   g   h   i   j   k   l   m   n   o   p   q   r   s   t   u   v   w   x   y   z

Base64 Character      : a  b  c  d  e   f   g   h   i   j   k   l   m   n   o   p   q   r   s   t   u   v   w   x   y   z

Dอiอgอiอtอsอ


Index	                :  52	  53	 54	 55	 56	  57	 58	 59	 60	 61	 

Base64 url Character  :  0    1    2   3   4    5    6   7   8    9

Base64 Character      :  0    1    2   3   4    5    6   7   8    9

Sอyอmอbอoอlอsอ


Index	                :   62     63

Base64 url Character  :   -      _

Base64 Character      :   +      /

=    (optional)

