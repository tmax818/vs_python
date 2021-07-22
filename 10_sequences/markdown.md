# Python Sequence Types

<img class="fragment" src="../images/Python-logo.png" width="400" height="400">



## Sequences

list <!-- .element: class="fragment" data-fragment -->

```python
my_list = ["spam", "eggs", "bacon"]
``` 

tuple <!-- .element: class="fragment" data-fragment -->

```python
my_tuple = ("John", 37, True)
``` 

range <!-- .element: class="fragment" data-fragment -->

```python
start = 2
stop = 100
step = 2
my_range = range(start, stop, step)
``` 



## Common Operations

<div class="fragment fade-in-then-out">

```python
my_list = ["spam", "eggs", "bacon"]
"spam" in my_list
# True
``` 
</div>

<div class="fragment fade-in-then-out">

```python
my_list = ["spam", "eggs", "bacon"]
"spam" not in my_list
# False
``` 
</div>

<div class="fragment fade-in-then-out">

```python
my_numbers = (11, 42, 35, 84, 500)
len(my_numbers)
# 5
min(my_numbers)
# 11
max(my_numbers)
# 500
``` 
</div>



## Slicing

[start, stop, step]




[Jupyter Notebooks](http://localhost:8888/notebooks/Desktop/intro_python/10_sequences.ipynb)