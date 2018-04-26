# .py

import random
min = 2
max = 11

sum = 0


draw1 = random.randint(min, max)
draw2 = random.randint(min, max)
draw3 = random.randint(min, max)
draw4 = random.randint(min, max)
draw5 = random.randint(min, max)
draw6 = random.randint(min, max)


if sum == 0:
    print (draw1)
    if sum <= 21:
        print ("draw more? (y/n)")
        
    i2 = str(input())
    if i2 == "y":
        #print (draw2)
        print ("your card is " + str(draw2))
    elif i2 == "n":
        print ("your result is " + str(draw1))
        
    if i2 == "y":
        sum_12 = draw1 + draw2
        print ("your sum now is " + str(sum_12))
        if sum_12 <= 21:
            print ("draw more? (y/n)")

    i3 = str(input())
    if i3 == "y":
        #print (draw3)
        print ("your card is " + str(draw3))
    elif i3 == "n":
        print ("your result is " + str(draw2))

    if i3 == "y":
        sum_123 = draw1 + draw2 + draw3
        print ("your sum now is " + str(sum_123))
        if sum_123 <= 21:
            print ("draw more? (y/n)")
    
        if sum_12 > 21 or sum_123 > 21:
                print ("Сань, хуй соси")
        elif sum_12 == 21 or sum_123 == 21:
            print ("blackjack")
        
                
    i4 = str(input())
    if i4 == "y":
        #print (draw2)
        print ("your card is " + str(draw4))
    elif i4 == "n":
        print ("your result is " + str(draw3))

    if i4 == "y":
        sum_1234 = draw1 + draw2 + draw3 + draw4
        print ("your sum now is " + str(sum_1234))
        if sum_1234 <= 21:
            print ("draw more? (y/n)")

        if sum_1234 > 21:
                print ("Сань, хуй соси")
        elif sum_1234 == 21:
            print ("blackjack")
                
    i5 = str(input())
    if i5 == "y":
        #print (draw5)
        print ("your card is " + str(draw5))
    elif i5 == "n":
        print ("your result is " + str(draw4))  

    if i5 == "y":
        sum_12345 = draw1 + draw2 + draw3 + draw4 + draw5
        print ("your sum now is " + str(sum_12345))
        if sum_12345 <= 21:
            print ("draw more? (y/n)")

        if sum_12345 > 21:
                print ("Сань, хуй соси")
        elif sum_12345 == 21:
            print ("blackjack")

    i6 = str(input())
    if i6 == "y":
        #print (draw6)
        print ("your card is " + str(draw6))
    elif i6 == "n":
        print ("your result is " + str(draw5))

    if i6 == "y":
        sum_123456 = draw1 + draw2 + draw3 + draw4 + draw5 + draw6
        print ("your sum now is " + str(sum_123456))
        if sum_123456 <= 21:
            print ("draw more? (y/n)")

        if sum_123456 > 21:
                print ("Сань, хуй соси")
        elif sum_123456 == 21:
            print ("blackjack")
