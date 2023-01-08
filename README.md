[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=9694213&assignment_repo_type=AssignmentRepo)

#displaying the item info
while True:
  print( '\033[1m'+ 'WELCOME TO THE')
  print('\033[1m'+'COMBO-VENDING EXPRESS!!'+'\033[0m')
  print('\033[1m' +'\033[92m'+ 'HERE IS THE MENU' + '\033[0m' )

  Candy= 1001
  print('\033[92m'+ "1001 - Candy")
  Drinks= 2001
  print("2001 - Drinks")
  Ice_creams= 3001
  print("3001 - Ice_creams")
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
    elif choice== Gumballs:
      print('\033[94m'+" ~ Great! You have chosen Gumballs ~ ")
      print("Please Pay 2 AED"+'\033[0m')
    elif choice== Dairymilk:
      print('\033[94m'+" ~ Great! You have chosen Dairymilk ~ ")
      print("Please Pay 2 AED"+'\033[0m')
    elif choice== Snickers:
      print('\033[94m'+" ~ Great! You have chosen Snickers ~ ")
      print("Please Pay 3 AED"+'\033[0m')
    elif choice== Galaxy:
      print('\033[94m'+" ~ Great! You have chosen Galaxy ~ ")
      print("Please Pay 3 AED"+'\033[0m')
    elif choice== Kitkats:
      print('\033[94m'+" ~ Great! You have chosen Kitkats ~ ")
      print("Please Pay 3 AED"+'\033[0m')

  if choice==Skittles:
    money_candy=float(input("Please insert the money"))
    Candy_price=1
    Candy_change=money_candy-Candy_price
    while True:
      if money_candy==Candy_price:
        print('\033[94m'+"Here is your item...")
        print("Thankyou for the purchase, have a good day!"+'\033[0m')
        break
      elif money_candy>Candy_price:
        print("Here is your change : ")
        print(Candy_change)
        print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
        break
      else:
        print('\033[91m'+"please enter enough money"+'\033[0m')
        moneyagain_candy=float(input("please insert money again"))
        if moneyagain_candy + money_candy==Candy_price:
          print('\033[94m'+"Here is your item...")
          print("Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        break

  if choice==Gumballs:
      money_Gumballs=float(input("Please insert the money"))
      Gumballs_price=2
      Gumballs_change=money_Gumballs-Gumballs_price
      while True:
        if money_Gumballs==Gumballs_price:
          print('\033[94m'+"Here is your item...")
          print("Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        elif money_Gumballs>Gumballs_price:
          print("Here is your change : ")
          print(Gumballs_change)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        else:
          print('\033[91m'+"please enter enough money"+'\033[0m')
          moneyagain_Gumballs=float(input("please insert money again"))
          if moneyagain_Gumballs + money_Gumballs==Gumballs_price:
            print('\033[94m'+"Here is your item...")
            print("Thankyou for the purchase, have a good day!"+'\033[0m')
            break
          break

    
  if choice==Dairymilk:
      money_Dairymilk=float(input("Please insert the money"))
      Dairymilk_price=2
      Dairymilk_change=money_Dairymilk-Dairymilk_price
      while True:
        if money_Dairymilk==Dairymilk_price:
          print('\033[94m'+"Here is your item...")
          print("Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        elif money_Dairymilk>Dairymilk_price:
          print("Here is your change : ")
          print(Dairymilk_change)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        else:
          print('\033[91m'+"please enter enough money"+'\033[0m')
          moneyagain_Dairymilk=float(input("please insert money again"))
          if moneyagain_Dairymilk + money_Dairymilk==Dairymilk_price:
            print('\033[94m'+"Here is your item...")
            print("Thankyou for the purchase, have a good day!"+'\033[0m')
            break
          break

  if choice==Snickers:
    money_Snickers=float(input("Please insert the money"))
    Snickers_price=3
    Snickers_change=money_Snickers-Snickers_price
    while True:
      if money_Snickers==Snickers_price:
        print('\033[94m'+"Here is your item...")
        print("Thankyou for the purchase, have a good day!"+'\033[0m')
        break
      elif money_Snickers>Snickers_price:
        print("Here is your change : ")
        print(Snickers_change)
        print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
        break
      else:
        print('\033[91m'+"please enter enough money"+'\033[0m')
        moneyagain_Snickers=float(input("please insert money again"))
        if moneyagain_Snickers + money_Snickers==Snickers_price:
          print('\033[94m'+"Here is your item...")
          print("Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        break

  if choice==Galaxy:
    money_Galaxy=float(input("Please insert the money"))
    Galaxy_price=3
    Galaxy_change=money_Galaxy-Galaxy_price
    while True:
      if money_Galaxy==Galaxy_price:
        print('\033[94m'+"Here is your item...")
        print("Thankyou for the purchase, have a good day!"+'\033[0m')
        break
      elif money_Galaxy>Galaxy_price:
        print("Here is your change : ")
        print(Galaxy_change)
        print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
        break
      else:
        print('\033[91m'+"please enter enough money"+'\033[0m')
        moneyagain_Galaxy=float(input("please insert money again"))
        if moneyagain_Galaxy + money_Galaxy==Galaxy_price:
          print('\033[94m'+"Here is your item...")
          print("Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        break

  if choice==Kitkats:
    money_Kitkats=float(input("Please insert the money"))
    Kitkats_price=3
    Kitkats_change=money_Kitkats-Kitkats_price
    while True:
      if money_Kitkats==Kitkats_price:
        print('\033[94m'+"Here is your item...")
        print("Thankyou for the purchase, have a good day!"+'\033[0m')
        break
      elif money_Kitkats>Kitkats_price:
        print("Here is your change : ")
        print(Kitkats_change)
        print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
        break
      else:
        print('\033[91m'+"please enter enough money"+'\033[0m')
        moneyagain_Kitkats=float(input("please insert money again"))
        if moneyagain_Kitkats + money_Kitkats==Kitkats_price:
          print('\033[94m'+"Here is your item...")
          print("Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        break

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

    if choice== Water:
      print('\033[94m'+" ~ Great! You have chosen Water ~ ")
      print("Please Pay 1 AED"+'\033[0m')
    elif choice== MountainDew:
      print('\033[94m'+" ~ Great! You have chosen MountainDew ~ ")
      print("Please Pay 3 AED"+'\033[0m')
    elif choice== Pepsi:
      print('\033[94m'+" ~ Great! You have chosen Pepsi ~ ")
      print("Please Pay 3 AED"+'\033[0m')
    elif choice== ColdCoffee:
      print('\033[94m'+" ~ Great! You have chosen ColdCoffee ~ ")
      print("Please Pay 3 AED"+'\033[0m')
    elif choice== Sprite:
      print('\033[94m'+" ~ Great! You have chosen Sprite ~ ")
      print("Please Pay 3 AED"+'\033[0m')
    elif choice== Coke:
      print('\033[94m'+" ~ Great! You have chosen Coke ~ ")
      print("Please Pay 3 AED"+'\033[0m')
    
  if choice==Water:
    money_Water=float(input("Please insert the money"))
    Water_price=1
    Water_change=money_Water-Water_price
    while True:
      if money_Water==Water_price:
        print('\033[94m'+"Here is your item...")
        print("Thankyou for the purchase, have a good day!"+'\033[0m')
        break
      elif money_Water>Water_price:
        print("Here is your change : ")
        print(Water_change)
        print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
        break
      else:
        print('\033[91m'+"please enter enough money"+'\033[0m')
        moneyagain_Water=float(input("please insert money again"))
        if moneyagain_Water + money_Water==Water_price:
          print('\033[94m'+"Here is your item...")
          print("Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        break

  if choice==MountainDew:
      money_MountainDew=float(input("Please insert the money"))
      MountainDew_price=3
      MountainDew_change=money_MountainDew-MountainDew_price
      while True:
        if money_MountainDew==MountainDew_price:
          print('\033[94m'+"Here is your item...")
          print("Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        elif money_MountainDew>MountainDew_price:
          print("Here is your change : ")
          print(MountainDew_change)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        else:
          print('\033[91m'+"please enter enough money"+'\033[0m')
          moneyagain_MountainDew=float(input("please insert money again"))
          if moneyagain_MountainDew + money_MountainDew==MountainDew_price:
            print('\033[94m'+"Here is your item...")
            print("Thankyou for the purchase, have a good day!"+'\033[0m')
            break
          break

  if choice==Pepsi:
      money_Pepsi=float(input("Please insert the money"))
      Pepsi_price=3
      Pepsi_change=money_Pepsi-Pepsi_price
      while True:
        if money_Pepsi==Pepsi_price:
          print('\033[94m'+"Here is your item...")
          print("Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        elif money_Pepsi>Pepsi_price:
          print("Here is your change : ")
          print(Pepsi_change)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        else:
          print('\033[91m'+"please enter enough money"+'\033[0m')
          moneyagain_Pepsi=float(input("please insert money again"))
          if moneyagain_Pepsi + money_Pepsi==Pepsi_price:
            print('\033[94m'+"Here is your item...")
            print("Thankyou for the purchase, have a good day!"+'\033[0m')
            break
          break

  if choice==ColdCoffee:
      money_ColdCoffee=float(input("Please insert the money"))
      ColdCoffee_price=3
      ColdCoffee_change=money_ColdCoffee-ColdCoffee_price
      while True:
        if money_ColdCoffee==ColdCoffee_price:
          print('\033[94m'+"Here is your item...")
          print("Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        elif money_ColdCoffee>ColdCoffee_price:
          print("Here is your change : ")
          print(ColdCoffee_change)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        else:
          print('\033[91m'+"please enter enough money"+'\033[0m')
          moneyagain_ColdCoffee=float(input("please insert money again"))
          if moneyagain_ColdCoffee + money_ColdCoffee==ColdCoffee_price:
            print('\033[94m'+"Here is your item...")
            print("Thankyou for the purchase, have a good day!"+'\033[0m')
            break
          break

  if choice==Sprite:
      money_Sprite=float(input("Please insert the money"))
      Sprite_price=3
      Sprite_change=money_Sprite-Sprite_price
      while True:
        if money_Sprite==Sprite_price:
          print('\033[94m'+"Here is your item...")
          print("Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        elif money_Sprite>Sprite_price:
          print("Here is your change : ")
          print(Sprite_change)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        else:
          print('\033[91m'+"please enter enough money"+'\033[0m')
          moneyagain_Sprite=float(input("please insert money again"))
          if moneyagain_Sprite + money_Sprite==Sprite_price:
            print('\033[94m'+"Here is your item...")
            print("Thankyou for the purchase, have a good day!"+'\033[0m')
            break
          break

  if choice==Coke:
      money_Coke=float(input("Please insert the money"))
      Coke_price=3
      Coke_change=money_Coke-Coke_price
      while True:
        if money_Coke==Coke_price:
          print('\033[94m'+"Here is your item...")
          print("Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        elif money_Coke>Coke_price:
          print("Here is your change : ")
          print(Coke_change)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        else:
          print('\033[91m'+"please enter enough money"+'\033[0m')
          moneyagain_Coke=float(input("please insert money again"))
          if moneyagain_Coke + money_Coke==Coke_price:
            print('\033[94m'+"Here is your item...")
            print("Thankyou for the purchase, have a good day!"+'\033[0m')
            break
          break

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
    elif choice== Chocolate:
      print('\033[94m'+" ~ Great! You have chosen Chocolate ~ ")
      print("Please Pay 2 AED"+'\033[0m')
    elif choice== Strawberry:
      print('\033[94m'+" ~ Great! You have chosen Strawberry ~ ")
      print("Please Pay 3 AED"+'\033[0m')
    elif choice== Coffee:
      print('\033[94m'+" ~ Great! You have chosen Coffee ~ ")
      print("Please Pay 3 AED"+'\033[0m')
    elif choice== Mango:
      print('\033[94m'+" ~ Great! You have chosen Mango ~ ")
      print("Please Pay 3 AED"+'\033[0m')
    elif choice== Avocado:
      print('\033[94m'+" ~ Great! You have chosen Avocado ~ ")
      print("Please Pay 3 AED"+'\033[0m')

  if choice==Vanilla:
      money_Vanilla=float(input("Please insert the money"))
      Vanilla_price=2
      Vanilla_change=money_Vanilla-Vanilla_price
      while True:
        if money_Vanilla==Vanilla_price:
          print('\033[94m'+"Here is your item...")
          print("Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        elif money_Vanilla>Vanilla_price:
          print("Here is your change : ")
          print(Vanilla_change)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        else:
          print('\033[91m'+"please enter enough money"+'\033[0m')
          moneyagain_Vanilla=float(input("please insert money again"))
          if moneyagain_Vanilla + money_Vanilla==Vanilla_price:
            print('\033[94m'+"Here is your item...")
            print("Thankyou for the purchase, have a good day!"+'\033[0m')
            break
          break

  if choice==Chocolate:
      money_Chocolate=float(input("Please insert the money"))
      Chocolate_price=2
      Chocolate_change=money_Chocolate-Chocolate_price
      while True:
        if money_Chocolate==Chocolate_price:
          print('\033[94m'+"Here is your item...")
          print("Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        elif money_Chocolate>Chocolate_price:
          print("Here is your change : ")
          print(Chocolate_change)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        else:
          print('\033[91m'+"please enter enough money"+'\033[0m')
          moneyagain_Chocolate=float(input("please insert money again"))
          if moneyagain_Chocolate + money_Chocolate==Chocolate_price:
            print('\033[94m'+"Here is your item...")
            print("Thankyou for the purchase, have a good day!"+'\033[0m')
            break
          break

  if choice==Strawberry:
      money_Strawberry=float(input("Please insert the money"))
      Strawberry_price=3
      Strawberry_change=money_Strawberry-Strawberry_price
      while True:
        if money_Strawberry==Strawberry_price:
          print('\033[94m'+"Here is your item...")
          print("Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        elif money_Strawberry>Strawberry_price:
          print("Here is your change : ")
          print(Strawberry_change)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        else:
          print('\033[91m'+"please enter enough money"+'\033[0m')
          moneyagain_Strawberry=float(input("please insert money again"))
          if moneyagain_Strawberry + money_Strawberry==Strawberry_price:
            print('\033[94m'+"Here is your item...")
            print("Thankyou for the purchase, have a good day!"+'\033[0m')
            break
          break

  if choice==Coffee:
      money_Coffee=float(input("Please insert the money"))
      Coffee_price=3
      Coffee_change=money_Coffee-Coffee_price
      while True:
        if money_Coffee==Coffee_price:
          print('\033[94m'+"Here is your item...")
          print("Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        elif money_Coffee>Coffee_price:
          print("Here is your change : ")
          print(Coffee_change)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        else:
          print('\033[91m'+"please enter enough money"+'\033[0m')
          moneyagain_Coffee=float(input("please insert money again"))
          if moneyagain_Coffee + money_Coffee==Coffee_price:
            print('\033[94m'+"Here is your item...")
            print("Thankyou for the purchase, have a good day!"+'\033[0m')
            break
          break

  if choice==Mango:
      money_Mango=float(input("Please insert the money"))
      Mango_price=3
      Mango_change=money_Mango-Mango_price
      while True:
        if money_Mango==Mango_price:
          print('\033[94m'+"Here is your item...")
          print("Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        elif money_Mango>Mango_price:
          print("Here is your change : ")
          print(Mango_change)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        else:
          print('\033[91m'+"please enter enough money"+'\033[0m')
          moneyagain_Mango=float(input("please insert money again"))
          if moneyagain_Mango + money_Mango==Mango_price:
            print('\033[94m'+"Here is your item...")
            print("Thankyou for the purchase, have a good day!"+'\033[0m')
            break
          break

  if choice==Avocado:
      money_Avocado=float(input("Please insert the money"))
      Avocado_price=3
      Avocado_change=money_Avocado-Avocado_price
      while True:
        if money_Avocado==Avocado_price:
          print('\033[94m'+"Here is your item...")
          print("Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        elif money_Avocado>Avocado_price:
          print("Here is your change : ")
          print(Avocado_change)
          print('\033[94m'+"Thankyou for the purchase, have a good day!"+'\033[0m')
          break
        else:
          print('\033[91m'+"please enter enough money"+'\033[0m')
          moneyagain_Avocado=float(input("please insert money again"))
          if moneyagain_Avocado + money_Avocado==Avocado_price:
            print('\033[94m'+"Here is your item...")
            print("Thankyou for the purchase, have a good day!"+'\033[0m')
            break
          break

  

  

  order=str(input("Do you want to order again? (1-yes/0-no) : "))
  if order=="0":
    break
  else:
   continue
