# printing-the-given-string-is-a-palindrome-or-not-by-using-function
def isPalindrome(data):
    s=str(data).lower()
    if s==s[::-1]:
        print("The string ",s,"is palindrome")
    else:
        print("It is not a palindrome")
n=input("enter any string:")
isPalindrome(n)
