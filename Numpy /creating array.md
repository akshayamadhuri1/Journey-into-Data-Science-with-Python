## Creating a Numpy Array

The most common way to create a `Numpy` array is by using the `numpy.array()`
function. You can pass any sequence-like object into this function, and it will be converted into an array. Let's convert a regular `Python` list into a `Numpy` array:

```python
import numpy as np

# Create a Python list
py_list = [1, 2, 3, 4, 5]

# Convert list to a Numpy array
np_array = np.array(py_list)

print(np_array) # Output: [1 2 3 4 5]
```

Executing these lines creates a one-dimensional Numpy array `np_array` with the same elements as our regular Python list `py_list`.

We can also create two-dimensional arrays (similar to matrices). Let's convert a list of lists into a 2D Numpy array:

```python
import numpy as np
# Create a 2D Python list
py_list_2d = [[1, 2, 3], [4, 5, 6], [7, 8, 9]]
# Convert list to a Numpy array
np_array_2d = np.array(py_list_2d)
print(np_array_2d)

# Output:
# [[1 2 3]
#  [4 5 6]
#  [7 8 9]]
```
We now have a two-dimensional Numpy array `np_array_2d`, with each sub-list of `py_list_2d` as a row in `np_array_2d`.
