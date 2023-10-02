# Some Python functions that might be useful for the further use


### Creating the function that sums up the squared values of a, b, c
```{py}
def square(x):
    y = x ** 2
    return y

def sum_of_square(x,y,z):
    a = square(x)
    b = square(y)
    c = square(z)
    return a+b+c

q = 2    #I added another q,w,e so they can be changed to any numbers
w = -5
e = 5
result = sum_of_square(q, w, e)
print(result)
```
54
### The function to sum up the square root of numbers

```{py}
def square_root(x):
    y = x ** 0.5
    return y

def sum_of_square_root(a, b, c, d):
    x = square_root(a)
    y = square_root(b)
    z = square_root(c)
    k = square_root(d)
    return x+y+z+k
q = 16
w = 25
e = 100
r = 121
result = sum_of_square_root(q, w, e, r)
print(result)
```
30

### Codes to get the sum of the odd numbers within 1000 in 3 different ways
```{py}
# N1
sum = 0
for n in range(1,1001,2):
    sum += n
print(sum)

# N2
sum = 0
n = 1
while n < 1000:
    if n%2==1: #separating the odd numbers
        sum += n
    n = n + 1
print(sum)
        
# N3
sum = 0
for i in range(1000):
    if i%2==1:
        sum += i
print(sum)
```
25000
25000
25000
