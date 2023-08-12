from math import *
class classname:
    def fun1(self):
        a=12
        b=50
        c=50

        d=(b*b) -(4*a*c)

        if d<0:
             
             print('roots are imaginary')
    
        else:
             x1=(-b+sqrt(d))/(2*a)
             X2=(-b-sqrt(d))/(2*a)
             print('X1=',x1)
             print('X2=',X2)
    
obj1=classname()
obj1.fun1()
