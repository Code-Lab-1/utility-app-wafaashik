[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=9694213&assignment_repo_type=AssignmentRepo)

#displaying the item info
print( '\033[1m'+ 'WELCOME TO THE')
print('\033[1m'+'COMBO-VENDING EXPRESS!!'+'\033[0m')
print('\033[1m' +'\033[92m'+ 'HERE IS THE MENU' + '\033[0m' )

Candy= 1001
print('\033[92m'+ "1001 - Candy")
Drinks= 2001
print("2001 - Drinks")
Chips= 3001
print("3001 - Chips")
Ice_creams= 4001
print("4001 - Ice_creams")
Other= 5001
print("5001 - Other"+'\033[0m')
choice=int(input("Please select your product: "))


if choice== Candy:
  print ('\033[94m'+" ~ You have selected Candy ~ "+'\033[0m')
  print(" {{ Here are the list of candies available }}")
  Skittles= 101
  print('\033[92m'+"101 - Skittels            - 1AED")
  Gumballs= 201
  print("201 - Gumballs            - 2AED")
  Dairymilk=301
  print("301 - Dairymilk           - 2AED")
  Snickers= 401
  print("401 - Snickers            - 3AED")
  Galaxy=  501
  print("501 - Galaxy              - 3AED")
  Kitkats= 601
  print("601 - Kitkats             - 3AED"+'\033[0m')
  choice=int(input("  Type a product code to continue... "))

if choice== Skittles:
  print('\033[94m'+" ~ Great! You have chosen Skittles ~ ")
  print("Please Pay 1 AED"+'\033[0m')
  y=float(input("Please insert the money.."))
  Skittles = 1
  if y > Skittles:
      print("Here is your change: ",y - Skittles)
      print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
  elif y< Skittles:
       print('\033[91m'+"please enter enough money"+'\033[0m')
       print('\033[91m'+"Your money is refunded "+'\033[0m')
      
  elif y==Skittles:
      print('\033[94m'+"Here is your item...")
      print("Thankyou for the purchase, have a good day!"+'\033[0m')
 
if choice== Gumballs:
      print('\033[94m'+" ~ Great! You have chosen Gumballs ~ ")
      print("Please Pay 2 AED"+'\033[0m')
      y=float(input("Please insert the money.."))
      Gumballs = 2
      if y > Gumballs:
          print("Here is your change :  ",y - Gumballs)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
      elif y< Gumballs:
           print('\033[91m'+"please enter enough money"+'\033[0m')
           print('\033[91m'+"Your money is refunded "+'\033[0m')
      elif y==Gumballs:
          print('\033[94m'+"Here is your item...")
          print("Thankyou for the purchase, have a good day!"+'\033[0m')

if choice== Dairymilk:
      print('\033[94m'+" ~ Great! You have chosen Dairymilk ~ ")
      print("Please Pay 2 AED"+'\033[0m')
      y=float(input("Please insert the money.."))
      Dairymilk = 2
      if y > Dairymilk:
          print("Here is your change :  ",y - Dairymilk)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
      elif y< Dairymilk:
        print('\033[91m'+"please enter enough money"+'\033[0m')
        print('\033[91m'+"Your money is refunded "+'\033[0m')
      elif y==Dairymilk:
       print('\033[94m'+"Here is your item...")
       print("Thankyou for the purchase, have a good day!"+'\033[0m')

if choice== Snickers:
      print('\033[94m'+" ~ Great! You have chosen Snickers ~ ")
      print("Please Pay 3 AED"+'\033[0m')
      y=float(input("Please insert the money.."))
      Snickers = 3
      if y > Snickers:
          print("Here is your change : ",y - Snickers)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
      elif y< Snickers:
         print('\033[91m'+"please enter enough money"+'\033[0m')
         print('\033[91m'+"Your money is refunded "+'\033[0m')
      elif y== Snickers:
        print('\033[94m'+"Here is your item...")
        print("Thankyou for the purchase, have a good day!"+'\033[0m')

if choice== Galaxy:
      print('\033[94m'+" ~ Great! You have chosen Galaxy ~ ")
      print("Please Pay 3 AED"+'\033[0m')
      y=float(input("Please insert the money.."))
      Galaxy = 3
      if y > Galaxy:
          print("Here is your change :  ",y - Galaxy)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
      elif y< Galaxy:
         print('\033[91m'+"please enter enough money"+'\033[0m')
         print('\033[91m'+"Your money is refunded "+'\033[0m')
      elif y==Galaxy:
        print('\033[94m'+"Here is your item...")
        print("Thankyou for the purchase, have a good day!"+'\033[0m')

