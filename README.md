this is my code of my game KBC which i have made on python 
def get_non_empty_input(prompt, valid_options=None):
    while True:
        user_input = input(prompt).strip()
        if user_input == "":
            print("Input cannot be empty. Please try again.")
            continue
        if valid_options:
            if user_input not in valid_options:
                print(f"Invalid option. Please enter one of: {', '.join(valid_options)}")
                continue
        return user_input

def get_strict_enter(prompt):
    while True:
        user_input = input(prompt)
        if user_input.strip() == "":
            return
        else:
            print("Please press only Enter to continue.")

# Create a program capable of displaying questions to the user like KBC
# Use list data type to store the questions and their correct answer
# Display the final amount to that person who is taking the final amount home after playing the game

Name = get_non_empty_input("Enter your name: ")
print("Hello", Name, "Let's play KBC!")
Rules = ("Rules of the game:")
print(Rules)
enter1 = get_strict_enter("Press Enter to continue: ")
print("")
print("You have to answer 2 questions")
enter2 = get_strict_enter("Press Enter to continue: ")
print("")
print("There are 2 Padav's in this question one is on Prashna 5 and the other is on Prashna 10, the Padav's are like checkpoint of the game")
enter3 = get_strict_enter("Press Enter to continue: ")
print("")
print("You can quit the game at any time by typing 'quit'")
enter4 = get_strict_enter("Press Enter to continue: ")
print("")
print("You can also use '50-50' to get rid of 2 wrong options")
get_strict_enter("Are you ready to start the game? If yes then press Enter and the game begins: ")
print("")

Question1 = "Prashna 1 -> What is the capital of India?"
print(Question1)
print("A. Delhi")
print("B. Mumbai")
print("C. Banglore")
print("D. Chennai")
Answer = get_non_empty_input("Enter your answer: ", ["A", "B", "C", "D", "quit", "50-50"])
if Answer == "A":
    print("Congratualtions! you got ₹1,000")
elif Answer == "B":
    print("Ohoo! you lost all your money, the correct option is A")
    exit()
elif Answer == "C":
    print("Ohoo! you lost all your money, the correct option is A")
    exit()
elif Answer == "D":
    print("Ohoo! you lost all your money, the correct option is A")
    exit()
else:
    print("Please write the option in capital letter like A, B etc.")

    # on the wrong answer program will exit

Question1_option1 = "Delhi"
Question1_option2 = "Mumbai"
Question1_option3 = "Banglore"
Question1_option4 = "Chennai"
Question1_answer = "Delhi"
Question1_option1reward = "Congratualtions! you got ₹1,000"
Question1_option2reward = "Ohoo! you lost all your money, the correct option is A"
Question1_option3reward = "Ohoo! you lost all your money, the correct option is A"
Question1_option4reward = "Ohoo! you lost all your money, the correct option is A"
Question1_option4reward = "Ohoo! you lost all your money, the correct option is A"

enter5 = input("Shall we proceed to next question?, if yes then press enter if no then type quit and the game will exit: ") 
if enter5 == "quit":
    print("Well played! you are taking only ₹1,000 with you")
    exit()

else :
    print("Let's proceed to next question")

print("")
# -------------------------------------------------------------Q2
Question2 = "Prashna 2 -> What is the sun total of 1003+2003?"
print(Question2)
print("A. 4006")
print("B. 2006")
print("C. 3006")
print("D. 5060")
Answer = get_non_empty_input("Enter your answer: ", ["A", "B", "C", "D", "quit", "50-50"])
if Answer == "A":
    print("Ohoo! you lost all your money, the correct option is C")
    exit()
elif Answer == "B":
    print("Ohoo! you lost all your money, the correct option is C")
    exit()
elif Answer == "C":
    print("Congratualtions! you got ₹2,000")
elif Answer == "D":
    print("Ohoo! you lost all your money, the correct option is C")
    exit()
elif quit == "quit":
    print("Well played! you are taking only ₹1,000 with you")
    exit()
else:
    print("Please write the option in capital letter like A, B etc.")
