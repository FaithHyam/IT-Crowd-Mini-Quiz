print("Welcome to my IT Crowd mini quiz!")

playing = input ("Do you want to play? ")

if playing.lower() != "yes":
    quit()

print("Great! Let's play! :)")
score = 0

answer = input("What does Moss often confuse with fire? ")
if answer.lower() == "golf":
    print("Correct!")
    score = score + 1
else:
    print("Incorrect!")

answer = input("How many miles does Denholm cycle to work everyday? ")
if answer.lower() == "70":
    print("Correct!")
    score = score + 1
else:
    print("Incorrect!")

answer = input("What are the first four digits of the new number for 999 (providing more attractive service)? ")
if answer.lower() == "0118":
    print("Correct!")
    score = score + 1
else:
    print("Incorrect!")

answer = input("What day is Roy predicted to die on after taking a mortality quiz? ")
if answer.lower() == "thursday":
    print("Correct!")
    score = score + 1
else:
    print("Incorrect!")

answer = input("What word did Moss win the Countdown teapot with? ")
if answer.lower() == "tnetennba":
    print("Correct!")
    score = score + 1
else:
    print("Incorrect!")

answer = input("What colour is the door that Richmond lives behind? ")
if answer.lower() == "red":
    print("Correct!")
    score = score + 1
else:
    print("Incorrect!")

print("You got " + str(score) + " questions correct!")
print("That's " + str((score/6) * 100) + " %!")
