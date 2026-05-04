class Department:
    def __init__(self):
        self.id = ""
        self.name = ""

    def getdeptdetails(self, id, name):
        self.id = id
        self.name = name

    def printdept(self):
        print("*"*30)
        print("Department ID:", self.id)
        print("Department Name:", self.name)


class Course(Department):
    def __init__(self):
        Department.__init__(self)
        self.code = ""
        self.cname = ""
        self.duration = ""

    def getcourse(self, code, cname, duration):
        self.code = code
        self.cname = cname
        self.duration = duration

    def printcourse(self):
        print("Course Code:", self.code)
        print("Course Name:", self.cname)
        print("Course Duration:", self.duration)


class Student(Course):
    def __init__(self):
        Course.__init__(self)
        self.rollno = ""
        self.sname = ""
        self.mark = ""

    def getdetails(self, rollno, sname, mark):
        self.rollno = rollno
        self.sname = sname
        self.mark = mark

    def printstudent(self):
        print("Roll Number:", self.rollno)
        print("Student Name:", self.sname)
        print("Marks:", self.mark)
        print("*"*30)


    def display(self):
        self.printdept()
        self.printcourse()
        self.printstudent()


print("_"*30)
print("Enter Department Details")
did = input("Enter Department ID: ")
dname = input("Enter Department Name: ")

print("\nEnter Course Details")
ccode = input("Enter Course Code: ")
cname = input("Enter Course Name: ")
cduration = input("Enter Course Duration: ")

print("\nEnter Student Details")
roll = input("Enter Roll Number: ")
sname = input("Enter Student Name: ")
mark = input("Enter Marks: ")

print("_"*30)
s = Student()


s.getdeptdetails(did, dname)
s.getcourse(ccode, cname, cduration)
s.getdetails(roll, sname, mark)

# Display all
print("\n--- All Details ---")
s.display()
