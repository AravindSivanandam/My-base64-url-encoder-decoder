# My-base64-url-encoder-decoder
For Encoding and Decoding base64-url !

Base64URL is a modification of the main Base64 standard, the purpose of which is the ability to use the encoding result as filename or URL address.

The Base64URL is described in RFC 4648 § 5, where it is mentioned that the standard Base64 alphabet contains invalid characters for URLs and filenames.

In contrast to base64 RFC3548 , In base64 url, the 62nd character ('+') is replaced with '-', the 63rd character ('/') is replaced with '_'.
Furthermore, the encoder does not fill the string with trailing '='.
The resulting encoded strings comply to the regular expression pattern '[A-Za-z0-9_-]' and thus are safe to use in URLs or for file names.

base64 url and bse64 characters

Uppercase Letters
Index	Base64 url Character  Base64 Character
0	    A                     A
1	    B                     B
2	    C                     C
3	    D                     D
4	    E                     E
5	    F                     F
6	    G                     G
7	    H                     H
8	    I                     I
9	    J                     J
10	  K                     K
11	  L                     L
12	  M                     M
13	  N                     N
14	  O                     O
15	  P                     P
16	  Q                     Q
17    R                     R
18	  S                     S
19	  T                     T
20	  U                     U
21	  V                     V
22	  W                     W
23	  X                     X
24	  Y                     Y
25	  Z                     Z

Lowercase Letters
Index	Base64 url Character  Base64 Character
26	  a                     a
27	  b                     b
28	  c                     c
29	  d                     d
30	  e                     e
31	  f                     f
32	  g                     g
33	  h                     h
34	  i                     i
35	  j                     j
36	  k                     k
37	  l                     l
38	  m                     m
39	  n                     n
40	  o                     o
41	  p                     p
42	  q                     q
43	  r                     r
44	  s                     s
45	  t                     t
46	  u                     u
47	  v                     v
48	  w                     w
49	  x                     x
50	  y                     y
51	  z                     z

Digits
Index	Base64 url Character  Base64 Character
52	  0                     0
53	  1                     1
54	  2                     2
55	  3                     3
56	  4                     4
57	  5                     5
58	  6                     6
59	  7                     7
60	  8                     8
61	  9                     9

Symbols
Index	Base64 url Character  Base64 Character
62    -                     +
63	  _                     /

(pad) =    (optional)

