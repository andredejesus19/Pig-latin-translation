# Pig-latin-translation
This is my first code in Python 

# This code is for translantion the words to pig latin

pyg = 'ay' # This variable is the letters that will end the word

original = input('Enter a word:') # here input in the console the word what let's translation

if len(original) > 0 and original.isalpha(): # Here we testing if teh word was input with only letter and don't have numbers or symbols

    print (original) # Print the word what was input in console

#   Here let's transform all the letters of word in lowercase
    word = original.lower() 

#   Here we will separate the first letter for inpunt in the end the word
    first= word[0] 

#   Sum of the three variables for make the translation to pig latin!
    new_word= word + first + pyg
    new_word= new_word[1:len(new_word)]
    print (new_word)
else:
    print ('empty')
