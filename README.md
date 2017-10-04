# learnpython

value = input("Enter something: ")
print ("you entered " + value)

print range(0,-10,1)
print range(9,-1,-1)
This gives you a bucket of numbers, like a hamper full of clothes
Can you use this as a whole ?
To put it in the washer, what does your mom tell you to do?
Take it one by one, stretch it out, turn it inside out, and button the shirts and so on.
To take it one by one from the bucket of numbers, you do

for number in range(0,-10,1)
  print number

Do It Yourself!

Print the odd or even numbers from 20 to 0.
Print multiples of 3 upto 30

Produce this output
[5,6,7,8,9,10]
5
0,1,2,3,4
6
0,1,2,3,4,5
7
0,1,2,3,4,5,6
8
0,1,2,3,4,5,6,7
9
0,1,2,3,4,5,6,7,8
10
0,1,2,3,4,5,6,7,8,9

The Operators

On command line, try this:
print 2+2
print 3-2
print 3*2
print 4/2
print float(3)/float(2)

ans= float(3)/float(2)
print("The answer is: " + ans)  #error
print("The answer is: " + str(ans)) 

Introduce int, float, str

print("The Awesome Calculator")
num1 = input("Enter a number: ")
num2 = input("Enter another number: ")
print("The sum of {0} and {1} is {2}".format(num1, num2, int(num1) + int(num2)))
