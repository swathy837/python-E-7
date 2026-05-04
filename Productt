class Product:
    def __init__(self):
        self.id = ""
        self.name = ""
        self.price = ""

    def getproduct(self, id, name, price):
        self.id = id
        self.name = name
        self.price = price

    def add_to_cart(self):
        print("Product added to cart")


class Electronics(Product):
    def __init__(self):
        super().__init__()
        self.product_name = ""
        self.type = ""
        self.warranty = ""

    def getdetails(self, product_name, type, warranty):
        self.product_name = product_name
        self.type = type
        self.warranty = warranty

    def display(self):
        print("\n--- Electronics Product ---")
        print("ID:", self.id)
        print("Name:", self.name)
        print("Price:", self.price)
        print("Product Name:", self.product_name)
        print("Type:", self.type)
        print("Warranty:", self.warranty)

    def add_to_cart(self):
        self.display()
        print("Electronics added to cart successfully")


class Clothing(Product):
    def __init__(self):
        super().__init__()
        self.type = ""
        self.size = ""
        self.colour = ""

    def getdetails(self, type, size, colour):
        self.type = type
        self.size = size
        self.colour = colour

    def display(self):
        print("\n--- Clothing Product ---")
        print("ID:", self.id)
        print("Name:", self.name)
        print("Price:", self.price)
        print("Type:", self.type)
        print("Size:", self.size)
        print("Colour:", self.colour)

    def add_to_cart(self):
        self.display()
        print("Clothing added to cart successfully")


print("-"*30)
print("ENTER ELECTRONICS DETAILS")
eid = input("ID: ")
ename = input("Name: ")
eprice = input("Price: ")
pname = input("Product Name: ")
etype = input("Type: ")
warranty = input("Warranty: ")

print("\nENTER CLOTHING DETAILS")
cid = input("ID: ")
cname = input("Name: ")
cprice = input("Price: ")
ctype = input("Type: ")
size = input("Size: ")
colour = input("Colour: ")

print("-"*30)
e = Electronics()
e = Electronics()
c = Clothing()


e.getproduct(eid, ename, eprice)
e.getdetails(pname, etype, warranty)

c.getproduct(cid, cname, cprice)
c.getdetails(ctype, size, colour)


print("\n===== SHOPPING CART =====")
print("*"*30)
e.add_to_cart()
c.add_to_cart()
print("*"*30)
