# Caesar Shift

The Caesar Shift is one of the earliest known secret codes. To encode using a Caesar Shift, you shift each letter in your message to the right a certain number of spaces in the alphabet.

For example, encoding``` "hello"``` with a Caesar Shift of 3 would produce ```"khoor"```.

Specifically, take "h" - start there and count three more letters in the alphabet, "i", "j", "k". So "h" becomes "k". Etc.


This gets tricky when you reach the end of the alphabet. For example, consider encoding "yes" with a Caesar Shift of 3. Starting at "y", the next letter is "z"... and that's the end of the alphabet! So we start over from the beginning, and count "a", then "b". "y" encoded with a shift of 3 "b". So, "yes" would be encoded as "bhv".



# Your Task

You should see a function header in ```main.py```. Write it so it correctly encodes and decodes using a given Caesar shift.

You will ONLY get strings made of lowercase letters. We won't worry about spaces, uppercase letters, grammar characters, etc.

You're given alphabet at the top of your main.py file; use it!

Finally, as one way to test yourself: - the string ```"helloworld"``` with a shift of 5 - should encode to the string ```"mjqqtbtwqi"```. Note that "w" becomes "b"!