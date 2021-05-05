import random


def play():

    print("Best of 3")

    user_score = 0
    computer_score = 0

    sets = [1,2,3]

    for _ in sets:
        print("")
        computer_choice = int(random.randint(1, 3))
        user_choice = int(input("1 for Rock, 2 for Paper or 3 for scissors - "))

        while computer_choice != user_choice:
            if computer_choice > user_choice:
                print("computer wins this round")
                computer_score += 1
                break
            else:
                print("you win this round")
                user_score += 1
                break
        else:
            print("It's a Tie!")
            sets.append(+1)

    if user_score > computer_score:
        print("You Won!")
    else:
        print("Computer Won!")

    print("")
    play_again = input("play again? - ")
    if play_again == "yes":
        play()
    else:
        exit()


play()