Question2_option1 = "4006"
Question2_option2 = "2006"
Question2_option3 = "3006"
Question2_option4 = "5060"
Question2_answer = "3006"
Question2_option1reward = "Ohoo! you lost all your money, the correct option is C"
Question2_option2reward = "Ohoo! you lost all your money, the correct option is C"
Question2_option3reward = "Congratualtions! you got ₹2,000"
Question2_option4reward = "Ohoo! you lost all your money, the correct option is C"

enter6 = input("Press enter to continue, if you want to quit type \"quit\" to exit the game: ") 
if enter6 == "quit":
    print("Well played! you are taking only ₹2,000 with you")
    exit()

else :
    print("Let's proceed to next question")
# By using 50-50 command user can get rid of 2 wrong options
# 5050 = input("Use (50 50) to execute the 50 50 lifeine: ")
# if 5050 == "50-50":
#     print("A. 4006")
#     print("C. 3006")
#     print("Enter your answer:")
#     Answer = get_non_empty_input("Enter your answer: ", ["A", "B", "C", "D", "quit", "50-50"])
#     if Answer == "A":
#         print("Ohoo! you lost all your money")
#     elif Answer == "C":
#         print("Congratualtions! you got ₹20,000")
#     else:
#         print("Please write the option in capital letter like A, B etc.")
print ("")
# -------------------------------------------------------------Q3
Question3 = "Prashna 3 -> Which of the following countries is the world's largest producer of saffron?"
print(Question3)
print("A. India")
print("B. Iran")
print("C. China")
print("D. Afghanistan")
Answer = get_non_empty_input("Enter your answer: ", ["A", "B", "C", "D", "quit", "50-50"])
if Answer == "A":
    print("Ohoo! you lost all your money, the correct option is B")
    exit()
elif Answer == "B":
    print("Congratualtions! you got ₹3,000")
elif Answer == "C":
    print("Ohoo! you lost all your money, the correct option is B")
    exit()
elif Answer == "D":
    print("Ohoo! you lost all your money, the correct option is B")
    exit()
elif quit == "quit":
    print("Well played! you are taking only ₹2,000 with you")
    exit()
else:
    print("Please write the option in capital letter like A, B etc.")
Question3_option1 = "India"
Question3_option2 = "Iran"
Question3_option3 = "China"
Question3_option4 = "Afghanistan"
Question3_answer = "Iran"
Question3_option1reward = "Ohoo! you lost all your money, the correct option is B"
Question3_option2reward = "Congratualtions! you got ₹3,000"
Question3_option3reward = "Ohoo! you lost all your money, the correct option is B"
Question3_option4reward = "Ohoo! you lost all your money, the correct option is B"
print("")

enter7 = input("Press enter to continue, if you want to quit type \"quit\" to exit the game: ") 
if enter7 == "quit":
    print("Well played! you are taking only ₹3,000 with you")
    exit()

else :
    print("Let's proceed to next question")

print("")
# -------------------------------------------------------------Q4
Question4 = "Prashna 4 ->How many major religions are there in India?"
print(Question4)
print("A. 4")
print("B. 5")
print("C. 6")
print("D. 7")
Answer = get_non_empty_input("Enter your answer: ", ["A", "B", "C", "D", "quit", "50-50"])
if Answer == "A":
    print("Ohoo! you lost all your money, the correct option is C")
    exit()
elif Answer == "B":
    print("Ohoo! you lost all your money, the correct opption is C")
    exit()
elif Answer == "C":
    print("Congratualtions! you got ₹5,000")
elif Answer == "D":
    print("Ohoo! you lost all your money, the correct option is C")
    exit()
elif quit == "quit":
    print("Well played! you are taking only ₹3,000 with you")
    exit()
else:
    print("Please write the option in capital letter like A, B etc.")


Question4_option1 = "4"
Question4_option2 = "5"
Question4_option3 = "6"
Question4_option4 = "7"
Question4_answer = "6"
Question4_option1reward = "Ohoo! you lost all your money, the correct option is C"
Question4_option2reward = "Ohoo! you lost all your money, the correct option is C"
Question4_option3reward = "Congratualtions! you got ₹5,000"
Question4_option4reward = "Ohoo! you lost all your money, the correct option is C"
print("")

