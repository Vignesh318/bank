import math
p= int(input("enter pi"))
t= int(input("enter time"))
print("enter for bankk 1")
y1 = int (input("Enter year "))
intr = float(input("Enter intrest: "))
y2 = int (input("Enter year "))
intr2 = float(input("Enter intrest "))
y3 = int(input("Enter year "))
intr3 = float(input("Enter intrest "))
s1=pow((1+intr),y1*12)
emi1=(p*intr)/(1-1/s1)
s2=pow((1+intr2),y2*12)
emi2=(p*intr2)/(1-1/s2)
s3=pow((1+intr3),y3*12)
emi3=(p*intr)/(1-1/s3)
su01=emi1+emi2+emi3

print("enter for bankk 2")
y01 = int (input("Enter year "))
intr0 = float(input("Enter intrest: "))
y02 = int (input("Enter year "))
intr02 = float(input("Enter intrest "))
y03 = int(input("Enter year "))
intr03 = float(input("Enter intrest "))
s01=pow((1+intr0),y01*12)
emi01=(p*intr0)/(1-1/s01)
s02=pow((1+intr02),y02*12)
emi02=(p*intr02)/(1-1/s02)
s03=pow((1+intr03),y03*12)
emi03=(p*intr03)/(1-1/s03)
su02=emi1+emi2+emi3
if(su01<su02):
    print("Bank 1")
else:
    print("Bank 2")



      

   
   


    
