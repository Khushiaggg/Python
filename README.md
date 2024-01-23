# Python
Python

def isPalindrome(string):                       #Define a function 
    if (string == string[::-1]) : 
        return "The string is a palindrome." 
    else: 
        return "The string is not a palindrome." 
 
string = input ("Enter string: ")               #Enter input string 
 
print(isPalindrome(string))
