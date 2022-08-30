# add-quotes-to-string
I used this little python script to make a line of words into a line of array items. I will be using it some more and I dont want to lose it, so it'll stay here.

To use the script you'll need separated words in one line. In the included file words are separated with a comma, if there is no comma in your line, you'll have to modify the code a bit:

On line 2, ``` line2 = ''.join( c for c in line if  c not in ',' ) ```, delete the comma in the end.

If you don't need the comma between the words at all, delete the comma on line 3, ``` ext = ' '.join('"{}",'.format(word) for word in line2.split(' ')) ```
