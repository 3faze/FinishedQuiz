#Finished quiz
total = 0
y = "Yes!"
n = "No..."
#Listing the questions
questions = ["Whats his name?", "How old is he?", "Is he my bestie?", "Whats his favourite food?", "Is he the best?"]


#Making the name input
name = input('What is your name?\n')
print('Hello, lets start this, %s!' % name)

#Setting the first question
question1= input(questions[0])

#Where it says santiago put the name you want
#Making the conditions
if question1 == "Santiago" or question1 == "santiago":
    print(y)
    print("+1")
    total = total + 1
else:
    print(n)
    print("+0")
    
#Setting the second question
question2 = input(questions[1])
    
#Where it says 12 put the age you want
#Making the conditions
if question2 == "12":
    print(y)
    print("+1")
    total = total + 1
else:
    print(n)
    print("+0")
    
#Setting the third question
question3 = input(questions[2])

#Making the conditions
if question3 == "Yes" or question3 == "yes" or question3 == "Yea" or question3 == "yea":
    print(y)
    print("+1")
    total = total + 1
else:
    print(n)
    print("+0")
    
#Setting the fourth question
question4 = input(questions[3])

#Where it says pizza put what you want
#Making the conditions
if question4 == "Pizza" or question4 == "pizza" or question4 == "Piza" or question4 == "piza":
    print(y)
    print("+1")
    total = total + 1
else:
    print(n)
    print("+0")
    
#Setting the fift question
question5 = input(questions[4])

#Making the conditions
if question5 == "Yes" or question5 == "yes" or question5 == "Yea" or question5 == "yea" or question5 == "ofc" or question5 == "Ofc" or question5 == "OFC":
    print(y)
    print("+1")
    total = total + 1
else:
    print(n)
    print("+0")
    
    
#Telling the score
print("Your score was " + str(total) +"/5")
#Giving credits
print("Made by @tompedro3faze1")