announcement = "This is the \"Pehla Padav\" of the game, you have to play this round if you don't know the answer simply type \"quit\" to exit the game"
print(announcement)
enter8 = get_strict_enter("Press Enter to continue: ")
if enter8 == "quit":
    print("Well played! you are taking only ₹5,000 with you")
    exit()

else :
    print("Let's proceed to next question")

print("")
# -------------------------------------------------------------Q5
Question5 = "Prashna 5 -> Which is the largest continent in the world?"
print(Question5)
print("A. Asia")
print("B. Africa")
print("C. North America")
print("D. South America")
Answer = get_non_empty_input("Enter your answer: ", ["A", "B", "C", "D", "quit", "50-50"])
if Answer == "A":
    print("Congratualtions! you got ₹10,000")
    print("Congratualtions! you have completed the Pehla Padav of the game")
elif Answer == "B":
    print("Ohoo! you got only ₹5,000, the correct option is A")
    exit()
elif Answer == "C":
    print("Ohoo! you got only ₹5,000, the correct option is A")
    exit()
elif Answer == "D":
    print("Ohoo! you got only ₹5,000, the correct option is A")
    exit()
elif quit == "quit":
    print("Well played! you are taking only ₹5,000 with you")
    exit()
else:
    print("Please write the option in capital letter like A, B etc.")
Question5_option1 = "Asia"
Question5_option2 = "Africa"
Question5_option3 = "North America"
Question5_option4 = "South America"
Question5_answer = "Asia"
Question5_option1reward = "Congratualtions! you got ₹10,000"
Question5_option2reward = "Ohoo! you got only ₹5,000, the correct option is A"
Question5_option3reward = "Ohoo! you got only ₹5,000, the correct option is A"
Question5_option4reward = "Ohoo! you got only ₹5,000, the correct option is A"

enter9 = input("Press enter to continue, if you want to quit type \"quit\" to exit the game: ") 
if enter9 == "quit":
    print("Well played! you are taking only ₹2,000 with you")
    exit()

else :
    print("Let's proceed to next question")

print("")
# -------------------------------------------------------------Q6
Question6 = "Which is the largest ocean in the world?"
print(Question6)
print("A. Atlantic Ocean")
print("B. Indian Ocean")
print("C. Arctic Ocean")
print("D. Pacific Ocean")
Answer = get_non_empty_input("Enter your answer: ", ["A", "B", "C", "D", "quit", "50-50"])
if Answer == "A":
    print("Ohoo! you got only ₹10,000, the correct option is D")
    exit()
elif Answer == "B":
    print("Ohoo! you got only ₹10,000, the correct option is D")
    exit()
elif Answer == "C":
    print("Ohoo! you got only ₹10,000, the correct option is D")
    exit()
elif Answer == "D":
    print("Congratualtions! you got ₹20,000")
    exit()
else :
    print("Please write the option in capital letter like A, B etc.")
Question6_option1 = "Atlantic Ocean"
Question6_option2 = "Indian Ocean"
Question6_option3 = "Arctic Ocean"
Question6_option4 = "Pacific Ocean"
Question6_answer = "Pacific Ocean"
Question6_option1reward = "Ohoo! you got only ₹10,000, the correct option is D"
Question6_option2reward = "Ohoo! you got only ₹10,000, the correct option is D"
Question6_option3reward = "Ohoo! you got only ₹10,000, the correct option is D"
Question6_option4reward = "Congratualtions! you got ₹20,000"

print("")
# -------------------------------------------------------------Q7
Question7 = "Prashna 7 -> Which god is also known as \'Gauri Nandan\'?"
print(Question7)
print("A. Lord Hanuman")
print("B. Lord Vishnu")
print("C. Lord Ganesha")
print("D. Lord Krishna")
Answer = get_non_empty_input("Enter your answer: ", ["A", "B", "C", "D", "quit", "50-50"])
if Answer == "A":
    print("Ohoo! you got only ₹10,000, the correct option is C")
    exit()
elif Answer == "B":
    print("Ohoo! you got only ₹10,000, the correct option is C")
    exit()
