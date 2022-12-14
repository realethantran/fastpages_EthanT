---
keywords: fastai
title: Unit 3 Vocabulary (Definitions + Examples)
badges: true
comments: true
author: Ethan Tran
categories: [unit 3, vocabulary]
nb_path: _notebooks/2022-12-8-unit-3-vocabulary.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-12-8-unit-3-vocabulary.ipynb
-->

<div class="container" id="notebook-container">
        
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Variables: A variable is a named container that stores a value that can be changed or updated.</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">X</span> <span class="o">=</span> <span class="mi">5</span>
<span class="nb">print</span><span class="p">(</span><span class="n">X</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>5
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Data Types: Different types of data such as numbers, strings, booleans, and objects that can be stored in variables.</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">X</span> <span class="o">=</span> <span class="s2">&quot;hello&quot;</span>
<span class="nb">print</span><span class="p">(</span><span class="n">X</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>hello
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Assignment Operators: Operators that are used to assign a value to a variable.</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">three</span> <span class="o">=</span> <span class="mi">3</span>
<span class="nb">print</span><span class="p">(</span><span class="n">three</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>3
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Managing Complexity with Variables: Lists, 2D Lists, Dictionaries, Class: Ways of organizing data in a more complex structure.</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">MyList</span> <span class="o">=</span> <span class="p">[</span><span class="mi">1</span><span class="p">,</span><span class="mi">2</span><span class="p">,</span><span class="mi">3</span><span class="p">,</span><span class="mi">4</span><span class="p">,</span><span class="mi">5</span><span class="p">]</span>
<span class="nb">print</span><span class="p">(</span><span class="n">MyList</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>[1, 2, 3, 4, 5]
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Algorithms: A set of instructions for solving a problem.</p>
<p><strong>Example: To find the largest number in a list, you could use a sorting algorithm.</strong></p>
<p>Sequence, Selection, Iteration: Three types of control flow structures in programming.</p>
<p><strong>Example: For a sequence, you could create a loop that prints out each number from 1 to 10.</strong></p>
<p>Expressions, Comparison Operators, Booleans Expressions and Selection, Booleans Expressions and Iteration, Truth Tables: Expressions are used to evaluate values and comparison operators are used to compare values.</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">if</span> <span class="p">(</span><span class="mi">5</span> <span class="o">&gt;</span> <span class="mi">3</span><span class="p">)</span> <span class="ow">is</span> <span class="kc">True</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;True&quot;</span><span class="p">)</span>
<span class="k">else</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;False&quot;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>True
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Characters: Individual letters, numbers, and symbols</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">Characters</span> <span class="o">=</span> <span class="s2">&quot;H&quot;</span>
<span class="nb">print</span><span class="p">(</span><span class="n">Characters</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>H
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Strings: A a combination of characters
Length: The number of characters in a string
Concatenation: A combination of strings together</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">Strings</span> <span class="o">=</span> <span class="s2">&quot;Hello World&quot;</span>
<span class="n">Strings2</span> <span class="o">=</span> <span class="s2">&quot;World Hello&quot;</span>
<span class="nb">print</span><span class="p">(</span><span class="n">Strings</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">Strings</span><span class="p">))</span>
<span class="nb">print</span><span class="p">(</span><span class="n">Strings</span><span class="p">,</span> <span class="n">Strings2</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>Hello World
11
Hello World World Hello
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Upper and Lower: Functions for changing the case of characters</p>
<p>Traversing Strings: Looping over each character in a string.</p>
<p>If, Elif, Else conditionals; Nested Selection Statements: Control statements that allow you to execute code based on certain conditions.</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">x</span> <span class="o">=</span> <span class="mi">5</span>
<span class="k">if</span> <span class="n">x</span> <span class="o">&gt;</span> <span class="mi">0</span><span class="p">:</span>
  <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;x is greater than 0&quot;</span><span class="p">)</span>
<span class="k">elif</span> <span class="n">x</span> <span class="o">==</span> <span class="mi">0</span><span class="p">:</span>
  <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;x is equal to 0&quot;</span><span class="p">)</span>
<span class="k">else</span><span class="p">:</span>
  <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;x is less than 0&quot;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>x is greater than 0
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Python For, While loops with Range, with List: Types of loops that allow you to iterate over a range of numbers or a list of items.</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">random</span>

<span class="n">x</span> <span class="o">=</span> <span class="n">random</span><span class="o">.</span><span class="n">randint</span><span class="p">(</span><span class="mi">0</span><span class="p">,</span><span class="mi">10</span><span class="p">)</span>
<span class="k">for</span> <span class="n">x</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">0</span><span class="p">,</span> <span class="mi">10</span><span class="p">):</span>
  <span class="nb">print</span><span class="p">(</span><span class="n">x</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>0
1
2
3
4
5
6
7
8
9
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Combining loops with conditionals to Break, Continue: Control statements that allow you to break out of a loop or skip an iteration.</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">x</span> <span class="o">=</span> <span class="mi">2</span>

<span class="k">while</span> <span class="n">x</span> <span class="o">&lt;</span> <span class="mi">10</span><span class="p">:</span>
  <span class="k">if</span> <span class="n">x</span> <span class="o">==</span> <span class="mi">5</span><span class="p">:</span>
    <span class="k">break</span>
  <span class="n">x</span> <span class="o">+=</span> <span class="mi">1</span>

<span class="nb">print</span><span class="p">(</span><span class="n">x</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>5
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Procedural Abstraction: A process used to simplify complex tasks by breaking them down into smaller, easier-to-manage tasks.</p>
<p>Python Def Procedures: A method used to define a set of instructions to be executed when a certain procedure is called.</p>
<p>Parameters: Arguments that are passed to a procedure when it is called.</p>
<p>Return Values: A value that is returned after a procedure has been executed.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Selection: Selection is a type of control flow that allows for the execution of certain code based on certain conditions.</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">firstNum</span> <span class="o">=</span> <span class="nb">int</span><span class="p">(</span><span class="nb">input</span><span class="p">(</span><span class="s2">&quot;Input your first number.&quot;</span><span class="p">))</span>
<span class="n">secondNum</span> <span class="o">=</span> <span class="nb">int</span><span class="p">(</span><span class="nb">input</span><span class="p">(</span><span class="s2">&quot;Input your second number.&quot;</span><span class="p">))</span>

<span class="n">conditional</span> <span class="o">=</span> <span class="nb">input</span><span class="p">(</span><span class="s2">&quot;AND, OR, XOR?&quot;</span><span class="p">)</span><span class="o">.</span><span class="n">lower</span><span class="p">()</span>
<span class="k">if</span> <span class="n">conditional</span> <span class="o">==</span> <span class="s2">&quot;and&quot;</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Selection:&quot;</span> <span class="p">,</span> <span class="s2">&quot;AND&quot;</span><span class="p">,</span> <span class="n">firstNum</span><span class="p">,</span> <span class="s2">&quot;&amp;&quot;</span><span class="p">,</span> <span class="n">secondNum</span><span class="p">,</span> <span class="s2">&quot;=&quot;</span><span class="p">,</span> <span class="n">firstNum</span> <span class="o">&amp;</span> <span class="n">secondNum</span><span class="p">)</span>
<span class="k">elif</span> <span class="n">conditional</span> <span class="o">==</span><span class="s2">&quot;or&quot;</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Selection:&quot;</span> <span class="p">,</span> <span class="s2">&quot;OR &quot;</span><span class="p">,</span> <span class="n">firstNum</span><span class="p">,</span> <span class="s2">&quot;|&quot;</span><span class="p">,</span> <span class="n">secondNum</span><span class="p">,</span> <span class="s2">&quot;=&quot;</span><span class="p">,</span> <span class="n">firstNum</span> <span class="o">|</span> <span class="n">secondNum</span><span class="p">)</span>
<span class="k">elif</span> <span class="n">conditional</span> <span class="o">==</span><span class="s2">&quot;xor&quot;</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Selection:&quot;</span> <span class="p">,</span> <span class="s2">&quot;XOR&quot;</span><span class="p">,</span> <span class="n">firstNum</span><span class="p">,</span> <span class="s2">&quot;^&quot;</span><span class="p">,</span> <span class="n">secondNum</span><span class="p">,</span> <span class="s2">&quot;=&quot;</span><span class="p">,</span> <span class="n">firstNum</span> <span class="o">^</span> <span class="n">secondNum</span><span class="p">)</span>
<span class="k">else</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Error&quot;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>Selection: OR  2 | 10 = 10
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Lists: Lists are data structures used to store multiple values in one variable.</p>
<p>Iteration: Iteration is a type of control flow that allows for the execution of certain code multiple times.</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="nb">print</span><span class="p">(</span><span class="s2">&quot;What is the variable name/key?&quot;</span><span class="p">,</span> <span class="s2">&quot;value?&quot;</span><span class="p">,</span> <span class="s2">&quot;type?&quot;</span><span class="p">,</span> <span class="s2">&quot;primitive or collection, why?&quot;</span><span class="p">)</span>
<span class="n">name</span> <span class="o">=</span> <span class="s2">&quot;Ethan Tran&quot;</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;name&quot;</span><span class="p">,</span> <span class="n">name</span><span class="p">,</span> <span class="nb">type</span><span class="p">(</span><span class="n">name</span><span class="p">))</span>

<span class="nb">print</span><span class="p">()</span>


<span class="c1"># variable of type integer</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;What is the variable name/key?&quot;</span><span class="p">,</span> <span class="s2">&quot;value?&quot;</span><span class="p">,</span> <span class="s2">&quot;type?&quot;</span><span class="p">,</span> <span class="s2">&quot;primitive or collection, why?&quot;</span><span class="p">)</span>
<span class="n">age</span> <span class="o">=</span> <span class="mi">15</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;age&quot;</span><span class="p">,</span> <span class="n">age</span><span class="p">,</span> <span class="nb">type</span><span class="p">(</span><span class="n">age</span><span class="p">))</span>

<span class="nb">print</span><span class="p">()</span>

<span class="c1"># variable of type float</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;What is the variable name/key?&quot;</span><span class="p">,</span> <span class="s2">&quot;value?&quot;</span><span class="p">,</span> <span class="s2">&quot;type?&quot;</span><span class="p">,</span> <span class="s2">&quot;primitive or collection, why?&quot;</span><span class="p">)</span>
<span class="n">score</span> <span class="o">=</span> <span class="mf">100.0</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;score&quot;</span><span class="p">,</span> <span class="n">score</span><span class="p">,</span> <span class="nb">type</span><span class="p">(</span><span class="n">score</span><span class="p">))</span>

<span class="nb">print</span><span class="p">()</span>

<span class="c1"># variable of type list (many values in one variable)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;What is variable name/key?&quot;</span><span class="p">,</span> <span class="s2">&quot;value?&quot;</span><span class="p">,</span> <span class="s2">&quot;type?&quot;</span><span class="p">,</span> <span class="s2">&quot;primitive or collection?&quot;</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;What is different about the list output?&quot;</span><span class="p">)</span>
<span class="n">langs</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;Python&quot;</span><span class="p">,</span> <span class="s2">&quot;JavaScript&quot;</span><span class="p">,</span> <span class="s2">&quot;Java&quot;</span> <span class="p">,</span> <span class="s2">&quot;Bash&quot;</span> <span class="p">,</span> <span class="s2">&quot;C&quot;</span> <span class="p">,</span> <span class="s2">&quot;R&quot;</span><span class="p">]</span> 
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;langs&quot;</span><span class="p">,</span> <span class="n">langs</span><span class="p">,</span> <span class="nb">type</span><span class="p">(</span><span class="n">langs</span><span class="p">),</span> <span class="s2">&quot;length&quot;</span><span class="p">,</span> <span class="nb">len</span><span class="p">(</span><span class="n">langs</span><span class="p">))</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;- langs[0]&quot;</span><span class="p">,</span> <span class="n">langs</span><span class="p">[</span><span class="mi">0</span><span class="p">],</span> <span class="nb">type</span><span class="p">(</span><span class="n">langs</span><span class="p">[</span><span class="mi">0</span><span class="p">]))</span>

