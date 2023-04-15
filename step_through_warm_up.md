## Prompt:
I'm teaching my Python class how to do DSA whiteboarding. Part of the process is that after the code, the students should do a "Step Through", meaning they create a Name/Value Table, which is a T table of names on the left and values on the right, and then go through their code block line by line tracking the state of each variable over time with their chosen test case. 

I'd like to provide a warm up exercise to help students practice their Step Throughs. Please respond with 3 python functions, starting with simple and becoming more complex, and the structure of the Name/Value Table associated with that function and chosen input/output wherein the names are filled in by you, and the values are ready for the students to fill in. Make sense?

## Response:

I understand your request. Here are three Python functions with increasing complexity, along with the structure of their respective Name/Value Tables. The tables have variable names pre-filled, and the values are left empty for the students to fill in as they step through the code.

1. Function 1: Add two numbers

```python
def add(a, b):
    result = a + b
    return result
```

Name/Value Table structure for <code>add(3, 4)</code>:

```css
| Name   | Value |
|--------|-------|
| a      |       |
| b      |       |
| result |       |
```

2. Function 2: Calculate the factorial of a number

```python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)
```

Name/Value Table structure for <code>factorial(5)</code>:

```mathematica
| Name   | Value |
|--------|-------|
| n      |       |
| Return |       |
```

Note: Students should track the changes of <code>n</code> and the return values as the function recurses.

3. Function 3: Find the maximum element in a list

```python
def find_max(arr):
    max_value = arr[0]
    for element in arr:
        if element > max_value:
            max_value = element
    return max_value
```

Name/Value Table structure for <code>find_max([3, 7, 1, 5, 2])</code>:

```lua
| Name      | Value |
|-----------|-------|
| arr       |       |
| max_value |       |
| element   |       |
```

Students should focus on updating the <code>max_value</code> and <code>element</code> variables as they iterate through the list.