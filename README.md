# tapsiriglar
choise=["rock","paper","scissors"]
player1=input("choose:")
player2=input("choose:")
if player1==player2:
    print("its a tie")
elif (player1 == "rock" and player2 == "scissors"):
    print("player1 won")
elif (player1 == "scissors" and player2 == "paper" ):
    print("player1 won")
elif (player1 == "paper" and player2 == "rock"):
    print("player 1 won")
else:
    print("player2 won")