if choice== Kitkats:
      print('\033[94m'+" ~ Great! You have chosen Kitkats ~ ")
      print("Please Pay 3 AED"+'\033[0m')
      y=float(input("Please insert the money.."))
      Kitkats = 3
      if y > Kitkats:
          print("Here is your change : ",y - Kitkats)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
      elif y< Kitkats:
         print('\033[91m'+"please enter enough money"+'\033[0m')
         print('\033[91m'+"Your money is refunded "+'\033[0m')
      elif y==Kitkats:
        print('\033[94m'+"Here is your item...")
        print("Thankyou for the purchase, have a good day!"+'\033[0m')



if choice== Drinks:
  print ('\033[94m'+" ~ You have selected Drinks ~ "+'\033[0m')
  print(" {{ Here are the list of Drinks available }}")
  Water=701
  print('\033[92m'+"701 - Water            - 1AED")
  MountainDew= 801
  print("801 - MountainDew      - 3AED")
  Pepsi=901
  print("901 - Pepsi            - 3AED")
  ColdCoffee= 111
  print("111 - ColdCoffee       - 3AED")
  Sprite=  112
  print("112 - Sprite           - 3AED")
  Coke= 113
  print("113 - Coke             - 3AED"+'\033[0m')
  choice=int(input("  Type a product code to continue... "))


if choice==Water:
  print('\033[94m'+" ~ Great! You have chosen Water ~ ")
  print("Please Pay 1 AED"+'\033[0m')
  y=float(input("Insert the money.."))
  Water = 1
  if y > Water:
      print("Here is your change: ",y - Water)
      print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
  elif y< Water:
       print('\033[91m'+"please enter enough money"+'\033[0m')
       print('\033[91m'+"Your money is refunded "+'\033[0m')
      
  elif y==Water:
      print('\033[94m'+"Here is your item...")
      print("Thankyou for the purchase, have a good day!"+'\033[0m')
 
if choice== MountainDew:
      print('\033[94m'+" ~ Great! You have chosen MountainDew ~ ")
      print("Please Pay 3 AED"+'\033[0m')
      y=float(input("Please insert the money.."))
      MountainDew = 3
      if y > MountainDew:
          print("Here is your change :  ",y - MountainDew)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
      elif y< MountainDew:
           print('\033[91m'+"please enter enough money"+'\033[0m')
           print('\033[91m'+"Your money is refunded "+'\033[0m')
      elif y==MountainDew:
          print('\033[94m'+"Here is your item...")
          print("Thankyou for the purchase, have a good day!"+'\033[0m')

if choice== Pepsi:
      print('\033[94m'+" ~ Great! You have chosen Pepsi ~ ")
      print("Please Pay 3 AED"+'\033[0m')
      y=float(input("Please insert the money.."))
      Pepsi = 3
      if y > Pepsi:
          print("Here is your change :  ",y - Pepsi)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
      elif y< Pepsi:
        print('\033[91m'+"please enter enough money"+'\033[0m')
        print('\033[91m'+"Your money is refunded "+'\033[0m')
      elif y==Pepsi:
       print('\033[94m'+"Here is your item...")
       print("Thankyou for the purchase, have a good day!"+'\033[0m')

if choice== ColdCoffee:
      print('\033[94m'+" ~ Great! You have chosen ColdCoffee ~ ")
      print("Please Pay 3 AED"+'\033[0m')
      y=float(input("Please insert the money.."))
      ColdCoffee = 3
      if y > ColdCoffee:
          print("Here is your change : ",y - ColdCoffee)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
      elif y< ColdCoffee:
         print('\033[91m'+"please enter enough money"+'\033[0m')
         print('\033[91m'+"Your money is refunded "+'\033[0m')
      elif y==ColdCoffee:
        print('\033[94m'+"Here is your item...")
        print("Thankyou for the purchase, have a good day!"+'\033[0m')

if choice== Sprite:
      print('\033[94m'+" ~ Great! You have chosen Sprite ~ ")
      print("Please Pay 3 AED"+'\033[0m')
      y=float(input("Please insert the money.."))
      Sprite = 3
      if y > Sprite:
          print("Here is your change :  ",y - Sprite)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
      elif y< Sprite:
         print('\033[91m'+"please enter enough money"+'\033[0m')
         print('\033[91m'+"Your money is refunded "+'\033[0m')
      elif y==Sprite:
        print('\033[94m'+"Here is your item...")
        print("Thankyou for the purchase, have a good day!"+'\033[0m')

