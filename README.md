##Request user to enter a sentence e.g. "This is a bunch of words"
##Assign the user response to a variable called str_manipulation
##Calculate and display the length of str_manip.
##Find the last letter in str_manip. Replace every occurrence of this
##letter in str_manip with ‘@’.
##Print the last 3 characters in str_manip backwards.
##Create a five-letter word that is made up of the first three characters
##and the last two characters in str_manip.

str_manip = input("Please enter any long sentence:")
print(str_manip)
print(len(str_manip))
str_manip2 = str_manip.replace("s" , "@")
print(str_manip2)
str_manipulation3 = str_manip[49:45:-1]
print(str_manipulation3)
str_manipulation4 = (str_manip[:3] + str_manip[49:46:-1])
print(str_manipulation4)