elif Answer == "C":
    print("Congratualtions! you got ₹40,000")
    exit()
elif Answer == "D":
    print("Ohoo! you got only ₹10,000, the correct option is C")
    exit()
else:
    print("Please write the option in capital letter like A, B etc.")   

Question7_option1 = "Lord Hanuman"
Question7_option2 = "Lord Vishnu"
Question7_option3 = "Lord Ganesha"
Question7_option4 = "Lord Krishna"
Question7_answer = "Lord Ganesha"
Question7_option1reward = "Ohoo! you got only ₹10,000, the correct option is C"
Question7_option2reward = "Ohoo! you got only ₹10,000, the correct option is C"
Question7_option3reward = "Congratualtions! you got ₹40,000"
Question7_option4reward = "Ohoo! you got only ₹10,000, the correct option is C"

print("")
# -------------------------------------------------------------Q8
Question8 = "Prashna 8 -> Which is the largest desert in the world?"
print(Question8)
print("A. Sahara Desert")
print("B. Arabian Desert")
print("C. Gobi Desert")
print("D. Kalahari Desert")
Answer = get_non_empty_input("Enter your answer: ", ["A", "B", "C", "D", "quit", "50-50"])
if Answer == "A":
    print("Congratualtions! you got ₹80,000")
    exit()
elif Answer == "B":
    print("Ohoo! you got only ₹10,000, the correct option is A")
    exit()
elif Answer == "C":
    print("Ohoo! you got only ₹10,000, the correct option is A")
    exit()
elif Answer == "D":
    print("Ohoo! you got only ₹10,000, the correct option is A")
    exit()
elif quit == "quit":
    print("Well played! you are taking only ₹80,000 with you")
    exit()
else:
    print("Please write the option in capital letter like A, B etc.")

Question8_option1 = "Sahara Desert"
Question8_option2 = "Arabian Desert"
Question8_option3 = "Gobi Desert"
Question8_option4 = "Kalahari Desert"
Question8_answer = "Sahara Desert"
Question8_option1reward = "Congratualtions! you got ₹80,000"
Question8_option2reward = "Ohoo! you got only ₹10,000, the correct option is A"
Question8_option3reward = "Ohoo! you got only ₹10,000, the correct option is A"
Question8_option4reward = "Ohoo! you got only ₹10,000, the correct option is A"

print("")
# -------------------------------------------------------------Q9
Question9 = "Prashna 9 -> When is the National Hindi Diwas celebrated?"
print(Question9)
print("A. 14 September")
print("B. 15 September")
print("C. 16 September")
print("D. 17 September")
Answer = get_non_empty_input("Enter your answer: ", ["A", "B", "C", "D", "quit", "50-50"])
if Answer == "A":
    print("Congratualtions! you got ₹1,60,000")
    exit()
elif Answer == "B":
    print("Ohoo! you got only ₹10,000, the correct option is A")
    exit()
elif Answer == "C":
    print("Ohoo! you got only ₹10,000, the correct option is A")
    exit()
elif Answer == "D":
    print("Ohoo! you got only ₹10,000, the correct option is A")
    exit()
elif quit == "quit":
    print("Well played! you are taking only ₹1,60,000 with you")
    exit()
else:
    print("Please write the option in capital letter like A, B etc.")

Question9_option1 = "14 September"
Question9_option2 = "15 September"
Question9_option3 = "16 September"
Question9_option4 = "17 September"
Question9_answer = "14 September"
Question9_option1reward = "Congratualtions! you got ₹1,60,000"
Question9_option2reward = "Ohoo! you got only ₹10,000, the correct option is A"
Question9_option3reward = "Ohoo! you got only ₹10,000, the correct option is A"
Question9_option4reward = "Ohoo! you got only ₹10,000, the correct option is A"
print("")

announcement1 = "This is the \"Dusara Padav\" of the game, you have to play this round if you don't know the answer simply type \"quit\" to exit the game"
print(announcement1)
enter10 = get_strict_enter("Press Enter to continue: ")
if enter10 == "quit":
    print("Well played! you are taking only ₹1,60,000 with you")
    exit()

