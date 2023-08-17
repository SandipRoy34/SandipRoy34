class student1:#this is parent class
    
    def activity(self):
        print('you are a punctual boy')
    def gpa(self):
            print('congratulations,you have')


class student2(student1):#inheritamce,this is derived class or child class 
        def name(self):
            print('welcome sandip')
        
                
obj1=student2()
obj1.name()
obj1.activity()
obj1.gpa()
