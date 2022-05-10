# python-program
python-program


## Odd number checking here
-------------------------------------------------- 

```py
number = input("Enter a number here: ")

if int(number) % 2 == 0:

  print("ok")

else:
    
  print("no")

```

## Check the enterd value start with vowel
-------------------------------------------------- 

```py
value = input("Enter the word here : ")

print("The program start here")

con = value.lower()

first = con[0]

vowel = ('a', 'e', 'i', 'o', 'u')

if first in vowel:

  print("Ok") 

else:
  
  print("no")
```

## Check the enterd value start with vowel --Method 2
-------------------------------------------------- 

```py
value = input("Enter a character: ")

con = value.lower()

first = con[0]

if ( "a" == first or "e" == first or "i" == first or "o" == first or "u" == first):
  print("Ok")
else:
  print("No")
```

## String and substring
-------------------------------------------------- 

```py
string = input("Enter the string : ")

substring = input("Enter the substring: ")

if substring in string:
  
  print("Ok")

else:

  print("No")
```


## character check

-------------------------------------------------- 

```py
string = input("Enter a string : ")

con = string.lower()

first = con[0]

last = con [-1]

if first == last:

  print("Ok")

else:

  print("No")
  ```