else :
    print("Let's proceed to next question")

print("")
# -------------------------------------------------------------Q10
Question10 = "Which country is the largest producer of coffee in the world?"
print(Question10)
print("A. Brazil")
print("B. Colombia")
print("C. Vietnam")
print("D. India")

Answer = get_non_empty_input("Enter your answer: ", ["A", "B", "C", "D", "quit", "50-50"])
if Answer == "A":
    print("Congratualtions! you got ₹3,20,000")
    exit()
elif Answer == "B":
    print("Ohoo! you got only ₹10,000, the correct option is A")
    exit()
elif Answer == "C":
    print("Ohoo! you got only ₹10,000, the correct option is A")
    exit()
elif Answer == "D":
    print("Ohoo! you got only ₹10,000, the correct option is A")
    exit()
elif quit == "quit":
    print("Well played! you are taking only ₹3,20,000 with you")
    exit()
else:
    print("Please write the option in capital letter like A, B etc.")
Question10_option1 = "Brazil"
Question10_option2 = "Colombia"
Question10_option3 = "Vietnam"
Question10_option4 = "India"
Question10_answer = "Brazil"
Question10_option1reward = "Congratualtions! you got ₹3,20,000"
Question10_option2reward = "Ohoo! you got only ₹10,000, the correct option is A"
Question10_option3reward = "Ohoo! you got only ₹10,000, the correct option is A"
Question10_option4reward = "Ohoo! you got only ₹10,000, the correct option is A"

print("")
#  -------------------------------------------------------------Q11
Question11 = "Prashna 11 -> Who wrote Vande Mataram?"
print(Question11)
print("A. Rabindranath Tagore")
print("B. Bankim Chandra Chatterjee")
print("C. Sarojini Naidu")
print("D. Mahatma Gandhi")
Answer = get_non_empty_input("Enter your answer: ", ["A", "B", "C", "D", "quit", "50-50"])

if Answer == "A":
    print("Ohoo! you got only ₹3,20,000, the correct option is B")
    exit()
elif Answer == "B":
    print("Congratualtions! you got ₹6,40,000")
    exit()
elif Answer == "C":
    print("Ohoo! you got only ₹3,20,000, the correct option is B")
    exit()
elif Answer == "D":
    print("Ohoo! you got only ₹3,20,000, the correct option is B")
    exit()
else:
    print("Please write the option in capital letter like A, B etc.")
Question11_option1 = "Rabindranath Tagore"
Question11_option2 = "Bankim Chandra Chatterjee"
Question11_option3 = "Sarojini Naidu"
Question11_option4 = "Mahatma Gandhi"
Question11_answer = "Bankim Chandra Chatterjee"
Question11_option1reward = "Ohoo! you got only ₹3,20,000, the correct option is B"
Question11_option2reward = "Congratualtions! you got ₹6,40,000"
Question11_option3reward = "Ohoo! you got only ₹3,20,000, the correct option is B"
Question11_option4reward = "Ohoo! you got only ₹3,20,000, the correct option is B"

print("")
# -------------------------------------------------------------Q12
Question12 = "Prashna 12 -> Which one of the following places is famous for the Great Vishnu Temple?"
print(Question12)
print("A. Khajuraho")
print("B. Kanchipuram")
print("C. Madurai")
print("D. Tirupati")
Answer = get_non_empty_input("Enter your answer: ", ["A", "B", "C", "D", "quit", "50-50"])

if Answer == "A":
    print("Ohoo! you got only ₹3,20,000, the correct option is D")
    exit()
elif Answer == "B":
    print("Ohoo! you got only ₹3,20,000, the correct option is D")
    exit()
elif Answer == "C":
    print("Ohoo! you got only ₹3,20,000, the correct option is D")
    exit()
elif Answer == "D":
    print("Congratualtions! you got ₹12,50,000")
    exit()
elif Answer == "E":
    print("Ohoo! you got only ₹3,20,000, the correct option is D")
    exit()
else:
    print("Please write the option in capital letter like A, B etc.")
