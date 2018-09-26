===============================================================
======== Mobile Phone Number Permutation List (Taiwan) ========
===============================================================

Description:
    Each phone number consists of 10 digits, where all of them starts with '09'.
The third and forth digits indicate which telecom company it belongs to. Below
are some analysis of how likely it is to find an actually-existing number in a
particular 'Range of Prefix' (the 3rd and 4th digits).


      MarketShare(2018)  #Prefixes  MarketShare Per Prefix
Emome:        35 %       20         1.75 %
FETnet:       24 %       23         1.04 %
TaiwanMobile: 24 %       23         1.04 %
TStar:        8 %        4          2.00 %
APTG:         8 %        6          1.33 %


Emome:
  0905*, 10, 11, 12, 19
    21,  28, 32, 33, 34
    37,  63, 65, 66, 72
    74,  75, 78, 84, 88 

FETnet:
  0900*, 03, 13, 15, 16
    17,  25, 26, 27, 30
    31,  36, 38, 54, 55
    60,  62, 66, 67, 68
    76,  81, 89

TaiwanMobile:
  0909*, 14, 18, 20, 22
    23,  24, 29, 31, 35
    39,  52, 53, 56, 58
    60,  61, 66, 70, 71
    79,  83, 87

TStar: 0908*, 71, 73, 86

APTG: 0906*, 07, 77, 80, 82, 85


All Prefixes: (71)
  (Note that some of them are shared among different companies. Those prefixes
  have the highest probabilities of finding a real number.)

05, 10, 11, 12, 19, 21, 28, 32, 33, 34, 37, 63, 65, 66(3), 72, 74, 75, 78, 84, 88
00, 03, 13, 15, 16, 17, 25, 26, 27, 30, 31(2), 36, 38, 54, 55, 60(2), 62, 67, 68, 76, 81, 89
09, 14, 18, 20, 22, 23, 24, 29, 35, 39, 52, 53, 56, 58, 61, 70, 71(2), 79, 83, 87
08, 73, 86
06, 07, 77, 80, 82, 85
