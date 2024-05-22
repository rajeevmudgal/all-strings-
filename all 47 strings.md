```python
#file_path1 = "C:\\Users\\rajee\\Desktop\\python.folder\\ram.py"
file_path2 = "C:/Users/rajee/Desktop/python.folder/ram.py"
#file_path3 = r"C:\Users\rajee\Desktop\python.folder\ram.py"

with open(file_path3) as file:
    content = file.read()

print(content)
```

    print("hello i'm ram")
    import rajeev.py
    print("hello world")
    


```python
str = "my name is rajeev sharma"
print(str.capitalize())
```

    My name is rajeev sharma
    


```python
str = "MY NAME IS RAJEEV SHARMA"
print(str.lower())
```

    my name is rajeev sharma
    


```python
str = "my name is rajeev sharma, name is not defined everything"
print(str.replace("name","work"))
```

    my work is rajeev sharma, work is not defined everything
    


```python
str = "my name is rajeev sharma"
print(str.title())
```

    My Name Is Rajeev Sharma
    


```python
str = "my name is,rajeev sharma"
print(str.count("sharma rajeev my name is"))
```

    0
    


```python
str = "MY NAME IS RAJEEV"
print(str.isupper())
```

    True
    


```python
str = "My Name Is Rajeev sharma"
print(str.swapcase())
```

    mY nAME iS rAJEEV SHARMA
    


```python
str1 = "my name is rajeev sharma"
str2 = "and my native place is gwalior"
print(str.join("str1""str2"))
```

    smy name is rajeev sharma , and my native place is gwaliortmy name is rajeev sharma , and my native place is gwaliorrmy name is rajeev sharma , and my native place is gwalior1my name is rajeev sharma , and my native place is gwaliorsmy name is rajeev sharma , and my native place is gwaliortmy name is rajeev sharma , and my native place is gwaliorrmy name is rajeev sharma , and my native place is gwalior2
    


```python
str = "8871447845"
print(str.isdigit())
```

    True
    


```python
str = "my name is rajeev sharma"
print(str.format())
```

    my name is rajeev sharma
    


```python
str = "ram989ramis8"
print(str.isascii())
```

    True
    


```python
str = "my name is rajeev sharma"
print(str.islower())
```

    True
    


```python
str = "My Name Is Rajeev Sharma"
print(str.isprintable())
```

    True
    


```python
str = "My Name Is Rajeev Sharma"
print(str.swapcase())
```

    mY nAME iS rAJEEV sHARMA
    


```python
str = "American standard authority"
print(str.swapcase())
```

    aMERICAN STANDARD AUTHORITY
    


```python
str = "my name is rajeev sharma"
print(str.upper())
```

    MY NAME IS RAJEEV SHARMA
    


```python
str = "MY NAME IS RAJEEV SHARMA"
print(str.isupper())
```

    True
    


```python
str = "MY NAME IS MUDGAL"
print(str.lower())
```

    my name is mudgal
    


```python
str = "my name is mudgal"
print(str.upper())
```

    MY NAME IS MUDGAL
    


```python
str = "Rajeev sharma"
print(str.swapcase())
```

    rAJEEV SHARMA
    


```python
str = "345676"
print(str.isnumeric())
```

    True
    


```python
str = "my name is rajeev sharma mob 887\1447827"
print(str.isprintable())
```

    True
    


```python
str = "RAJEEV SHARMA"
print(str.lower())
```

    rajeev sharma
    


```python
str = "RAJEEV SHARMA"
print(str.islower())
```

    False
    


```python
str = "Rajeev Sharma"
print(str.istitle())
```

    True
    


```python
str = "rajeev sharma"
print(str.title())
```

    Rajeev Sharma
    


```python
str = "#####RajeevSharma#####"
print(str.rfind("#"))
```

    21
    


```python
str = "rajeev sharma is good boy his native place is gwalior"
print(str.find("is"))
```

    14
    


```python
str = "887144 rajeev sharma"
print(str.startswith("887144"))
```

    True
    


```python
str = "Rajeev Sharma  8871444"
print(str.casefold())
```

    rajeev sharma  8871444
    


```python
str = "rajeev sharma"
print(str.upper())
```

    RAJEEV SHARMA
    


```python
str = "I like Clean and Green Gwalior 451266"
print(str.title())
```

    I Like Clean And Green Gwalior 451266
    


```python
str1 = "Hello World! Hello Hello"
print(str1.count("Hello"))
```

    3
    


```python
str1 = "Hello World! Hello Hello"
print(str1.find("Hello",15,30))
```

    19
    


```python
str = "Hello World Hello Hello"
print(str.index("Hello"))
```

    0
    


```python
str = "Hello World Hello Hello!"
print(str.endswith("Hello!"))
```

    True
    


```python
str = "Hello World Hello Hello!"
print(str.startswith("Hello"))
```

    True
    


```python
# is alpha numeric
#str = "rajeevsharma@15061gmail.com"
print(str.isalnum())

str = "rajeevsharma15061"
print(str.isalnum())

```

    False
    True
    


