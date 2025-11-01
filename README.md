#NumberGuesser-Game-Algorithm
Project Author: Blessing Adeyemi
Version: 1.0
Project Reviewer: Ireti George

##About Game
This is a number guessing game to guess a randomly generated number between 0-10.
It is presented in an algorithmic and a pseudocode format

##Algorithm

1. Create a random number called randomNumber
2. read user input and store it as UserGuess
3. If UserGuess is not between 0 and 10:
   i. show message "Please input a valid number between 0-10
   ii. Go back to step 2
   else:
   i. if userGuess = randomNumber:
   show message "Hooray! You guessed correctly"
   exit program
   else:
   show message "Guess incorrect"
   Go back to step 2

##PSEUDOCODE-ISH
randomNumber = random(0-10)
isEqual = False

do{
userGuess = readInput()

if(userGuess is not number || (userGuess < 0 || >10)):

    showMessage("Please input a valid number between 0 and 10")

else:

    if (UserGuess = randomNumber):
      isEqual == True
    else if (UserGuess < randomNumber):
      showMessage("Your guess is lower, try again")
    else if (UserGuess > randomNumber):
      showMessage("Your guess is too high, try again")

} while (isEqual = False)

showMessage("Hooray! You have guessed correctly and won 200 naira")
End of program
