# Programming and Scripting Problem Set Solutions 2021

## Summary of Assignment
<p>This repository contains my programming and scripting problem sheet 2021. In this eight weeks, was developed skills in, github, Matplolib, Seaborn, NumPy and Pandas.</p>


## 1-BMI.py week 02
<p>1- Write a program that calculates somebody’s Body Mass Index (BMI) The inputs are the person's height in centimetres and weight in kilograms. The output is their weight divided by their height in metres squared. Body Mass Index is a method for screening the relative weight of a person, and is measured by taking the person's weight in kilograms divided by the square of height in metres.</p>

### Code

<p><b>#set variables weight and height and collect user input</b> <br> weight = float(input("Enter your weight in kilograms: "))<br>height = float(input("Enter your height in centimeters: "))</p>

<p><b>#perform BMI calculation conversion of height cm to meters</b> <br> height_meters = height / 100<br> bmi = weight / (height_meters  ** 2)</p>

<p><b>#print formatting method may not work in older versions python</b><br> print('BMI is: {}.'.format(round(bmi, 2)))</p>

<b>References:</b><br>https://www.ramsayhealth.co.uk/weight-loss-surgery/bmi/bmi-formula<br>Lectures



## 2-Secondstring.py week 03
<p>1- Write a program that takes asks a user to input a string and outputs every second letter in reverse order.</p>

### Code
<p><b>#type:  The quick brown fox jumps over the lazy dog.</b><br>sentence = input("Type a sentence that you want reversed:")</p>

<p><b>#reverse a sentence every second letter in reverse order. [::-2] get 2 in 2 letters</b><br>
print(sentence[::-2])


<b>References:</b><br> https://djangocentral.com/reverse-a-sentence/<br>Used lecture on Tuesday program as a base for the problem.


## 3-Collatz.py week 04
<p>1- Write a program that asks the user to input any positive integer and outputs the successive values of the following calculation.<br>At each step calculate the next value by taking the current value and, if it is even, divide it by two, but if it is odd, multiply it by three and add one.<br>Have the program end if the current value is one.</p>

### Code
<p>#Defining the function<br>def collatz(number):<p/>

 # If the number is negative print "Unfortunately this is not a positive Integer."
 if number <= 0:
       print("Unfortunately this is not a positive Integer.") 
       quit() 
       
# looping through and if number found is even divide it by 2
 elif number % 2 == 0:
        print(number // 2)
        return number // 2

 elif number % 2 == 1:
        result = 3 * number + 1
        print(result)
        return result
       
# Type the number
n = input("Type a number: ")

# running the function togethe final result number 1
while n != 1:
    n = collatz(int(n))


# Reference:
# https://stackoverflow.com/questions/45990261/implementing-the-collatz-function-using-python
# Used lecture



## 4-Weekday.py week 05
<p>1- Write a program that calculates somebody’s Body Mass Index (BMI) The inputs are the person's height in centimetres and weight in kilograms. The output is their weight divided by their height in metres squared.</p>

### Code

## 5-Squareroot.py week 06
<p>1- Write a program that calculates somebody’s Body Mass Index (BMI) The inputs are the person's height in centimetres and weight in kilograms. The output is their weight divided by their height in metres squared.</p>

### Code

## 6-Es.py week 07
<p>1- Write a program that calculates somebody’s Body Mass Index (BMI) The inputs are the person's height in centimetres and weight in kilograms. The output is their weight divided by their height in metres squared.</p>

### Code

## 7-Plottask.py week 08
<p>1- Write a program that calculates somebody’s Body Mass Index (BMI) The inputs are the person's height in centimetres and weight in kilograms. The output is their weight divided by their height in metres squared.</p>

### Code
