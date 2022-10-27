# inheritance/mropractice
# without inheritance
class Person:
  def __init__(self, firstname, lastname, age):
    self.firstname=firstname
    self.lastname=lastname
    self.age=age
    print('In Class Person')
    
class Student():
  def __init__(self, firstname, lastname, age, sr_code, section, grade):
    self.firstname=firstname
    self.lastname=lastname
    self.age=age
    self.sr_code=sr_code
    self.section=section
    self.grade=grade
    print('In Class Student')

person=Person('Angel', 'Dela Cruz', 40)
print(person.firstname)
print(person.lastname)
print(person.age)

student=Student('Lyzel', 'Leido', 20, 2103618 ,2101, 1.50)
print(student.firstname)
print(student.lastname)
print(student.age)
print(student.sr_code)
print(student.section)
print(student.grade)
			
