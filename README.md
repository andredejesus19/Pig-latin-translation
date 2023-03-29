# Pig-latin-translation
This is my first code in Python 


# This variable is the letters that will end the word
pyg = 'ay' 

# Here input in the console the word what let's translation
original = input('Enter a word:') 

# Here we testing if teh word was input with only letter and don't have numbers or symbols
if len(original) > 0 and original.isalpha(): 

    print (original) # Print the word what was input in console

#   Here let's transform all the letters of word in lowercase
    word = original.lower() 

#   Here we will separate the first letter for inpunt in the end the word
    first= word[0] 

#   Sum of the three variables for make the translation to pig latin!
    new_word= word + first + pyg

#   Let's choose which letter the translated word will start from and finally print
    new_word= new_word[1:len(new_word)]
    print (new_word)

# Case not have a word input the code go print "empty"
else:
    print ('empty')