```python
#str = "rajeev sharma \n my name is rajeev sharma"
print(str.isspace())

str1 = "rajeev_mudgal"
print(str.isspace())
```

    False
    False
    


```python
str = "      rajeev sharmaf"
print(str.lstrip())
```

    rajeev sharmaf
    


```python
#str = "    rajeev sharma     "
print(str.rstrip())

str = "rajeev sharma    "
print(str.rstrip())
```

        rajeev sharma
    rajeev sharma
    


```python
str = "        rajeev sharma                                  "
print(str.strip())
```

    rajeev sharma
    


```python
str = "Helloworld"
str1 = "-"   #separator
print(str.join("str+str1"))
```

    sHelloworldtHelloworldrHelloworld+HelloworldsHelloworldtHelloworldrHelloworld1
    


```python
#str = "India is a Great Country"
print(str.partition("is"))

str = "India is a Great Country"
print(str.partition("are"))
```

    ('India ', 'is', ' a Great Country')
    ('India is a Great Country', '', '')
    


```python
#str = "India is a Great Country"
print(str.split())

str = "india is a great cournty"
print(str.split("a"))
```

    ['India', 'is', 'a', 'Great', 'Country']
    ['indi', ' is ', ' gre', 't cournty']
    


```python
str = "MaRiya"
print(str.casefold())
```

    mariya
    


```python
str = "rajeev sharma"
print(str.center(50))

```

                      rajeev sharma                   
    


```python
str = "abc_abc_abc_abc"
print(str.count("bc"))
```

    4
    


```python
str = "Elon Musk"
print(str.encodes(encoding="UTF-8", errors="strict"))
```


    ---------------------------------------------------------------------------

    AttributeError                            Traceback (most recent call last)

    Cell In[12], line 2
          1 str = "Elon Musk"
    ----> 2 print(str.encodes(encoding="UTF-8", errors="strict"))
    

    AttributeError: 'str' object has no attribute 'encodes'



```python
str = "text\ttext2\ttext3"
print(str.expandtabs(20))
```

    text                text2               text3
    


```python
str = "Indian peoples are doing well"
position: int = str.find("peoples")
print(position)
print(str[position:])
```

    7
    peoples are doing well
    


```python
text: str = "{subject} is doing: {action}."
print(text.format(subject="cat", action="meow"))

text: str = "{} is doing: {}." #alternative
print(text.format("cat", "meow"))
```

    cat is doing: meow.
    cat is doing: meow.
    


```python
# format_map()
coordinates: dict = {"x": 10, "y": -5}
text: str = "coordinates: ({x}, {y})"
print(text.format_map(coordinates))
```

    coordinates: (10, -5)
    


```python
# index()
text: str = "Astronauts recently discovered a banana on the moon?"
position: int = text.index("banana")
print(position)
print(text[position:])
```

    33
    banana on the moon?
    


```python
#isdecimal()
text: str = "1234"
print(text.isdecimal())

#isnumeric
str = "45785"
print(str.isnumeric())

#isdigit()
str = "45656"
print(str.isdigit())
```

    True
    True
    True
    


```python
# isidentifier()
str = "test-sample"
print(str.isidentifier())


str = "test_sample"
print(str.isidentifier())
```

    False
    True
    


```python
# isprintable()
str = "text"
print(str.isprintable())
```

    True
    


```python
# isspace()
str = "        "
print(str.isspace())
```

    True
    


```python
# istitle()
str = "The Video"
print(str.istitle())
```

    True
    


```python
#join()
str = "++"
print(str.join(["text1","text2","text3"]))
```

    text1++text2++text3
    


```python
# ljust()
str = "text"
print(str.ljust(20, "_"))
```

    text________________
    


```python
# maketrans()
text: str = "That is Rahul"
table = text.maketrans("R", "e")
print(table)

#translate()
print(text.translate(table))
```

    {82: 101}
    That is eahul
    


```python
#partition()
text: str = "a+b=c"
print(text.partition("="))
```

    ('a+b', '=', 'c')
    


```python
#removeprefix()
text: str = "endless"
print(text.removeprefix("end"))
```

    less
    


```python
#removesuffix()
text: str = "everything"
print(text.removesuffix("thing"))
```

    every
    


```python
#rjust()
str = "text"
print(str.rjust(20, "_"))
```

    ________________text
    


```python
#rpartition()
str = "text=text2=text3"
print(str.rpartition("+"))
```

    ('', '', 'text=text2=text3')
    


```python
#strip()
text: str = "This is some special stuff"
print(text.strip("maxstrip=2"))

#rstrip()
text: str = 'his name is Mario Mario'
print(text.rstrip("Mario"))


```

    This is some special stuff
    his name is Mario 
    


```python
# splitlines()
text: str = "Remember to comment!\nor else...\n"
print(text.splitlines(keepends=True))
```

    ['Remember to comment!\n', 'or else...\n']
    


```python
# zfill()
text: str = "text"
print(text.zfill(20))

text: str = "happy"
print(text.zfill(80))
```

    0000000000000000text
    000000000000000000000000000000000000000000000000000000000000000000000000000happy
    


```python

```
