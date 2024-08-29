secret_key = 100
guess_count = 0      #initialization
guess_limit = 3      # condition check number

while guess_count < guess_limit:
    guess = int(input("Guess a number: "))
    guess_count += 1

    if guess == secret_key:
        print("Congratulations! You guessed the correct number!")
        break


    else:
        print("Sorry, you guessed the wrong number!")
        print("Guess again!")

