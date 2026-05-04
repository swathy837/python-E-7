class Vehicle:
    def __init__(self):
        self.make = ""
        self.year = ""
        self.colour = ""

    def getvehicle(self, make, year, colour):
        self.make = make
        self.year = year
        self.colour = colour

    def printvehicle(self):
        print("Make:", self.make)
        print("Year:", self.year)
        print("Colour:", self.colour)


class Car(Vehicle):
    def __init__(self):
        super().__init__()
        self.model = ""
        self.capacity = ""

    def getcar(self, model, capacity):
        self.model = model
        self.capacity = capacity

    def printcar(self):
        print("\n--- Car Details ---")
        super().printvehicle()
        print("Model:", self.model)
        print("Capacity:", self.capacity)


class Bike(Vehicle):
    def __init__(self):
        super().__init__()
        self.type = ""
        self.mileage = ""

    def getbike(self, type, mileage):
        self.type = type
        self.mileage = mileage

    def printbike(self):
        print("\n--- Bike Details ---")
        super().printvehicle()
        print("Type:", self.type)
        print("Mileage:", self.mileage)


print("-"*30)

print("ENTER CAR DETAILS")
make1 = input("Make: ")
year1 = input("Year: ")
colour1 = input("Colour: ")
model = input("Model: ")
capacity = input("Capacity: ")

print("\nENTER BIKE DETAILS")
make2 = input("Make: ")
year2 = input("Year: ")
colour2 = input("Colour: ")
btype = input("Type: ")
mileage = input("Mileage: ")
print("-"*30)


c = Car()
b = Bike()


c.getvehicle(make1, year1, colour1)
c.getcar(model, capacity)

b.getvehicle(make2, year2, colour2)
b.getbike(btype, mileage)

print("\n CAR DETAILS")
print("*"*30)
c.printcar()
print("*"*30)
print("\n BIKE DETAILS")
print("*"*30)
b.printbike()
print("*"*30)
