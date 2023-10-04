# fun_rectangular.py
#practice
#function to calculate aRAEA and parimeter of a rectangular
#reuirements
#length
#breadth
#AREA
#PARIMETER

#CODE
def rectangular(length,breadth):
    area=length*breadth
    perimeter=2*(length+breadth)
    return area,perimeter
#function ends here
l=int(input("enter the length of rectangular:"))
b=int(input("enter the breadth of rectangular:"))
area,perimeter=rectangular(l,b)
print("area is",area,"\nperimeter is :",perimeter)

