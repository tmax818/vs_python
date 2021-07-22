# Python Loops

<img class="fragment" src="../images/Python-logo.png" width="400" height="400">



## Loops 

Loops allow the repetion of a statement until a condition is met.

`while`  <!-- .element: class="fragment" data-fragment-index="1" -->

`for`  <!-- .element: class="fragment" data-fragment-index="2" -->



<section data-auto-animate>
<pre data-id="code-animation"><code data-line-numbers>
condition = True
while condition:
</code></pre>
</section>
<section data-auto-animate>
<pre data-id="code-animation"><code data-line-numbers>
condition = True
while condition:
    print("Hello World")
</code></pre>
</section>
<section data-auto-animate>
<pre data-id="code-animation"><code data-line-numbers>
condition = True
while condition:
    print("Hello World")
# Hello World
# Hello World
# Hello World
# Hello World
# Hello World
...
</code></pre>
</section>
<section data-auto-animate>
<pre data-id="code-animation"><code data-line-numbers=>
condition = True
while condition:
    print("Hello World")
# Hello World
# Hello World
# Hello World
# Hello World
# Hello World
# Hello World
# Hello World
# Hello World
# Hello World
# Hello World
# Hello World
# Hello World
...
</code></pre>
</section>
<section data-auto-animate>
<pre data-id="code-animation"><code data-line-numbers=2|3|4|6|5|3|7>
condition = True
while condition:
    print("Hello World")
    condition = False
# Hello World
# exit the loop
</code></pre>
</section>




[Jupyter Notebooks](http://localhost:8888/notebooks/Desktop/intro_python/08_loops.ipynb)