if choice== Coke:
      print('\033[94m'+" ~ Great! You have chosen Coke ~ ")
      print("Please Pay 3 AED"+'\033[0m')
      y=float(input("Please insert the money.."))
      Coke = 3
      if y > Coke:
          print("Here is your change : ",y - Coke)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
      elif y< Coke:
         print('\033[91m'+"please enter enough money"+'\033[0m')
         print('\033[91m'+"Your money is refunded "+'\033[0m')
      elif y==Coke:
        print('\033[94m'+"Here is your item...")
        print("Thankyou for the purchase, have a good day!"+'\033[0m')
 

#CHIPS
if choice== Chips:
  print ('\033[94m'+" ~ You have selected Chips ~ "+'\033[0m')
  print(" {{ Here are the list of Chips available }}")
  Doritos=114
  print('\033[92m'+"114 - Doritos             - 3AED")
  Cheetos= 115
  print("115 - Cheetos             - 2AED")
  Pringles=116
  print("116 - Pringles            - 2AED")
  Lays= 117
  print("117 - Lays                - 1AED")
  Buggles=  118
  print("118 - Buggles             - 1AED")
  Pofak= 119
  print("119 - Pofak               - 1AED"+'\033[0m')
  choice=int(input("  Type a product code to continue... "))

if choice== Cheetos:
      print('\033[94m'+" ~ Great! You have chosen Cheetos ~ ")
      print("Please Pay 2 AED"+'\033[0m')
      y=float(input("Please insert the money.."))
      Cheetos = 2
      if y > Cheetos:
          print("Here is your change :  ",y - Cheetos)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
      elif y< Cheetos:
           print('\033[91m'+"please enter enough money"+'\033[0m')
           print('\033[91m'+"Your money is refunded "+'\033[0m')
      elif y==Cheetos:
          print('\033[94m'+"Here is your item...")
          print("Thankyou for the purchase, have a good day!"+'\033[0m')

if choice== Pringles:
      print('\033[94m'+" ~ Great! You have chosen Pringles ~ ")
      print("Please Pay 2 AED"+'\033[0m')
      y=float(input("Please insert the money.."))
      Pringles = 2
      if y > Pringles:
          print("Here is your change :  ",y - Pringles)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
      elif y< Pringles:
        print('\033[91m'+"please enter enough money"+'\033[0m')
        print('\033[91m'+"Your money is refunded "+'\033[0m')
      elif y==Pringles:
       print('\033[94m'+"Here is your item...")
       print("Thankyou for the purchase, have a good day!"+'\033[0m')

if choice== Lays:
      print('\033[94m'+" ~ Great! You have chosen Lays ~ ")
      print("Please Pay 1 AED"+'\033[0m')
      y=float(input("Please insert the money.."))
      Lays = 1
      if y > Lays:
          print("Here is your change : ",y - Lays)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
      elif y< Lays:
         print('\033[91m'+"please enter enough money"+'\033[0m')
         print('\033[91m'+"Your money is refunded "+'\033[0m')
      elif y==Lays:
        print('\033[94m'+"Here is your item...")
        print("Thankyou for the purchase, have a good day!"+'\033[0m')

if choice== Buggles:
      print('\033[94m'+" ~ Great! You have chosen Buggles ~ ")
      print("Please Pay 1 AED"+'\033[0m')
      y=float(input("Please insert the money.."))
      Buggles = 1
      if y > Buggles:
          print("Here is your change :  ",y - Buggles)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
      elif y< Buggles:
         print('\033[91m'+"please enter enough money"+'\033[0m')
         print('\033[91m'+"Your money is refunded "+'\033[0m')
      elif y==Buggles:
        print('\033[94m'+"Here is your item...")
        print("Thankyou for the purchase, have a good day!"+'\033[0m')

if choice== Pofak:
      print('\033[94m'+" ~ Great! You have chosen Pofak ~ ")
      print("Please Pay 1 AED"+'\033[0m')
      y=float(input("Please insert the money.."))
      Pofak = 1
      if y > Pofak:
          print("Here is your change : ",y - Pofak)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
      elif y< Pofak:
         print('\033[91m'+"please enter enough money"+'\033[0m')
         print('\033[91m'+"Your money is refunded "+'\033[0m')
      elif y==Pofak:
        print('\033[94m'+"Here is your item...")
        print("Thankyou for the purchase, have a good day!"+'\033[0m')  
 

