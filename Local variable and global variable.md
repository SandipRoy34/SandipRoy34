### Hi there 👋

i=6#it's global variable because it's used avobe the fuction but it can be used in this whole program even inside that function
def myfun(y):
    x=10#local variable because we used it inside a function
    i=1
    i=i+1#we can not use same global variable in assingment operator because it will be referenced as local we have to make a other local variable for to work inside that function.
    print('sum is',x+y+i)
   
   
myfun(10)
