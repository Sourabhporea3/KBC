# KBC
kbc lottarry price collection 

r=[]
def question1():
    print("1)Where is stylishstar: \n 1)in home     2)in mess \n 3)in college     4)in library")
    a=int(input("Enter your answer :"))
    if 0<a<5:
        if a==3:
            print("Right Answer")
            r.append(1)
        else:
            print("Wrong answer")
            r.append(0)
    else:
        print("You enter a invalid option")
        r.append("invalid")
def question2():
    print("2)What are you doing here: \n 1)waiting for my didi  \b   2)Waiting for my wife \n 3)waiting my mom     4)Waiting for you")
    a=int(input("Enter your answer :"))
    if 0<a<5:
        if a==1:
            print("Right Answer")
            r.append(1)
        else:
            print("Wrong answer")
            r.append(0)
    else:
        print("You enter a invalid option")
        r.append("invalid")
def question3():
    print("3)How many times you bath in a week: \n 1)4 times  \b   2)6 times \n 3) no nut     4)greater than 6")
    a=int(input("Enter your answer :"))
    if 0<a<5:
        if a==2:
            print("Right Answer")
            r.append(1)
        else:
            print("Wrong answer")
            r.append(0)
    else:
        print("You enter a invalid option")
        r.append("invalid")
def question4():
    print("4)If i want to meet with you then what is your Answer: \n 1)o fuck you  \b   2)You are really naughty \n 3)vag motherbord     4)in marrage")
    a=int(input("Enter your answer :"))
    if 0<a<5:
        if a==4:
            print("Right Answer")
            r.append(1)
        else:
            print("Wrong answer")
            r.append(0)
    else:
        print("You enter a invalid option")
        r.append("invalid")
def question5():
    print("5)Do you love me: \n 1)yes   \b   2)yes with some smile \n 3)noops     4)really i want to marry you")
    a=int(input("Enter your answer :"))
    if 0<a<5:
        if a==4:
            print("Right Answer")
            r.append(1)
        else:
            print("Wrong answer")
            r.append(0)
    else:
        print("You enter a invalid option")
        r.append("invalid")
def question6():
    print("6)Can i get a hug from you: \n 1)obviously  \b   2)not at this time \n 3)Its totally depend on you     4)hug me")
    a=int(input("Enter your answer :"))
    if 0<a<5:
        if a==3:
            print("Right Answer")
            r.append(1)
        else:
            print("Wrong answer")
            r.append(0)
    else:
        print("You enter a invalid option")
        r.append("invalid")
def question8():
    print("8)Are you committed: \n 1)no  \b   2)yes \n 3)don't know     4)little yes more no")
    a=int(input("Enter your answer :"))
    if 0<a<5:
        if a==4:
            print("Right Answer")
            r.append(1)
        else:
            print("Wrong answer")
            r.append(0)
    else:
        print("You enter a invalid option")
        r.append("invalid")
def question9():
    print("9)Where are you from: \n 1)America  \b   2)father of fakisthan \n 3)brazil     4)argentina")
    a=int(input("Enter your answer :"))
    if 0<a<5:
        if a==2:
            print("Right Answer")
            r.append(1)
        else:
            print("Wrong answer")
            r.append(0)
    else:
        print("You enter a invalid option")
        r.append("invalid")
def question10():
    print("10)Your favourite player: \n 1)Harduk  \b   2)kohli \n 3)Dhoni     4)Rohit")

    a=int(input("Enter your answer :"))
    if 0<a<5:
        if a==1:
            print("Right Answer")
            r.append(1)
        else:
            print("Wrong answer")
            r.append(0)
    else:
        print("You enter a invalid option")
        r.append("invalid")
def question7():
    print("7)What is your favorite actor/actress: \n 1)stylishstar  \b   2)kohli \n 3)samantha     4)1 & 2")
    a=int(input("Enter your answer :"))
    if 0<a<5:
        if a==4:
            print("Right Answer")
            r.append(1)
        else:
            print("Wrong answer")
            r.append(0)
    else:
        print("You enter a invalid option")
        r.append("invalid")
question1()
question2()
question3()
question4()
question5()
question6()
question7()
question8()
question9()
question10()



 # print(question1(),question2())
# print(r)
c=r.count(1)
print("Your correct answers are :",c)
print("you Win: ",c*2500,"rs")
