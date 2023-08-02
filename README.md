# python
بازی سنگ کاغذ قیچی
import random

print("rock")     # سنگ
print("peper")    # کاغذ
print("scissor")  # قیچی

randomnumber = random.randint(0, 2)
cumputer = "rock"

if randomnumber == 0:
    computer = "rock"
elif randomnumber == 1:
    computer == "peper"
elif randomnumber == 2:
    computer = "scissor"

player1 = input("Enter player 1 :").lower()
print(f"Enter player 2 :{computer}")
player2 = computer

if player1 == player2:
    print("The game is equal")  # بازی مساوی است
elif player1 == "rock" and player2 == "peper":
    print("Player 2 wins the game")
elif player1 == "rock" and player2 == "scissor":
    print("Player 1 wins the game")
elif player1 == "peper" and player2 == "rock":
    print("Player 1 wins the game")
elif player1 == "peper" and player2 == "scissor":
    print("Player 2 wins the game")
elif player1 == "scissor" and player2 == "rock":
    print("Player 2 wins the game")
elif player1 == "scissor" and player2 == "peper":
    print("Player 1 wins the game")
else:
    print("You made a mistake...")
