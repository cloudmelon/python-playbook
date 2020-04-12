# Play 2 String formatting functions

## Single quotes or double quotes ? 

In general you can use single quote it works perfectly !

```
print('hello wonderful world')
```
At some point, you'll need to use double quote such as the following when the string itself contains a single quote: 

```
print("It's a small world after all")
```
## modify the strings 
The following functions you can use to modify the strings :

```
sample_input = input('what is your impression on our world ?')
sample_str = 'Hello ' + sample_input +' world'

print(sample_str.upper())
print(sample_str.lower())
print(sample_str.capitalize())
print(sample_str.count('o'))

print(sample_str + ' ' \
    + sample_str.upper() + '!')

```

The sample output will look like the following : 

<img src="Screenshots/str_functions.PNG" alt="string functions" width="600px"/>


## Formatting the strings

Putting in place holders with curly braces 

```
your_greetings = 'Hello'
your_name = 'cloudmelon'

str_output = 'hello,{0} {1}'.format(your_greetings, your_name)

# Below is only working in Python 3
str_output_py3 = f'{your_greetings} {your_name}'

print(str_output)
print('In Python 3 : ', str_output_py3)

```

The sample output will look like the following : 

<img src="Screenshots/str_formatting.PNG" alt="string formatting" width="600px"/>


## Playing with numbers 

You can use the variables the define numbers of your choice, you'll need to play with math with numbers,  you can use the following operators : 
- Addition (+)
- Subtraction (-)
- Multiplication (*)
- Division(/)
- Exponent (**) such as 7 to the power of 3 = 73 = 343 ( To stick with 7 to the power of 3 as an example, insert 7 for the base and enter 3 as the index, also known as exponent or power.) 

You can use such things as follows :

```
num_1 = 6
num_2 = 3


# Time to play with math :)
print(num_1 + num_2) 
print(num_1 - num_2) 
print(num_1 / num_2)
print(num_1 * num_2)
print(num_1 ** num_2)

```

Expecting the output would be as the following : 

<img src="Screenshots/num_math.PNG" alt="num math" width="600px"/>

## Playing with string and numbers 

In this case, Python is getting confused sometimes, so you need to tell them exactly what data types in your program, this is where conversion comes in, the previous program could be improved as the following : 

```
num_1 = int(input('Input your 1st number : '))
num_2 = int(input('Input your 2nd number : '))


# Time to play with math :)
print ('Addition is ')
print (num_1 + num_2) 

print('Subtraction is ' ) 
print(num_1 - num_2)

print('Division is ' )
print(num_1/num_2)

print('Multiplication is ' )
print(num_1*num_2)

print('Exponent is ' )
print(num_1**num_2)


```

Expecting the output would be as the following : 

<img src="Screenshots/num_str_math.PNG" alt="num str math" width="600px"/>