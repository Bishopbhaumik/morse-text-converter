# morse-text-converter
The given project is to take a text file as input and display # its morse code and vice versa.   

# SOLUTION METHOD FOLLOWED  
According to our given problem statement we have initialised the morse and character values of each. Then we are taking a command line input and we are extracting the  extension of the file. If the extention is .txt then we perform the text to morse  conversion and if the extension is .morse then morse code to text conversion is done. 

## TEXT TO MORSE ALGORITHM  

If the extension of the entered file is .txt then we will get right into conversion  to the morse code for the same. We will read each character from the file one by one. If the character read is found to be '\n' or next line operator then we also move to a # new line in the display promt. If the character is a valid character then we print the respective morse value for it followed by a '/'. If the character is a blankspace ' ' then we print a '/'. So the output comes is such a way that each letter of a word is  separated by a '/' and each word is separated by a '//'.  

## MORSE TO TExT ALGORITHM  
If the extension of the entered file is .morse then we will get right into conversion  to the text for the same. We will read each character from the file one by one.  If the character read is found to be '\n' or next line operator then we also move to a  new line in the display promt. We have taken a string variable &lt;word> in which we will   store the read characters until we find a '/'. When a '/' is found then we will print the # &lt;word> variable and again make it null and &lt;flag> is made to 1. If we again find a '/' and # the &lt;flag> is 1 then we will print a blankspace and make &lt;flag> to 0. Here I have predefined the alphabets and certain characters with their respective morse code values.
