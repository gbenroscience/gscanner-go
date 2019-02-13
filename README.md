# gscanner

This is a simple Golang library that helps you quickly scan a string and split it into 
substrings based on an array of supplied tokens.

This library benchmarks very fast and is stable.

There are times when you either can do without the overhead of regular expressions, or the tokens required to 
split a string are a finite number.

There is no need to resort to regular expressions in this case.

This simple library lends itself as an hi-speed scanner/splitter and returns an array containing the substrings of the original
string. Whether you would love to retain the splitting tokens in the scanner's output is totally up to you! 

Simply set the ```IncludeTokensInOutput``` property of your ```GScanner``` to true to retain the splitting tokens.
Else set it to false.

Enjoy!