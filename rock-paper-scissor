# rock paper scissor
import random
print('ROCK, PAPER, SCISSORS')
win = 0
lose = 0
tie = 0
#print("%s win %s lose %s tie"%(win,lose,tie))

while True:
    #c_move = ['r','p','s'] this line probably not in use
    r_move = random.randint(1,3)
    print("%s win %s lose %s tie"%(win,lose,tie))
    print("\n")
    p_move = input("enter move (r)ock (p)aper (s)cissor or (q)uit :")
    print("\n")

    if p_move == "r":
        print('ROCK VS ....')
    elif p_move == "p":
        print("PAPER VS ....")
    elif p_move == 's':
        print("SCISSOR VS ...")
    elif p_move == "q":
        print("thank you for playing")
        break
    else:
        print("please enter correct option")
        
    if r_move == 1:
        print("ROCK")
    elif r_move == 2:
        print("PAPER")
    elif r_move == 3:
        print("SCISSOR")
    else:
        print("!!")
    print("\n")

    if (p_move == "r") and (r_move == 1):
        print("tie")
        tie += 1
    elif (p_move == "r") and (r_move == 2):
        print("win")
        win += 1
    elif (p_move == "r") and (r_move == 3):
        print("win")
        win += 1
    elif (p_move == "p") and (r_move == 1):
        print("lose")
        lose += 1
    elif (p_move == "p") and (r_move == 2):
        print("tie")
        tie += 1
    elif (p_move == "p") and (r_move == 3):
        print("lose")
        lose += 1
    elif (p_move == "s") and (r_move == 1):
        print("lose")
        lose += 1
    elif (p_move == "s") and (r_move == 2):
        print("win")
        win += 1
    elif (p_move == "s") and (r_move == 3):
        print("tie")
        tie += 1
    else:
        pass
"""created by atul"""
