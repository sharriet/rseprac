# Solution to problem 5

**(i) Can you determine the content of the fname_out variable?**

It would be a string in a format like this:

`Ozone_2001-01-01_0000.png`

**(ii) What information is missing?**

+ The `Home` variable is undefined and should be a string. Not sure if maybe it's meant to specify a path to a base directory or something else.
+ The `simhour` variable is undefined and should be a number which will have a constant length of 4 digits.
+ `Timestamp` is currently a constant and should probably be assigned the current date. This could be achieved using the built-in `datetime` module.