<span class="nb">print</span><span class="p">()</span>

<span class="c1"># variable of type dictionary (a group of keys and values)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;What is the variable name/key?&quot;</span><span class="p">,</span> <span class="s2">&quot;value?&quot;</span><span class="p">,</span> <span class="s2">&quot;type?&quot;</span><span class="p">,</span> <span class="s2">&quot;primitive or collection, why?&quot;</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;What is different about the dictionary output?&quot;</span><span class="p">)</span>
<span class="n">person</span> <span class="o">=</span> <span class="p">{</span>
    <span class="s2">&quot;name&quot;</span><span class="p">:</span> <span class="n">name</span><span class="p">,</span>
    <span class="s2">&quot;age&quot;</span><span class="p">:</span> <span class="n">age</span><span class="p">,</span>
    <span class="s2">&quot;score&quot;</span><span class="p">:</span> <span class="n">score</span><span class="p">,</span>
    <span class="s2">&quot;langs&quot;</span><span class="p">:</span> <span class="n">langs</span><span class="p">,</span>
<span class="p">}</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;person&quot;</span><span class="p">,</span> <span class="n">person</span><span class="p">,</span> <span class="nb">type</span><span class="p">(</span><span class="n">person</span><span class="p">),</span> <span class="s2">&quot;length&quot;</span><span class="p">,</span> <span class="nb">len</span><span class="p">(</span><span class="n">person</span><span class="p">))</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;- person[&quot;name&quot;]&#39;</span><span class="p">,</span> <span class="n">person</span><span class="p">[</span><span class="s2">&quot;name&quot;</span><span class="p">],</span> <span class="nb">type</span><span class="p">(</span><span class="n">person</span><span class="p">[</span><span class="s2">&quot;name&quot;</span><span class="p">]))</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>What is the variable name/key? value? type? primitive or collection, why?
name Ethan Tran &lt;class &#39;str&#39;&gt;

