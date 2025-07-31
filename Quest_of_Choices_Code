print('''
*******************************************************************************
          |                   |                  |                     |
 _________|________________.=""_;=.______________|_____________________|_______
|                   |  ,-"_,=""     `"=.|                  |
|___________________|__"=._o`"-._        `"=.______________|___________________
          |                `"=._o`"=._      _`"=._                     |
 _________|_____________________:=._o "=._."_.-="'"=.__________________|_______
|                   |    __.--" , ; `"=._o." ,-"""-._ ".   |
|___________________|_._"  ,. .` ` `` ,  `"-._"-._   ". '__|___________________
          |           |o`"=._` , "` `; .". ,  "-._"-._; ;              |
 _________|___________| ;`-.o`"=._; ." ` '`."\ ` . "-._ /_______________|_______
|                   | |o ;    `"-.o`"=._``  '` " ,__.--o;   |
|___________________|_| ;     (#) `-.o `"=.`_.--"_o.-; ;___|___________________
____/______/______/___|o;._    "      `".o|o_.--"    ;o;____/______/______/____
/______/______/______/_"=._o--._        ; | ;        ; ;/______/______/______/_
____/______/______/______/__"=._o--._   ;o|o;     _._;o;____/______/______/____
/______/______/______/______/____"=._o._; | ;_.--"o.--"_/______/______/______/_
____/______/______/______/______/_____"=.o|o_.--""___/______/______/______/____
/______/______/______/______/______/______/______/______/______/______/_____ /
*******************************************************************************
''')
print("Welcome to Treasure Island.")
print("Your mission is to find the treasure.")

first_level= input("You have two path right or left.Choose where you want to go.").lower()   # we use lower() to all the input text in lower case
if first_level == "left":
    second_level = input("you have came across the river. Did you want to continue or wait for the boat?").lower()
    if second_level == "wait":
        third_level = input("Congratulation you have reached the last part. Select which colour of door you select? Red , Blue , Yellow .").lower()
        if third_level == "red":
            print("You fell into fire and got burned . Game Over")
        elif third_level == "blue":
            print("You eaten by the beast . ")
        elif third_level == "yellow":
            print("Congratulation you win the game . The treasure is your's . ")
        else:
            print("Game Over")
    else:
        print("You were eaten by crocodile.Game Over")
else:
    print("You have fell into a hole . Game Over")
