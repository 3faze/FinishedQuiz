# FinishedQuiz
Quiz
total = 0
questions = ["Whats his name?", "How old is he?", "Is he my bestie?", "Whats his favourite food?", "Is he dabest?"]

name = input('What is your name?\n')
print('Hello, lets start this, %s!' % name)

question1= input(questions[0])

if question1 == "Santiago" or question1 == "santiago":
    print("oke")
    print("+1")
    total = total + 1
else:
    print("Not really")
    print("+0")
    
question2 = input(questions[1])
    
if question2 == "12":
    print("oke")
    print("+1")
    total = total + 1
else:
    print("Not really")
    print("+0")
    
question3 = input(questions[2])

if question3 == "Yes" or question3 == "yes" or question3 == "Yea" or question3 == "yea":
    print("You're right")
    print("+1")
    total = total + 1
else:
    print("Nah")
    print("+0")
    
question4 = input(questions[3])

if question4 == "Pizza" or question4 == "pizza" or question4 == "Piza" or question4 == "piza":
    print("Yea")
    print("+1")
    total = total + 1
else:
    print("Nah")
    print("+0")
    
question5 = input(questions[4])

if question5 == "Yes" or question5 == "yes" or question5 == "Yea" or question5 == "yea" or question5 == "ofc" or question5 == "Ofc" or question5 == "OFC":
    print("Yea")
    print("+1")
    total = total + 1
else:
    print("Nah")
    print("+0")
    
    
print("Your score was " + str(total) +"/5")
print("Made by @tompedro3faze1")

restart = input("Restart?")

if restart == "yes" or restart == "Yes":
    print("Ok, restarting")
else:
    print("Ok")
