# -*- coding: utf-8 -*-
"""
Spyder Editor

This is a temporary script file.
"""

#A string
class_name = "p5_Delinquents: "
#Error: Class_name + 5              You cannot concenate a string and number
student1 = "Carlos"
top_delinquents = "Carlos, Nicholas, Gionna, Gonzalo"
class_students = class_name + top_delinquents


print(class_students)
third_student = 3
same_name = "2"
print(type(same_name))
student2 = "Carlos" + same_name
print(student2)
student3 = "Carlos" + str(third_student)
print(student3)

#Int
grade1 = input("What did you get in p1")
grade2 = input("What did you get in p2")
grade3 = input("What did you get in p3")
grade4 = input("What did you get in p4")

print("to verify: you scored:" + "\n" + str(grade1) + "\n"
      + str(grade2) + "\n" + str(grade3) + "\n" + str(grade4))

gpa = (int(grade1) + int(grade2) + int(grade3) + int(grade4)) /4
print("GPA: " +str(gpa))
