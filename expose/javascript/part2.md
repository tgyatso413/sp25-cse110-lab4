1. At line 12, the value of i will be printed because var has no block-level visibility, so i's value can be used at line 12.
2. Line 13 will also print smoothly due to var's lack of block-level visibility.
3. Same as the first two - all of the variables are in the same function, so the console can read their values.
4. [50, 100, 150]
5. An error will be thrown because i's value doesn't exist outside the for loop.
6. An error will be thrown because discountedPrice was deckared in a block.
7. finalPrice can be printed because it was declared outside of the block.
8. [50, 100, 150]
9. An error will be thrown because i's value doesn't exist outside the for loop.
10. length should be printed because length's value has not been changed.
11. [50, 100, 150]
12. 
    1.  student.name
    2.  student['Grad Year']
    3.  student.greeting()
    4.  student['Favorite Teacher'].name
    5.  CSE110
13. 
    1.  "32" is outputted because 2 is converted into a string.
    2.  1 is outputted because '3' is converted into an int.
    3.  3 is outputted becayse null is turned into 0.
    4.  4 is outputted because true is equal to 1.
    5.  0 is outputted because both false and null are equivalent to 0.
    6.  "3undefined" is outputted because undefined is converted into a string.
    7.  NaN is outputted because "3" turns into 3 and undefined turns into NaN.
14. 
    1.  true: '2' is turned into an int.
    2.  false: since they are strings and not ints, 2 is greater than 1.
    3.  true: the == comparison turns '2' into 2.
    4.  false: true is equivalent to 1
    5.  true: Boolena(2) is equal to true
15. == compares values after type coercion, while === doesn't convert types.
16. 
17. [2,4,6] is returned.
18. 
19.  1 and 4 are printed, then after 1 second, 2 and 3 will print.