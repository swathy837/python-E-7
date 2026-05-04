class Employee:
    def __init__(self):
        self.id = ""
        self.name = ""
        self.salary = ""
        self.percentage = ""

    def getemployee(self, id, name, salary, percentage):
        self.id = id
        self.name = name
        self.salary = float(salary)
        self.percentage = float(percentage)

    def calculate_bonus(self):
        bonus = (self.salary * self.percentage) / 100
        return bonus


class Manager(Employee):
    def __init__(self):
        super().__init__()
        self.department = ""
        self.teamsize = ""
        self.allowance = ""

    def getmanager(self, department, teamsize, allowance):
        self.department = department
        self.teamsize = teamsize
        self.allowance = float(allowance)

    def printmanager(self):
        print("\n--- Manager Details ---")
        print("ID:", self.id)
        print("Name:", self.name)
        print("Salary:", self.salary)
        print("Department:", self.department)
        print("Team Size:", self.teamsize)
        print("Allowance:", self.allowance)
        print("Bonus:", self.calculate_bonus())


class Developer(Employee):
    def __init__(self):
        super().__init__()
        self.project = ""
        self.experience = ""

    def getdeveloper(self, project, experience):
        self.project = project
        self.experience = experience

    def printdeveloper(self):
        print("\n--- Developer Details ---")
        print("ID:", self.id)
        print("Name:", self.name)
        print("Salary:", self.salary)
        print("Project:", self.project)
        print("Experience:", self.experience)
        print("Bonus:", self.calculate_bonus())



print("ENTER MANAGER DETAILS")
print("-"*30)
mid = input("ID: ")
mname = input("Name: ")
msalary = input("Salary: ")
mpercentage = input("Bonus Percentage: ")
dept = input("Department: ")
team = input("Team Size: ")
allow = input("Allowance: ")
print("-"*30)

print("\nENTER DEVELOPER DETAILS")
print("-"*30)
did = input("ID: ")
dname = input("Name: ")
dsalary = input("Salary: ")
dpercentage = input("Bonus Percentage: ")
project = input("Project: ")
exp = input("Experience: ")
print("-"*30)

m = Manager()
d = Developer()

m.getemployee(mid, mname, msalary, mpercentage)
m.getmanager(dept, team, allow)

d.getemployee(did, dname, dsalary, dpercentage)
d.getdeveloper(project, exp)


print("\n===== EMPLOYEE DETAILS =====")
print("*"*30)
e = Employee()
m.printmanager()
d.printdeveloper()
print("*"*30)
