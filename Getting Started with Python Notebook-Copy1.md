

```python
print('Hello World!!')
```

    Hello World!!


# Getting started with Python
## We have done
* Installed Python
* Started IPython Notebook

## Create some variables in Python


```python
i=4 #int
```


```python
type(i)
```




    int




```python
f=4.1
```


```python
type(f)
```




    float




```python
b=True #boolean
```


```python
s="This is a string!"
```


```python
print (s)
```

    This is a string!


## Advanced python types


```python
l=[3,1,2]
```


```python
print(l)
```

    [3, 1, 2]



```python
d={'foo':1,'bar':2.3,'s':'my first dictionary'}
```


```python
print(d['foo'])
```

    1



```python
n=None
```


```python
type(n)
```




    NoneType



## Advanced printing


```python
print ("Our float value is %s. Our int value is %s"%(f,i))
```

    Our float value is 4.1. Our int value is 4


## Conditional statements in python


```python
if i==1 and f>4:
    print("The value of i is 1 and f is ...")
elif i>4 or f>4:
    print ("i and f are both greater than 4.")
else:
    print ("both i and f are less... ")
```

    i and f are both greater than 4.


## Conditional loops


```python
print(l)
```

    [3, 1, 2]



```python
for e in l:
    print (e)
```

    3
    1
    2



```python
counter=6
while counter<10:
    print(counter)
    counter+=1
```

    6
    7
    8
    9


## Creating functions in python


```python
def add2(x):
    y=x+2
    return y
```


```python
i=5
```


```python
add2(i)
```




    7




```python
square=lambda x: x*x
```


```python
square(3)
```




    9




```python

```
