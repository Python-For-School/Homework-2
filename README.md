### Problem 1:

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

### Problem 2:

```python
numbers = []
for iteration in range(6):
    numbers.append(int(input("Enter number motherfucker: "))) 
for index in range(6):
    print(index)
    if (index % 2):
        print("ODD: " + str(numbers[index]))
    else:
        print("EVEN: " + str(numbers[index]))
```
### Problem 3:
```py
numbers = []
for index in range(6):
    numbers.append(int(input("Please enter a number: ")))
temp = numbers[0]
for index in range(5):
    numbers[index] = numbers[index + 1]
numbers[-1] = temp

print(numbers)
```
