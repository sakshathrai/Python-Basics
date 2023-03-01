# Area of Triangle :

 Formula for area of triange is area = (1/2)*base*height


```python
base=10.2
height=20.5
area=(1/2)*base*height
print("Area of Triangle : \n")
area
```

    Area of Triangle : 
    104.55



# Data Types:


```python
type(10.2)
```




    float




```python
type(True)
```




    bool




```python
type(1)
```




    int




```python
type("Abcd")
```




    str




```python
type("1234")
```




    str




```python
c1=2+3j
type(c1)
```




    complex




```python
# Round off a float number:
#ex:
foo=1.349439483984983
```


```python
round(foo,2)
```




    1.35




```python
round(foo,4)
```




    1.3494



# Operations:


```python
1+2
```




    3




```python
2/2
```




    1.0




```python
2%10  # reminder is the answer
```




    2




```python
2**3   #power of a number
```




    8




```python
10+2*3  # BODMASS rule, if we need we can use bracket to avoid this rule
```




    16



# Exercise: Numbers in python:

# 1. You have a football field that is 92 meter long and 48.8 meter wide. Find out total area using python and print it.


```python
length=92
breath=48.8
area=length*breath
print("Area of Football field is "+str(round(area,2)))
```

    Area of Football field is 4489.6


# 2. You bought 9 packets of potato chips from a store. Each packet costs 1.49 dollar and you gave shopkeeper 20 dollar. Find out using python, how many dollars is the shopkeeper going to give you back?


```python
no_pac=9
cost=1.49
given=20
amt=no_pac*cost
back=given-amt
print("Shopkeeper gives back "+str(back))
```

    Shopkeeper gives back 6.59


# 3. You want to replace tiles in your bathroom which is exactly square and 5.5 feet is its length. If tiles cost 500 rs per square feet, how much will be the total cost to replace all tiles. Calculate and print the cost using python (Hint: Use power operator ** to find area of a square)


```python
area=5.5**2
cost=500
amt=500*area
print("Total cost for tiles is "+str(amt))
```

    Total cost for tiles is 15125.0


# 4. Print binary representation of number 17


```python
format(17,'b')
```




    '10001'


