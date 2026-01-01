import random
print("****************student marks detector****************************")
name = input(("Enter the student name: "))
print(f"welcome,{name}")
seat_number = input("Enter the seat number: ")
print(f"nice,{name} and your marks will be.......!!")


marks = (random.randint(0,100))
print(marks)


if marks>=95:
    grade = "A++"
elif marks>=85:
    grade = "A"
elif marks>=75:
    grade = "B"
elif marks>=60:
     grade = "C"
else:
   print("Fail")
    
    #output section
print('-------------result------------')
print(f"name : {name}")
print(f"Seat Number:  {seat_number}")
print(f"marks : {marks}")
print(f"you got grade:  {grade}")
print(f"\nCongratulations! {name}" if grade!="fail" else "\n try next time")

print(f"\nCongratulations! {name}" if grade!="fail" else "\n try next time")
