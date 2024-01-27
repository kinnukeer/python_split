# python_split
import string
my_str=input("Enter a paragraph:")
words=my_str.split(" ")
words.sort()
#display the sorted words
for word in words:
  print(word)
