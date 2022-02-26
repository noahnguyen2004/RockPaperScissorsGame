# rock paper scissors game
# Type 0 for Rock, 1 for Paper, or 2 for Scissors

import random
print("Welcome to the Rock Paper Scissors Game!")
user_choice = input("What do you choose? Type 0 for Rock, 1 for Paper or 2 for Scissors\n")
int_user_choice = int(user_choice)
comp_random = random.randint(0, 2)
rock = '''   _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)'''
paper = ''' _______
---'   ____)____
          ______)
          _______)
         _______)
---.__________)'''
scissors = ''' _______
---'   ____)____
          ______)
       __________)
      (____)
---.__(___)'''

game_images = [rock, paper, scissors]
if int_user_choice == 0:        # 0 = rock
    print(game_images[0])
    print("\nComputer choice:\n")
    if comp_random == 0:
        print(game_images[0])
        print("You draw!")
    elif comp_random == 1:
        print(game_images[1])
        print("You lose!")
    else:
        print(game_images[2])
        print("You win!")
elif int_user_choice == 1:      # 1 = paper
    print(game_images[1])
    print("\nComputer choice:\n")
    if comp_random == 0:
        print(game_images[0])
        print("You win!")
    elif comp_random == 1:
        print(game_images[1])
        print("You draw!")
    else:
        print(game_images[2])
        print("You lose!")
else:                           # 2 = scissors
    print(game_images[2])
    print("\nComputer choice:\n")
    if comp_random == 0:
        print(game_images[0])
        print("You lose!")
    elif comp_random == 1:
        print(game_images[1])
        print("You win!")
    else:
        print(game_images[2])
        print("You draw!")







