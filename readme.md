StringTest 
1. What is the knowledge point of the test? Where is the official document to the knowledge point?
	* Official Document: https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html 
	* Learning of Optional Class 
       * Strings are immutable
       * String builder
	* String manipulation
	* String unicode
2. Why the test failed at first?
	* The expected values are incorrect
3. Why you corrected the test that way?
	* I initialized the value of Optional Boolean from Optional.empty() to Optional.of(true||false)
	* Get the index of the expectedString and used substring to get the expected output.
	* Split string by whitespace or forward slash and store in an array
	* Used nested for loop to design the expected output and string builder to store characters.
	* For loop to checksum of each character in a string
	* Initialized the expected output string Unicode to display Nihongo characters
	* Add string builder to store characters and used for loop to get the last character to first character
	* Initialized value with string format and change and concatenate the format classifier as variable.
4. Do you have further questions on this knowledge point?
	* None