#ICECREAMS

if choice== Ice_creams:
  print ('\033[94m'+" ~ You have selected Ice_creams ~ "+'\033[0m')
  print(" {{ Here are the list of Icecream Flavours available }}")
  
  Vanilla= 120
  print('\033[92m'+"120 - Vanilla               - 2AED")
  Chocolate= 121
  print("121 - Chocolate             - 2AED")
  Strawberry=122
  print("122 - Strawberry            - 3AED")
  Coffee= 123
  print("123 - Coffee                - 3AED")
  Mango=  124
  print("124 - Mango                 - 3AED")
  Avocado= 125
  print("125 - Avocado               - 3AED"+'\033[0m')
  choice=int(input("  Type a product code to continue... "))


if choice== Vanilla:
  print('\033[94m'+" ~ Great! You have chosen Vanilla ~ ")
  print("Please Pay 2 AED"+'\033[0m')
  y=float(input("Insert the money.."))
  Vanilla = 2
  if y > Vanilla:
      print("Here is your change: ",y - Vanilla)
      print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
  elif y< Vanilla:
       print('\033[91m'+"please enter enough money"+'\033[0m')
       print('\033[91m'+"Your money is refunded "+'\033[0m')
      
  elif y==Vanilla:
      print('\033[94m'+"Here is your item...")
      print("Thankyou for the purchase, have a good day!"+'\033[0m')
 
if choice== Chocolate:
      print('\033[94m'+" ~ Great! You have chosen Chocolate ~ ")
      print("Please Pay 2 AED"+'\033[0m')
      y=float(input("Please insert the money.."))
      Chocolate = 2
      if y > Chocolate:
          print("Here is your change :  ",y - Chocolate)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
      elif y< Chocolate:
           print('\033[91m'+"please enter enough money"+'\033[0m')
           print('\033[91m'+"Your money is refunded "+'\033[0m')
      elif y==Chocolate:
          print('\033[94m'+"Here is your item...")
          print("Thankyou for the purchase, have a good day!"+'\033[0m')

if choice== Strawberry:
      print('\033[94m'+" ~ Great! You have chosen Strawberry ~ ")
      print("Please Pay 3 AED"+'\033[0m')
      y=float(input("Please insert the money.."))
      Strawberry = 3
      if y > Strawberry:
          print("Here is your change :  ",y - Strawberry)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
      elif y< Strawberry:
        print('\033[91m'+"please enter enough money"+'\033[0m')
        print('\033[91m'+"Your money is refunded "+'\033[0m')
      elif y==Strawberry:
       print('\033[94m'+"Here is your item...")
       print("Thankyou for the purchase, have a good day!"+'\033[0m')

if choice== Coffee:
      print('\033[94m'+" ~ Great! You have chosen Coffee ~ ")
      print("Please Pay 3 AED"+'\033[0m')
      y=float(input("Please insert the money.."))
      Coffee= 3
      if y > Coffee:
          print("Here is your change : ",y -Coffee)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
      elif y< Coffee:
         print('\033[91m'+"please enter enough money"+'\033[0m')
         print('\033[91m'+"Your money is refunded "+'\033[0m')
      elif y==Coffee:
        print('\033[94m'+"Here is your item...")
        print("Thankyou for the purchase, have a good day!"+'\033[0m')

if choice== Mango:
      print('\033[94m'+" ~ Great! You have chosen Mango ~ ")
      print("Please Pay 3 AED"+'\033[0m')
      y=float(input("Please insert the money.."))
      Mango = 3
      if y > Mango:
          print("Here is your change :  ",y - Mango)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
      elif y< Mango:
         print('\033[91m'+"please enter enough money"+'\033[0m')
         print('\033[91m'+"Your money is refunded "+'\033[0m')
      elif y==Mango:
        print('\033[94m'+"Here is your item...")
        print("Thankyou for the purchase, have a good day!"+'\033[0m')

