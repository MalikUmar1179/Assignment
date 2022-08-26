```python
# imple Message: Assign a message to a variable, 
# and then print that message?

message = "pleases try again"
print (message)
```

    pleases try again
    


```python
#  Find a quote from a famous person you admire.
# Print the quote and the name of its author. 
# Your output should look something like the following,
# including the quotation marks:
#Albert Einstein once said, “A person who never made a mistake never tried anything new.”

print('Banjamen franklin once said, "Well Done Is Bettrer Then Well Said"')
```

    Banjamen franklin once said, "Well Done Is Bettrer Then Well Said"
    


```python
#Calculate Area of a Circle::
#write a Python program which accepts the radius of a circle from the user and compute the area.
#Program Console Sample Output 1:
#Input Radius: 0.5
#Area of Circle with radius 0.5 is 0.7853981634

radius_of_circle = int(input("Please enter radius "))

Area_of_circle = (3.14)*(radius_of_circle**2)
print("Area of circle is:",Area_of_circle)
```

    Please enter radius 6
    Area of circle is: 113.04
    


```python
# Check Number either positive, negative or zero::
# Write a Python program to check if a number is positive, negative or zero

number_check = int(input("please enter a number to check status of that number")) 
if number_check >= 1:
    Print("positive number entered")
elif number_check <= -1:
    Print("Negative number entered")
else:
    print ("Zero Enterd")
```

    please enter a number to check status of that number0
    Zero Enterd
    


```python
vowels_letter = [ "A", "E","I","O","U"]
user_input1 = input("Enter a character: ")
for i in vowels_letter:
    if user_input1.upper() == i:
        print("letter " + user_input1 + " is a vowel ")
        break
else:
    print("letter " + user_input1 + "is not a vowel")
```

    Enter a character: E
    letter E is a vowel 
    


```python
# BMI Calculator
# Write a Python program to calculate body mass index Program Console Sample 1:
#Write a Python program to calculate body mass index Program Console Sample 1:
#Enter Height in Cm: 180
#Enter Weight in Kg: 75
#Your BMI is 23.15
```


```python
height_in_cm = int(input("Height entered in cm: "))
weight_in_kg = int(input("Weight entered in kg: "))

conversionHeightIn_squareMeter = (height_in_cm/100)**2
bmiCalculation = weight_in_kg/conversionHeightIn_squareMeter

print("Your BMI is: " + str(round(bmiCalculation,2)))
```

    Height entered in cm: 180
    Weight entered in kg: 75
    Your BMI is: 23.15
    


```python
# Store the names of a few of your friends in a list called names
# Print each person’s name by accessing each element in the list, one at a time.

names = ["Malik","faizan","Majid","usman","suleman","Umar"]
for name in names:
    print(name)
```

    Malik
    faizan
    Majid
    usman
    suleman
    Umar
    


```python
# Start with the list you used in Question 4, but instead of just printing each person’s name, 
# print a message to them. The text of each message should be the same,
# but each message should be personalized with the person’s name

for name in names:
    print("hello",name)
```

    hello Malik
    hello faizan
    hello Majid
    hello usman
    hello suleman
    hello Umar
    


```python

# .Make a python program that conatains your nine favourite dishes in a list called foods.
# Print the message, The first three items in the list are:

# Then use a slice to print the first three items from that program’s list.
# Print the message, Three items from the middle of the list are:
# Use a slice to print three items from the middle of the list.
# Print the message, The last three items in the list are:
# Use a slice to print the last three items in the list
```


```python
foods = ["biryani","qurma","kabab","palao","nihari",
         "halwa","Zarda","kheer","custurd"]

print("First three item of the list are",foods[3:])
print("Three item fro themiddle of the list are",foods[3:6])
print("The last three item of the list are",foods[6:])
```

    First three item of the list are ['palao', 'nihari', 'halwa', 'Zarda', 'kheer', 'custurd']
    Three item fro themiddle of the list are ['palao', 'nihari', 'halwa']
    The last three item of the list are ['Zarda', 'kheer', 'custurd']
    


```python
#Start with your program from your last Question8. Make a copy of the list of foods, and call it friend_foods.
#Then, do the following:
#Add a new dish to the original list.
#Add a different dish to the list friend_foods.
#Prove that you have two separate lists.
#Print the message, My favorite pizzas are: and then use a for loop to print the first list.
#Print the message,
#My friend’s favorite foods are:, and then use a for loop to print the second list.
#NOTE: Make sure each new dish is stored in the appropriate list
```


```python
foods = ["biryani","qurma","kabab","palao","nihari",
         "halwa","Zarda","kheer","custurd"]

friends_foods = foods.copy()

foods.insert(len(foods),"mutter palao")
friends_foods.insert(len(friends_foods),"pasta")

print(foods)
print(friends_foods)
```

    ['biryani', 'qurma', 'kabab', 'palao', 'nihari', 'halwa', 'Zarda', 'kheer', 'custurd', 'mutter palao']
    ['biryani', 'qurma', 'kabab', 'palao', 'nihari', 'halwa', 'Zarda', 'kheer', 'custurd', 'pasta']
    


```python
print('"my favourite pezzas are:"')
for a in foods:
    print(a)
    
print("\n")

print("\"My friend's favourite foods are:\"")
for b in friends_foods:
      print(b)
```

    "my favourite pezzas are:"
    biryani
    qurma
    kabab
    palao
    nihari
    halwa
    Zarda
    kheer
    custurd
    mutter palao
    
    
    "My friend's favourite foods are:"
    biryani
    qurma
    kabab
    palao
    nihari
    halwa
    Zarda
    kheer
    custurd
    pasta
    


```python

```
