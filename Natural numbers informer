"""
The program asks for any natural number and then it gives an information how many digits the natural number consists of and what is the sum of this digits. 
The program works even if there is some spaces in typed information and react in proper way if you put the data which is not in digital form.
"""


print("Natural numbers analyser")

i = 0
while i != 2:
    i = int(input("""What would you like to do? 
1 - Choose the natural number to analyse, 
2 - End program
>>> """))
    if i != 1 and i !=2:
        print("This function does not exist. Choose 1 or 2 to run program")
    if i == 1:
        NatNumber = (input("Type any natural number: "))
        if  NatNumber.strip().isdigit() == True and int(NatNumber) > 0:
            print("This Natural Number consists of: ", len(list(NatNumber.strip())), "digits.")
            print("The sum of all separate digits from this natural number is: ", sum([int(cyfra) for cyfra in NatNumber.strip()]))
        else:
            print("This is not Natural Number. Type it again in digital form")
    elif i == 2:
        print("Good bye :)")
