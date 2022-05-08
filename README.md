class length:
    l = 0
    def length(self):  
        return self.l
class breadth:
    b = 0
    def breadth(self):
        return self.b
class rect_area(length, breadth):
    def r_area(self):
        print("The area of rectangle with length "+str(self.l)+" units and breadth "+ 
              str(self.b)+" units is "+str(self.l * self.b)+" sq. units.")
o = rect_area()
o.l = int(input("Enter the required length for rectangle: "))
o.b = int(input("Enter the required breadth for rectangle: "))
o.r_area()
