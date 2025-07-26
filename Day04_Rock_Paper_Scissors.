import random

rock = '''
    _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)
'''

paper = '''
    _______
---'   ____)____
          ______)
          _______)
         _______)
---.__________)
'''

scissors = '''
    _______
---'   ____)____
          ______)
       __________)
      (____)
---.__(___)
'''

game_images = [rock, paper, scissors]

print ("Welcome to Rock, Paper and Scissor game")

user_choice = int(input("What do you choose? Type 0 for Rock, 1 for Paper or 2 for Scissors.\n"))
computer_choice = random.randint(0, 2)

print("Your choice:")

if user_choice >= 0 and user_choice <= 2:
    print(game_images[user_choice])

print("Computer's choice:")

print(game_images[computer_choice])

if user_choice > 2 or user_choice < 0:
    print("It's an invalid entry. you lost")
elif user_choice == computer_choice:
    print("It's a draw")
elif user_choice == 2 and computer_choice == 0:
    print("You lost")
elif user_choice == 0 and computer_choice == 2:
    print("You won")
elif user_choice > computer_choice:
    print("You won")
elif computer_choice > user_choice:
    print("You lost")
