**Level 5**  <br>
Given an input string and a dictionary of words, split the input string into a space-separated sequence of dictionary words if possible. For example, if the input string is "thisisafunproblem" and the dictionary contains a standard set of English words,then we would return the string "this is a fun problem."

submitted by [seemaullal](https://github.com/seemaullal)

myList1 =['this', 'is', 'a','fun','problem']
myString = 'thisisafunproblem'
myList =[]
for word in myList1: 
    if word in myString:
        myList.append(word)
print(myList)
result = ''
for word in myList:
    result+= ' ' + word
print(result)