Question12_option1 = "Khajuraho"
Question12_option2 = "Kanchipuram"
Question12_option3 = "Madurai"
Question12_option4 = "Tirupati"
Question12_answer = "Tirupati"
Question12_option1reward = "Ohoo! you got only ₹1,60,000, the correct option is D"
Question12_option2reward = "Ohoo! you got only ₹1,60,000, the correct option is D"
Question12_option3reward = "Ohoo! you got only ₹1,60,000, the correct option is D"
Question12_option4reward = "Congratualtions! you got ₹12,50,000"

print("")
# -------------------------------------------------------------Q13
Question13 = "Prashna 13 -> Where is the largest Buddhist Monastery in India located?"
print(Question13)
print("A. Sikkim")
print("B. Arunachal Pradesh")
print("C. Himachal Pradesh")
print("D. Ladakh")
Answer = get_non_empty_input("Enter your answer: ", ["A", "B", "C", "D", "quit", "50-50"])

if Answer == "A":
    print("Ohoo! you got only ₹3,20,000, the correct option is B")
    exit()
elif Answer == "B":
    print("Congratualtions! you got ₹25,00,000")
    exit()
elif Answer == "C":
    print("Ohoo! you got only ₹3,20,000, the correct option is B")
    exit()
elif Answer == "D":
    print("Ohoo! you got only ₹3,20,000, the correct option is B")
    exit()
else:
    print("Please write the option in capital letter like A, B etc.")
Question13_option1 = "Sikkim"
Question13_option2 = "Arunachal Pradesh"
Question13_option3 = "Himachal Pradesh"
Question13_option4 = "Ladakh"
Question13_answer = "Arunachal Pradesh"
Question13_option1reward = "Ohoo! you got only ₹3,20,000, the correct option is B"
Question13_option2reward = "Congratualtions! you got ₹25,00,000"
Question13_option3reward = "Ohoo! you got only ₹3,20,000, the correct option is B"
Question13_option4reward = "Ohoo! you got only ₹3,20,000, the correct option is B"

print("")
# -------------------------------------------------------------Q14
Question14 = "Prashna 14 -> Which Indian monument was originally built as a victory tower to commemorate the defeat of the Khan of Khambhat?"
print(Question14)
print("A. Qutub Minar")
print("B. Red Fort")
print("C. Gol Gumbaz")
print("D. Charminar")
Answer = get_non_empty_input("Enter your answer: ", ["A", "B", "C", "D", "quit", "50-50"])

if Answer == "A":
    print("Congratualtions! you got ₹50,00,000")
    exit()
elif Answer == "B":
    print("Ohoo! you got only ₹3,20,000, the correct option is A")
    exit()
elif Answer == "C":
    print("Ohoo! you got only ₹3,20,000, the correct option is A")
    exit()
elif Answer == "D":
    print("Ohoo! you got only ₹3,20,000, the correct option is A")
    exit()
else:
    print("Please write the option in capital letter like A, B etc.")
Question14_option1 = "Qutub Minar"
Question14_option2 = "Red Fort"
Question14_option3 = "Gol Gumbaz"
Question14_option4 = "Charminar"
Question14_answer = "Qutub Minar"
Question14_option1reward = "Congratualtions! you got ₹50,00,000"
Question14_option2reward = "Ohoo! you got only ₹3,20,000, the correct option is A"
Question14_option3reward = "Ohoo! you got only ₹3,20,000, the correct option is A"
Question14_option4reward = "Ohoo! you got only ₹3,20,000, the correct option is A"

print("")
# -------------------------------------------------------------Q15
Question15 = "Prashna 15 -> Who was the first Indian woman to win a medal in the Olympics??"
print(Question15)
print("A. Mary Kom")
print("B. Saina Nehwal")
print("C. Karnam Malleswari")
print("D. P.V. Sindhu")
Answer = get_non_empty_input("Enter your answer: ", ["A", "B", "C", "D", "quit", "50-50"])

if Answer == "A":
    print("Ohoo! you got only ₹3,20,000, the correct option is C")
    exit()
elif Answer == "B":
    print("Ohoo! you got only ₹3,20,000, the correct option is C")
    exit()
