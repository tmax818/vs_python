# Python Lists

<img class="fragment" src="../images/Python-logo.png" width="400" height="400">



## Lists

a sequence of comma-separated items <!-- .element: class="fragment" data-fragment -->


list <!-- .element: class="fragment" data-fragment -->

```python
my_list = ["spam", "eggs", "bacon"]
``` 


## Common List Operations


<div class="fragment fade-in-then-out">
<h2>Add an item to a list</h2>

```python
my_list = ["spam", "eggs", "bacon"]
my_list.append("lobster thermidor")

my_list = ["spam", "eggs", "bacon"]
my_list.insert(1, "lobster thermidor")
``` 
</div>

<div class="fragment fade-in-then-out">
<h2>Remove an item from a list</h2>

```python
my_list = ["spam", "eggs", "bacon", "lobster thermidor"]
my_list.pop("lobster thermidor")

my_list = ["spam", "eggs", "bacon"]
my_list.remove("spam")
``` 
</div>



[Jupyter Notebooks](http://localhost:8888/notebooks/Desktop/intro_python/10.1_lists.ipynb)