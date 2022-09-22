## Problem 1:

```python
numbers = []
flag = 1
while flag != 0:
    if len(numbers) > 5: 
        flag = 0
        pass
    number = int(input("Enter number mother fucker: "))
    if number > 9 and number < 100:
        numbers.append(number)
        
numbers.sort() 
print(numbers[0])
print(numbers[-1])
```