elif Answer == "C":
    print("Congratualtions! you got ₹7,50,000")
    exit()
elif Answer == "D":
    print("Ohoo! you got only ₹3,20,000, the correct option is C")
    exit()
else:
    print("Please write the option in capital letter like A, B etc.")
Question15_option1 = "Mary Kom"
Question15_option2 = "Saina Nehwal"
Question15_option3 = "Karnam Malleswari"
Question15_option4 = "P.V. Sindhu"
Question15_answer = "Karnam Malleswari"
Question15_option1reward = "Ohoo! you got only ₹3,20,000, the correct option is C"
Question15_option2reward = "Ohoo! you got only ₹3,20,000, the correct option is C"
Question15_option3reward = "Congratualtions! you got ₹7,50,000"
Question15_option4reward = "Ohoo! you got only ₹3,20,000, the correct option is C"

print("")
# -------------------------------------------------------------Q16
Question16 = "Prashna 16 -> Which administrative reform implemented by Alauddin Khalji during the Delhi Sultanate was most crucial in maintaining the stability of his empire?"
print(Question16)
print("A. Market Control")
print("B. Land Revenue Assessment")
print("C. Military Reforms")
print("D. Bureaucratic Reforms")
Answer = get_non_empty_input("Enter your answer: ", ["A", "B", "C", "D", "quit", "50-50"])

if Answer == "A":
    print("Congratualtions! you got ₹1,00,00,000")
elif Answer == "B":
    print("Ohoo! you got only ₹3,20,000, the correct option is A")
    exit()
elif Answer == "C":
    print("Ohoo! you got only ₹3,20,000, the correct option is A")
    exit()
elif Answer == "D":
    print("Ohoo! you got only ₹3,20,000, the correct option is A")
    exit()
else:
    print("Please write the option in capital letter like A, B etc.")
Question16_option1 = "Market Control"
Question16_option2 = "Land Revenue Assessment"
Question16_option3 = "Military Reforms"
Question16_option4 = "Bureaucratic Reforms"
Question16_answer = "Market Control"
Question16_option1reward = "Congratualtions! you got ₹1,00,00,000"
Question16_option2reward = "Ohoo! you got only ₹3,20,000, the correct option is A"
Question16_option3reward = "Ohoo! you got only ₹3,20,000, the correct option is A"
Question16_option4reward = "Ohoo! you got only ₹3,20,000, the correct option is A"

print("")
# -------------------------------------------------------------Q17 Final Question
Question17 = "Prashna 17 -> Which of the following is not a part of the Indian Constitution?"
print(Question17)
print("A. Fundamental Rights")
print("B. Directive Principles of State Policy")
print("C. Fundamental Duties")
print("D. Preamble")
Answer = get_non_empty_input("Enter your answer: ", ["A", "B", "C", "D", "quit", "50-50"])

if Answer == "A":
    print("Ohoo! you got only ₹3,20,000, the correct option is D")
    exit()
elif Answer == "B":
    print("Ohoo! you got only ₹3,20,000, the correct option is D")
    exit()
elif Answer == "C":
    print("Ohoo! you got only ₹3,20,000, the correct option is D")
    exit()
elif Answer == "D":
    print("Saaaaat Karoooood!")
else:
    print("Please write the option in capital letter like A, B etc.")
Question17_option1 = "Fundamental Rights"
Question17_option2 = "Directive Principles of State Policy"
Question17_option3 = "Fundamental Duties"
Question17_option4 = "Preamble"
Question17_answer = "Preamble"
Question17_option1reward = "Ohoo! you got only ₹3,20,000, the correct option is D"
Question17_option2reward = "Ohoo! you got only ₹3,20,000, the correct option is D"
Question17_option3reward = "Ohoo! you got only ₹3,20,000, the correct option is D"
Question17_option4reward = "Saaaaat Karoooood!"

print("")
# -------------------------------------------------------------End of the game
print("Congratulations! you have completed the game")
print("")
print("You are taking home ₹7,00,00,000")
print("")
print("Thank you for playing the game")
print("")
print("Have a nice day!")
print("")
print("Bye Bye")
print("")
exit()

I want a REDME file for my github
