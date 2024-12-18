# Task1
def is_palindrome(string):
    # Convert the string to lowercase to make the check case-insensitive
    string = string.lower()
    # Reverse the string and compare with the original
    return string == string[::-1]


input_string = "radar"
print(is_palindrome(input_string))  
