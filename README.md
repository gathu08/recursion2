# recursion2
This a simple program that shows how recursion is used


def countdown(x):
    if x == 0:
        print ("Done!")
        return
    else:
        print (x, " ..")
        countdown(x-1) 
        
print (countdown(10))


# Function that calculates the power
def power(num,pwr):
    if pwr == 0:
        return 1
    else:
        return num *power(num,pwr -1)
print (power(2,4))

#function that calculates the factorial
def factorial(num):
    if num == 0:
        return 1
    else:
        return num * factorial(num -1)
    

print(factorial(5))
    
