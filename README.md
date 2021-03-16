

#Pseudo code
=======

Reversing String:
V1:
Get word
Reverse word
Display reversed word

V2:
GET word
For every letter in word push to the right
Display word

V3:
GET word
FOR letter in str
  Take last letter
  Append letter to reverseWord
ENDFOR
PRINT reverseWord

V4:
GET word
INIT reverseWord
FOR letter in str
  GET last letter
  INCREMENT reverseWord by last letter
  DECREMENT str
ENDFOR
PRINT reverseWord







Fibonnaci Sequence:
======
v1:
get an input n
go through fibonnaci sequence n times

v2:
GET n
For up to n times
  Get next number in sequnce

v3:
GET n
FOR n
  ADD previousNumber to currentNumber

v4:
GET n
INIT prevNumber
SET prevNumber as 0
INIT currentNumber
SET currentNumber as 1
FOR n
  ADD prevNumner to currentNumber
ENDFOR
PRINT currentNumber

v5:
GET n
INIT prevNumber
SET prevNumber as 0
INIT currentNumber
SET currentNumber as 1
INIT temp
FOR n - 1 
  SET temp as currentNumber
  ADD prevNumner to currentNumber
  SET prevNumber as temp
ENDFOR
PRINT currentNumber
