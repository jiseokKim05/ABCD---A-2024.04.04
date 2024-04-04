# ABCD---A 2024.04.04

```python
# Quiz 1

a = '★'

for i in range(3):
  for j in range(1):
    print(a * 4)
```

```python
# Quiz 2

a = '★'

for i in range(3):
  print(a * 4)
```
```python
# Quiz 3

horizontal_stars = '★★★'
vertical_repeats = '★★★★' 

for i in vertical_repeats:
  print(horizontal_stars)
```

```python
#Quiz 4

star = '*'

horizental_stars = star * 3

for i in range(4):
  print(horizental_stars)
```

```python
#Quiz 5 - 1 
import math
 
R = int(input("반지름을 설정해주세요 "))
h = int(input("높이를 설정해주세요 "))

Result = (math.pi * (R*R)) * h 
R_R = round(Result, 3) 

print(R_R)
```

```python
#Quiz 5 - 2
import math

R = 5
h = 10

Result = (math.pi * (R*R)) * h 
R_R = round(Result, 3) 

print(R_R)
```

```python
#Quiz 6-1

import datetime

x = datetime.datetime.now()

print(x)
```

```python
#Quiz 6-2

import datetime

x = datetime.datetime.now()
weekday_index = x.weekday()
weekdays = ["월", "화", "수", "목", "금", "토", "일"]

print(x.year, "년")
print(x.month, "월")
print(x.day, "일")
print(weekdays[weekday_index], "요일")
print(x.hour, "시")
print(x.minute, "분")
print(x.second, "초")
```

```python
# Quiz 7

tall = (177, 146, 168, 189, 160, 164, 185, 174, 194, 188)

for tall in tall:
    if tall <= 170:
        continue
    print(tall, "cm")
```

```python
# Quiz 8
def star(repeat):
    a = '★'
    for i in range(repeat):
        print(a * 4)

star(3)
```

```python
# Quiz 9
def star(repeat):
    a = '★'
    for i in range(repeat):
        print(a * 4)

star(3)
```

```python
# Quiz 10
def star(repeat):
    a = '★'
    for i in range(repeat):
        print(a * 4)

star(3)
```

```python
# Quiz 11
def star(repeat):
    a = '*'
    for i in range(repeat):
        print(a * 4)

star(3)
```

```python
# Quiz 12-1

def cylinder(R,h):
  result = (math.pi * (R ** 2)) * h
  return round(result, 3)

R = int(input("반지름을 설정해주세요 "))
h = int(input("높이를 설정해주세요 "))

cylinder_v = cylinder(R, h)
print("원기둥의 부피:", cylinder_v)
```

```python
# Quiz 12-2

def cylinder(R,h):
  result = (math.pi * (R ** 2)) * h
  return round(result, 3)

R = 5
h = 10

cylinder_v = cylinder(R, h)
print("원기둥의 부피:", cylinder_v)
```

```python
# Quiz 13 - 1

import datetime

def print_current_datetime():
    x = datetime.datetime.now()
    print(x)

print_current_datetime()
```

```python
#Quiz 13 - 2

import datetime

def print_datetime_datetime():
  x = datetime.datetime.now()
  weekday_index = x.weekday()
  weekdays = ["월", "화", "수", "목", "금", "토", "일"]
  print(x.year, "년")
  print(x.month, "월")
  print(x.day, "일")
  print(weekdays[weekday_index], "요일")
  print(x.hour, "시")
  print(x.minute, "분")
  print(x.second, "초")

print_datetime_datetime()'
```

```python
# Quiz 14

def print_tall_above_limit(tall_list, limit):
    for tall in tall_list:
        if tall <= limit:
            continue
        print(tall, "cm")

tall = (177, 146, 168, 189, 160, 164, 185, 174, 194, 188)

print_tall_above_limit(tall, 170)
```
