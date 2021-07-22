# Python Control Flow

<img class="fragment" src="../images/Python-logo.png" width="400" height="400">



### Control Flow

allows different code to execute depending on a condition.  <!-- .element: class="fragment" data-fragment-index="1" -->

the keywords:  <!-- .element: class="fragment" data-fragment-index="2" -->

`if`  <!-- .element: class="fragment" data-fragment-index="3" -->

`elif`  <!-- .element: class="fragment" data-fragment-index="4" -->

`else`  <!-- .element: class="fragment" data-fragment-index="5" -->




<section data-auto-animate>
<pre data-id="code-animation"><code data-line-numbers="2|3|4">
condition = True
if condition:
    print("The condition is", condition)
else:
    print("Everything else must be false!!!")
</code></pre>
</section>
<section data-auto-animate>
<pre data-id="code-animation"><code data-line-numbers="2|5|6">
condition = False
if condition:
    print("The condition is", condition)
else:
    print("Everything else must be false!!!")
</code></pre>
</section>
<section data-auto-animate>
<pre data-id="code-animation"><code data-line-numbers="3|6,7">
condition = False
other_condition = True
if condition:
    print("The condition is", condition)
elif other_condition:
    print("The other condition is", other_condition)
else:
    print("Everything else must be false!!!")
</code></pre>
</section>
<section data-auto-animate>
<pre data-id="code-animation"><code data-line-numbers="4|2|3|4|9|10">
condition = False
other_condition = False
yet_another_condition = True
if condition:
    print("The condition is", condition)
elif other_condition:
    print("The other condition is", other_condition)
elif yet_another_condition:
    print("The other condition is", other_condition)
else:
    print("Everything else must be false!!!")
</code></pre>
</section>



[Jupyter Notebooks](http://localhost:8888/notebooks/Desktop/intro_python/07_controlFlow.ipynb)