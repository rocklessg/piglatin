# piglatin

print("Welcome To My Piglatin")

pyg = "ay"

original = input("Enter a word:")

#print(original)

if len(original) > 0 and original.isalpha():
    
    print(original)
    
    word = original.lower()
    
    first = original[0]

else:
    
    print("please \"type\" a word to proceed...") 

new_word = word + first + pyg

#print(new_word)

new_word = word[1:] + first + pyg

print (new_word)


