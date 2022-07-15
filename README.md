from random import randint

answer= randint(1,20)

guess_as_str = input("Guess a number: ")
guess = int(guess_as_str)

while guess != answer:
    
    if guess < answer:
        print("Too small!")
    else:
        print("Too big")
    guess_as_str = input("Guess a number: ")
    guess = int(guess_as_str)
    

    print("Brawo")
