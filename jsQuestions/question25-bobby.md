* What is the difference between `==` and `===`?

The `equality operator` '==' and the `identity operator` '===' behave identically except that '===' does not do type conversion meaning the types of both arguments must be equal or else the comparison will return false.

the `==` operator conversely will compare for equality *after doing any necessary type conversions*.

##### Examples of some equality operator cases:
```
'' == '0'           // false
0 == ''             // true
0 == '0'            // true

false == 'false'    // false
false == '0'        // true

false == undefined  // false
false == null       // false
null == undefined   // true

' \t\r\n ' == 0     // true
```