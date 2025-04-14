# python-grade-managment
print('heyy.. welcome to your student grade system')
student={}
def adding_std(name,marks):
    student[name]=grade
    print(f"added {name} with {grade} succesfully")
def update_std(name,grade):
    if name in student:
        student[name]= grade
        print(f"your data is succesfully updated")
    else:
        print("{name} is not found")
def del_std(name):
    if name in student:
        del student[name]
        print(f"your {name} is successfully deleted")
    else:
        print("student not found")
def display_std():
    if display_std:
        for name,grade in student.items():
            print(f"{name}:{grade}")
    else:
        print("student not found")
while True:
    your=int(input("we can:-\n1=add\n2=update\n3=delete\n4=display\n5=exit\nwhat you want:-"))
    if your==1:
        name=input("enter your name:-")
        grade=input("enter your grade:-")
        adding_std(name,grade)
    elif your==2:
        name=input("enter your name you want to update:-")
        grade=input("enter your grade you want to update:-")
        update_std(name,grade)
    elif your==3:
        name=input("enter your name you want delete:-")
        del_std(name)
    elif your==4:
        display_std()
    elif your==5:
        print("(:....thank you so much please visit again......:)")
        break
    
                 
            
                 
             
             

    
        
    
    
