# 5-bit-language (single hand)
```
this language derives primarily from english, with an an alphabeet of 26 letters (characters).
words can be formed through a comb(o)-ination of letters in the english language.

(from left to right)
first bit represents thumb
the next 4 bits are the other fingers

0 means that the finger is absent
1 means that the finger is present

any 5 bits that do not correspond to a value in the alphabet is represented as null.

a present finger is one that is fully extended
an absent finger is one that is fully retracted

example:
0 0000 = all fingers are absent, value: null (a fist)
1 1111 = all fingers are present, value: null (high five)

alphabet (right hand):
a =	0 0001
b =	0 0010
c =	0 0011
d = 	0 0100
e =	0 0101
f =	0 0110
g =	0 0111
h =	0 1000
i =	0 1001
j =	0 1010
k =	0 1011
l =	0 1100
m =	0 1101
n =	0 1110
o =	0 1111
p =	1 0000
q =	1 0001
r =	1 0010
s =	1 0011
t =	1 0100
u =	1 0101
v =	1 0110
w =	1 0111
x =	1 1000
y =	1 1001
z =	1 1010

TO DO:
- add left hand functionality
- add values to null expressions
```
