Ans1)

```python
l, u, p, d = 0, 0, 0, 0
s = input()

capitalalphabets="ABCDEFGHIJKLMNOPQRSTUVWXYZ"

smallalphabets="abcdefghijklmnopqrstuvwxyz"

specialchar="$@_"

digits="0123456789"

if (len(s) >= 10):

    for i in s:
 

        # counting lowercase alphabets

        if (i in smallalphabets):

            l+=1           
 

        # counting uppercase alphabets

        if (i in capitalalphabets):

            u+=1           
 

        # counting digits

        if (i in digits):

            d+=1           
 

        # counting the mentioned special characters

        if(i in specialchar):

            p+=1       

if (l>=1 and u>=1 and p>=1 and d>=1 and l+p+u+d==len(s)):

    print("Valid Password")

else:

    print("Invalid Password")
```

     We43@


    Invalid Password


Ans2)

```python
fruits = ['apple','banana','orange','mango','avocado']
name1 = 'a'
name = list(filter(lambda x: x.startswith(name1), fruits))
print("The list will be : " + str(name))
```

    The list will be : ['apple', 'avocado']



```python
numbers = "2341"
print (numbers.isnumeric())
```

    True



```python
fruits1 = [("mango",99),("orange",80), ("grapes", 1000)]
fruits1.sort(key=lambda a: a[1])
print(fruits1)
```

    [('orange', 80), ('mango', 99), ('grapes', 1000)]



```python
square = [1,2,3,4,5,6,7,8,9,10]
list(map(lambda x : x**2 , square ))
```




    [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]




```python
cube = [1,2,3,4,5,6,7,8,9,10]
list(map(lambda x : x**3 , cube ))
```




    [1, 8, 27, 64, 125, 216, 343, 512, 729, 1000]




```python
a = [1,2,3,4,5,6,7,8,9,10]
list(map(lambda x : x%2==0 , a))
```




    [False, True, False, True, False, True, False, True, False, True]




```python
b = [1,2,3,4,5,6,7,8,9,10]
list(filter(lambda x : x%2 !=0 , b))
```




    [1, 3, 5, 7, 9]




```python
c = [1,2,3,4,5,6,-1,-2,-3,-4,-5,0] 
list(filter(lambda x : x>0 , c))
```




    [1, 2, 3, 4, 5, 6]




```python
list(filter(lambda x : x<0 , c))
```




    [-1, -2, -3, -4, -5]




```python

```


```python

```


```python

```

