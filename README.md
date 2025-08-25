# Experiment-1
##  Write programs in Python Language to demonstrate the working of
followingconstructs with possible test cases: a) do…while b) while…do c)
if …else d) switch e) for

## a) Aim
To write python programs for do…while, while, for, switch and if…else and test with possible test
cases.

## Algorithm
1.	Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4. Test the program with possible test cases.
5. Stop the program. 

## Program
# 1. Do-while:
```python
def do_while_example(start):
    result = []
    while True:
        result.append(start)
        start += 1
        if start > 5:
            break
    return result
def test_1():
    assert do_while_example(2) == [2, 3, 4, 5]
def test_2():
    assert do_while_example(2) == [2, 3, 4]
```

# 2. while:
```python
def while_loop_example(start):
    result = []
    while start < 5:
        result.append(start)
        start += 1
    return result

def test_while_loop_1():
    assert while_loop_example(2) == [2, 3, 4]

def test_while_loop_2():
    assert while_loop_example(2) == [2, 3]
```

# 3. for:
```python
def for_loop_example(start):
    result = []
    for i in range(start, 5):
        result.append(i)
    return result

def test_for_loop_1():
    assert for_loop_example(2) == [2, 3, 4]

def test_for_loop_2():
    assert for_loop_example(2) == [2, 3]
```

# 4. Switch:
```python
def switch_example(value):
    match value:
        case 1:
            return "One"
        case 2:
            return "Two"
        case _:
            return "Other"

def test_switch_1():
    assert switch_example(1) == "One"
    assert switch_example(2) == "Two"
    assert switch_example(5) == "Other"

def test_switch_2():
    assert switch_example(1) == "Two"
```

# 5. if else:
```python
def if_else_example(num):
    if num > 5:
        return "Greater"
    else:
        return "Smaller or equal"

def test_if_else_1():
    assert if_else_example(7) == "Greater"
    

def test_if_else_2():
    assert if_else_example(7) == "Smaller or equal"
```

## Output:
# 1. Do-while:
<img width="1644" height="579" alt="image" src="https://github.com/user-attachments/assets/b038565a-4443-4e20-91e3-856209cf5f62" />

# 2. while:
<img width="1641" height="575" alt="image" src="https://github.com/user-attachments/assets/219fbea5-61da-4d71-b105-59ac77fd68a7" />

# 3.for:
<img width="1646" height="567" alt="image" src="https://github.com/user-attachments/assets/1fed43a0-2954-4bf9-a82d-d785b8f162ab" />

# 4.Switch:
<img width="1627" height="564" alt="image" src="https://github.com/user-attachments/assets/d4eeb61b-9774-4938-8637-2ed774b4e7a1" />

# 5.if else:
<img width="1623" height="558" alt="image" src="https://github.com/user-attachments/assets/dd39c194-68a0-41bf-aec0-4e5e4338d7ba" />


## Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.



