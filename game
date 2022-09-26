import random

upper=int(input("enter upperbound :"))
lower=int(input("enter lower bound :"))

x=random.randint(lower,upper)
num=int(input("how many you want to try"))
i=0
while i <num:
    Guess = int(input("enter your guess number"))
    if Guess==x:
        print("answer is correct ! you had done at your %s try")
        break
    elif Guess>x:
        print("number is less than your Guess you have %s more try"%(num-i))
    elif Guess<x:
        print("number is greater than your Guess you have %s more try"%(num-i))
    i=i+1