What is the variable name/key? value? type? primitive or collection, why?
age 15 &lt;class &#39;int&#39;&gt;

What is the variable name/key? value? type? primitive or collection, why?
score 100.0 &lt;class &#39;float&#39;&gt;

What is variable name/key? value? type? primitive or collection?
What is different about the list output?
langs [&#39;Python&#39;, &#39;JavaScript&#39;, &#39;Java&#39;, &#39;Bash&#39;, &#39;C&#39;, &#39;R&#39;] &lt;class &#39;list&#39;&gt; length 6
- langs[0] Python &lt;class &#39;str&#39;&gt;

What is the variable name/key? value? type? primitive or collection, why?
What is different about the dictionary output?
person {&#39;name&#39;: &#39;Ethan Tran&#39;, &#39;age&#39;: 15, &#39;score&#39;: 100.0, &#39;langs&#39;: [&#39;Python&#39;, &#39;JavaScript&#39;, &#39;Java&#39;, &#39;Bash&#39;, &#39;C&#39;, &#39;R&#39;]} &lt;class &#39;dict&#39;&gt; length 4
- person[&#34;name&#34;] Ethan Tran &lt;class &#39;str&#39;&gt;
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Logical Operator: A logical operator is a type of operator in computer science that performs a logical operation, such as a comparison or a boolean operation, on two or more values or variables. Examples of logical operators include AND, OR, NOT, XOR, and NAND.</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">Tru</span> <span class="o">=</span> <span class="kc">True</span>
<span class="n">equals</span> <span class="o">=</span> <span class="s2">&quot;=&quot;</span>
<span class="n">opposite</span> <span class="o">=</span> <span class="ow">not</span><span class="p">(</span><span class="n">Tru</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">opposite</span><span class="p">)</span>

<span class="n">fun</span> <span class="o">=</span> <span class="s2">&quot;fun&quot;</span>
<span class="n">awesome</span> <span class="o">=</span> <span class="n">fun</span>

<span class="k">if</span> <span class="n">fun</span> <span class="ow">and</span> <span class="n">awesome</span> <span class="o">==</span> <span class="s2">&quot;fun&quot;</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;AND&quot;</span><span class="p">)</span>
<span class="k">else</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;NOT AND&quot;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>False
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">fun</span> <span class="o">=</span> <span class="s2">&quot;fun&quot;</span>
<span class="n">awesome</span> <span class="o">=</span> <span class="n">fun</span>

<span class="k">if</span> <span class="n">fun</span> <span class="ow">and</span> <span class="n">awesome</span> <span class="o">==</span> <span class="s2">&quot;fun&quot;</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;AND&quot;</span><span class="p">)</span>
<span class="k">else</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;NOT AND&quot;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>AND
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">random</span> 

<span class="n">numList</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;1&quot;</span><span class="p">,</span> <span class="s2">&quot;2&quot;</span><span class="p">,</span> <span class="s2">&quot;3&quot;</span><span class="p">,</span> <span class="s2">&quot;4&quot;</span><span class="p">,</span> <span class="s2">&quot;5&quot;</span><span class="p">]</span>
<span class="n">ranNum</span> <span class="o">=</span> <span class="n">random</span><span class="o">.</span><span class="n">randrange</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">numList</span><span class="p">))</span>
<span class="nb">print</span><span class="p">(</span><span class="n">ranNum</span><span class="p">)</span>

<span class="k">if</span> <span class="n">ranNum</span> <span class="o">==</span> <span class="mi">2</span> <span class="ow">or</span> <span class="n">ranNum</span> <span class="o">==</span> <span class="mi">5</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;OR&quot;</span><span class="p">)</span>
<span class="k">else</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;NOT OR&quot;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>3
NOT OR
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

</div>
 

