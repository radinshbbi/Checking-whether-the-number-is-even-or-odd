# Checking-whether-the-number-is-even-or-odd





def number ():
    number_person = int(input("please enter your number:\n"))
    if number_person % 2==0:
        print(number_person," is even")
    else:
        print(number_person," is odd")
def again():
    question = input(''' 
    DO you want to check your number
    please type Y for Yes or N for No?\n    
    ''')
    if question == "Y":
        number()
    elif question == "N":
        print("Glad to see you, Goodby.")
    else:
        again()

number()
again()
