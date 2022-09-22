# Python-Functions
Write a function called add_excitement that takes a list of strings and adds an exclamation point (!) to the end of each string in the list. The program should modify the original list and not return anything.
def add_excitement(string_list):
    string_list = [e+"!" for e in string_list]
    print(string_list)
x = []
for i in range(3):
    List1 = input("Enter a string: ")
    x.append(List1)
add_excitement(x)
    
