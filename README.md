dict={"Shape1":"Square","Shape2":"Cube","Shape3":"Circle","Shape4":"Sphere","Shape5":"Cone"} 
user_input=(input("Enter the shape you want to get Perimeter, Area,Volume")) 
if dict.get("Shape1")==user_input:
    side=int(input("Enter side of square")) 
    peri_sq = 4 * side
    area_sq = side ** 2
    print("\nThe perimeter of square is : ", peri_sq, 
      "\nThe area of square is : ",area_sq,) 
if dict.get("Shape2")==user_input:
    side=int(input("Enter side of cube")) 
    area_cube = 6 * (side ** 2)
    vol_cube = side ** 3
    print("\nThe area of cube is : ",area_cube, 
    "\nThe volume of cube is : ",vol_cube,) 
if dict.get("Shape3")==user_input:
    radius =int(input("Enter radius of circle")) 
    peri_cir = 2 *(22/7) * radius
    area_cir = (22/7) * (radius) ** 2
    print("\nThe perimeter of circle is : ",peri_cir, 
      "\nThe area of circle is : ",area_cir,) 
if dict.get("Shape4")==user_input:
    radius=int(input("Enter radius of sphere")) 
    area_sph = 4 * (22/7) * (radius) ** 2
    vol_sph = (4/3) * (22/7) * (radius) ** 3
    print("\nThe area of sphere is : ",area_sph, 
     "\nThe volume of sphere is : ",vol_sph,) 
if dict.get("Shape5")==user_input:
    side_cone=int(input("Enter side of cone")) 
    radius_cone=int(input("Enter radius of cone")) 
    area_cone = (22/7) * side_cone * radius_cone
    print("\nThe area of cone is : ",area_cone,) 
else:
    print("Enter a value between Square, Cube, Circle, Sphere, Cone") 
