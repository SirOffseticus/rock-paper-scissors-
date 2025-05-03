from getpass import getpass as input
print("Rock, Paper, Scissors, Shoot!")
print("Type Q to quit anytime.")
user1_score = 0
user2_score = 0
score = 0
R = "R"
P = "P"
S = "S"
move = "R" , "P" , "S"
user1 = "user1"
user2 = "user2"
while user1_score < 3 and user2_score < 3:
    user1 = input("user1 make your move: \n")
    user2 = input("user2 make your move: \n")
    user1 = input("user1 make your move: \n")
    if user1 == "Q":
        break
    user2 = input("user2 make your move: \n")
    if user2 == "Q":
        break
    if user1 not in move or user2 not in move:
        print("Invalid move, try again.")
        continue
    if (user1 == "R" and user2  == "S" or user1 == "S" and user2 == "P" or user1 == "P" and user2 == "R"):
        print("user1 wins")
        user1_score += 1
    elif (user2 == "R" and user1 == "S" or user2 == "S" and user1 == "P" or user2 == "P" and user1 == "R"):
        print("user2 wins")
        user2_score += 1
    if user1 == user2:
        print("it's a tie.")
wins = +1
score = user1_score + wins
score = user2_score + wins
if user1_score or user2_score >= 3:
    print("Game Over!")
    print("user1 score is,", user1_score)
    print("user2 score is,", user2_score)
if user1_score > user2_score:
    print("user1 wins!")
else:
    print("user2 wins!")

exit()
