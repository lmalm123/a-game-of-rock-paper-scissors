valid_choices = ("rock" "paper" "scissors").lower()


while True:
    player1 = input("player1, pls choose rock,paper,scissors:").lower()
    if player1 in valid_choices:
    
        break
else: 
    print("invalid choice, pls only input valid choices")


while True:
    player2 = input("player2, pls choose rock,paper,scissors:").lower()
    if player2 in valid_choices:
    
        break
else: 
    print("invalid choice, pls only input valid choices")

if player1 == player2:
      print("its a draw!")

elif player1 == "rock" and player2 == "scissors":
      print("player 1 wins!")
      
elif player1 =="rock" and player2 =="paper":
      print("player2 wins!")

elif player1 == "scissors" and player2 =="paper":
      print("player1 wins!")