if choice== Avocado:
      print('\033[94m'+" ~ Great! You have chosen Avocado ~ ")
      print("Please Pay 3 AED"+'\033[0m')
      y=float(input("Please insert the money.."))
      Avocado = 3
      if y > Avocado:
          print("Here is your change : ",y - Avocado)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
      elif y< Avocado:
         print('\033[91m'+"please enter enough money"+'\033[0m')
         print('\033[91m'+"Your money is refunded "+'\033[0m')
      elif y==Avocado:
        print('\033[94m'+"Here is your item...")
        print("Thankyou for the purchase, have a good day!"+'\033[0m') 



#OTHERS

if choice== Other:
  print ('\033[94m'+" ~ You have selected Other ~ "+'\033[0m')
  print(" {{ Here are the list of some Emergency Items }}")
  
  Instant_Ramen= 126
  print('\033[92m'+"126 - Instant_Ramen               - 4AED")
  Sanitary_Napkin= 127
  print("127 - Sanitary_Napkin             - 1AED")
  Plastic_Bag=128
  print("128 - Plastic_Bag                 - 2AED")
  Umbrella= 129
  print("129 - Umbrella                    - 6AED")
  Mask=  130
  print("130 - Mask                        - 1AED")
  choice=int(input("  Type a product code to continue... "))


if choice== Instant_Ramen:
  print('\033[94m'+" ~ Great! You have chosen Instant_Ramen ~ ")
  print("Please Pay 4 AED"+'\033[0m')
  y=float(input("Insert the money.."))
  Instant_Ramen = 4
  if y > Instant_Ramen:
      print("Here is your change: ",y - Instant_Ramen)
      print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
  elif y< Instant_Ramen:
       print('\033[91m'+"please enter enough money"+'\033[0m')
       print('\033[91m'+"Your money is refunded "+'\033[0m')
      
  elif y==Instant_Ramen:
      print('\033[94m'+"Here is your item...")
      print("Thankyou for the purchase, have a good day!"+'\033[0m')
 
if choice== Sanitary_Napkin:
      print('\033[94m'+" ~ Great! You have chosen Sanitary_Napkin ~ ")
      print("Please Pay 1 AED"+'\033[0m')
      y=float(input("Please insert the money.."))
      Sanitary_Napkin = 1
      if y > Sanitary_Napkin:
          print("Here is your change :  ",y - Sanitary_Napkin)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
      elif y< Sanitary_Napkin:
           print('\033[91m'+"please enter enough money"+'\033[0m')
           print('\033[91m'+"Your money is refunded "+'\033[0m')
      elif y==Sanitary_Napkin:
          print('\033[94m'+"Here is your item...")
          print("Thankyou for the purchase, have a good day!"+'\033[0m')

if choice== Plastic_Bag:
      print('\033[94m'+" ~ Great! You have chosen Plastic_Bag~ ")
      print("Please Pay 2 AED"+'\033[0m')
      y=float(input("Please insert the money.."))
      Plastic_Bag = 2
      if y > Plastic_Bag:
          print("Here is your change :  ",y - Plastic_Bag)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
      elif y< Plastic_Bag:
        print('\033[91m'+"please enter enough money"+'\033[0m')
        print('\033[91m'+"Your money is refunded "+'\033[0m')
      elif y==Plastic_Bag:
       print('\033[94m'+"Here is your item...")
       print("Thankyou for the purchase, have a good day!"+'\033[0m')

if choice== Umbrella:
      print('\033[94m'+" ~ Great! You have chosen Umbrella ~ ")
      print("Please Pay 6 AED"+'\033[0m')
      y=float(input("Please insert the money.."))
      Umbrella= 6
      if y > Umbrella:
          print("Here is your change : ",y -Umbrella)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
      elif y< Umbrella:
         print('\033[91m'+"please enter enough money"+'\033[0m')
         print('\033[91m'+"Your money is refunded "+'\033[0m')
      elif y==Umbrella:
        print('\033[94m'+"Here is your item...")
        print("Thankyou for the purchase, have a good day!"+'\033[0m')

if choice== Mask:
      print('\033[94m'+" ~ Great! You have chosen Mask ~ ")
      print("Please Pay 1 AED"+'\033[0m')
      y=float(input("Please insert the money.."))
      Mask= 1
      if y > Mask:
          print("Here is your change :  ",y - Mask)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
      elif y< Mask:
         print('\033[91m'+"please enter enough money"+'\033[0m')
         print('\033[91m'+"Your money is refunded "+'\033[0m')
      elif y==Mask:
        print('\033[94m'+"Here is your item...")
        print("Thankyou for the purchase, have a good day!"+'\033[0m')