## Understanding the Problem

- metaphore surgeon operating a knee where the tumour is on the head

## Design a Solution with Python

- divide the problem into small pieces

## The Importance of the Function in Programming

- why is the function what you should always search for

## What happens when you execute a `function()` in Python?

```python
import pandas
pandas.read_excel(io='data.xlsx', sheet_name=0)
```

1. `library`
    - pandas
2. `.` **DOT NOTATION** to access functions inside the library
3. `function()`
    - read_excel()
4. `(parameter=object)` pass objects to the parameters
    - `io='data.xlsx'`, we pass the `string` object `'data.xlsx'` to the parameter `io`
        - because it's the name of the `Excel` file we want to load
    - `sheet_name=1`, we pass the `integer` object `0` to the parameter `0`
        - beacuse it's the position of the `Sheet` we want to load
5. Execute
6. Magic
7. The `function()` returns an `object`