class Student:
    def __init__(self, name, roll_no, test_mark):
        self.name = name
        self.roll_no = roll_no
        self.test_mark = test_mark

    def total_marks(self):
        return self.test_mark

    def display(self):
        print("Name:", self.name)
        print("Roll No:", self.roll_no)
        print("Total Marks:", self.total_marks())


class Literary_Student(Student):
    def __init__(self, name, roll_no, test_mark, literary_marks):
        super().__init__(name, roll_no, test_mark)
        self.literary_marks = literary_marks

    def total_marks(self):
        return self.test_mark + self.literary_marks


class Sports_Student(Student):
    def __init__(self, name, roll_no, test_mark, sports_marks):
        super().__init__(name, roll_no, test_mark)
        self.sports_marks = sports_marks

    def total_marks(self):
        return self.test_mark + self.sports_marks


class Lit_Sport_Student(Student):
    def __init__(self, name, roll_no, test_mark, literary_marks, sports_marks):
        super().__init__(name, roll_no, test_mark)
        self.literary_marks = literary_marks
        self.sports_marks = sports_marks

    def total_marks(self):
        return self.test_mark + self.literary_marks + self.sports_marks


name = input("Enter name: ")
roll = int(input("Enter roll number: "))
test = int(input("Enter test mark: "))
lit = int(input("Enter literary mark: "))
sport = int(input("Enter sports mark: "))

s = Lit_Sport_Student(name, roll, test, lit, sport)

print("\nStudent Details")
s.display()
