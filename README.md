_**Roman Numerals Kata**_

`Introduction`

The Romans wrote their numbers using letters; specifically the letters 'I' meaning '1', 'V' meaning '5', 'X' meaning '10', 'L' meaning '50', 'C' meaning '100', 'D' meaning '500', and 'M' meaning '1000'. There were certain rules that the numerals followed which should be observed.

The symbols 'I', 'X', 'C', and 'M' can be repeated at most 3 times in a row. The symbols 'V', 'L', and 'D' can never be repeated. The '1' symbols ('I', 'X', and 'C') can only be subtracted from the 2 next highest values ('IV' and 'IX', 'XL' and 'XC', 'CD' and 'CM'). Only one subtraction can be made per numeral ('XC' is allowed, 'XXC' is not). The '5' symbols ('V', 'L', and 'D') can never be subtracted.


`Problem - Converting Arabic to Roman`

We would like to be able to convert Arabic numbers into their Roman numeral equivalents. We just need some kind of program that can accept a numeric input and output the Roman numeral for the input number. **To simplify things a bit we just need this program to convert numbers up to 3,999**.


**Examples**

   1 ➔ I
   
   2 ➔ II
   
   3 ➔ III
   
   4 ➔ IV
   
   5 ➔ V
   
   9 ➔ IX
   
  21 ➔ XXI
  
  45 ➔ XLV
  
  50 ➔ L
  
 100 ➔ C
 
 500 ➔ D
 
1000 ➔ M


