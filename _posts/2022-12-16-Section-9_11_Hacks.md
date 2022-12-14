---
keywords: fastai
title: Hacks Unit 3 Sections 9-11
badges: true
comments: true
author: Ethan Tran
categories: [unit 3, sections 9-11, notes hacks]
nb_path: _notebooks/2022-6-12-Section-9_11_Hacks.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-6-12-Section-9_11_Hacks.ipynb
-->

<div class="container" id="notebook-container">
        
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Notes">Notes<a class="anchor-link" href="#Notes"> </a></h2><p>1) Developing Algorithms</p>
<p>When creating an algorithm, its good to outline its process before coding
This ensures that it is sequenced correctly
You should represent the algorithm using a flowchart or natural language
Visualization can help you better see the flow of the whole algorithm
This may allow for the coding process to be more efficient and effective</p>
<p>2) Review of Selection and Iteration</p>
<p>Algorithms with iteration repeat a function until a goal is reached
To more easily represent an algorithm without showing all the repeated steps, we can use iteration
Algorithms with selection only go through certain functions if certain things are true or false</p>
<p>3) Why use algorithms?</p>
<p>When 2 algorithms look extremely similar, it is easy to assume they do the same thing. However, that is not the case and we have learn how to notice small differences in code and pretty much debug.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Hacks-3.9.1">Hacks 3.9.1<a class="anchor-link" href="#Hacks-3.9.1"> </a></h2><p>1) Why is it important to know that algorithms that look different can do the same thing and that algorithms that look the same might have different results?</p>
<ul>
<li>It is vital to know that algorithms that appear different are capable of performing the same functions, and that algorithms that look the same may have different results. This is because it allows for creativity when coding, leading to finding new or different ways of solving the same 
issue(s).</li>
</ul>
<p>2) For the converted conditional to boolean conversion</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">isSunny</span> <span class="o">=</span> <span class="kc">True</span>
<span class="n">isRainy</span> <span class="o">=</span> <span class="kc">False</span>

<span class="k">if</span> <span class="n">isSunny</span> <span class="o">==</span> <span class="kc">True</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;No umbrella necessary!&quot;</span><span class="p">)</span>

<span class="k">else</span><span class="p">:</span>
    <span class="k">if</span> <span class="n">isRainy</span> <span class="o">==</span> <span class="kc">True</span><span class="p">:</span>
        <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Might want an umbrella!&quot;</span><span class="p">)</span>
    
    <span class="k">else</span><span class="p">:</span>
        <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;No umbrella necessary!&quot;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>No umbrella necessary!
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
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">isSunny</span> <span class="o">=</span> <span class="kc">False</span>
<span class="n">isRainy</span> <span class="o">=</span> <span class="kc">True</span>

<span class="c1"># setting variables here (same as above to make comparison easier)</span>
<span class="n">puddles</span> <span class="o">=</span> <span class="ow">not</span><span class="p">(</span><span class="n">isSunny</span><span class="p">)</span> <span class="ow">and</span> <span class="n">isRainy</span>
<span class="k">if</span> <span class="n">isRainy</span> <span class="o">==</span> <span class="kc">False</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Puddles!&quot;</span><span class="p">)</span>
<span class="k">if</span> <span class="n">isSunny</span> <span class="o">==</span> <span class="kc">True</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;No puddles!&quot;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Hacks-3.9.2">Hacks 3.9.2<a class="anchor-link" href="#Hacks-3.9.2"> </a></h2><ul>
<li>Develop your own complex algorithm using a flowchart and natural language, then code it!</li>
<li>Requirements:</li>
<li>Includes both a flowchart AND natural language</li>
<li>Working code of the same algorithm</li>
<li>Incorporates selection AND/OR iteration</li>
<li>Make it creative!</li>
</ul>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<html>
{% include image.html height="350px" file="https://user-images.githubusercontent.com/109186517/206651133-bae66b49-0b13-4d4a-80d6-850f5001859d.png" %}
</html>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>1) Once the code starts, the starting amount of money is set to $10.</p>
<p>2) The variable, spendMoney, is set to True.</p>
<p>3) While spendMoney remains true, $1 is deducted from the money variable.</p>
<p>4) Once the variable, money, reaches a value of 0, spendMoney is set to False and the string, "You're out of money!" is printed.</p>
<p>5) End</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">money</span> <span class="o">=</span> <span class="mi">10</span>
<span class="n">spendMoney</span> <span class="o">=</span> <span class="kc">True</span>
<span class="k">while</span><span class="p">(</span><span class="n">spendMoney</span> <span class="o">==</span> <span class="kc">True</span><span class="p">):</span>
    <span class="n">money</span> <span class="o">-=</span> <span class="mi">1</span>
    <span class="k">if</span> <span class="n">money</span> <span class="o">==</span> <span class="mi">0</span><span class="p">:</span>
        <span class="n">spendMoney</span> <span class="o">==</span> <span class="kc">False</span>
        <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;You&#39;re out of money!&quot;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>You&#39;re out of money!
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Hacks-3.9.3">Hacks 3.9.3<a class="anchor-link" href="#Hacks-3.9.3"> </a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<ul>
<li>Fix the number guessing game</li>
</ul>
<p>1) Make a flow chart for the algorithm number guessing game</p>
<p>2) Make a function that gets the user guess</p>
<p>3) Modify the existing search function to give more encouraging feedback</p>
<html>
{% include image.html height="350px" file="https://user-images.githubusercontent.com/109186517/206798120-9cf0bde9-b5ec-49fd-9659-e885cc30fb6a.png" %}
</html>
</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">random</span>

<span class="c1">#sets variables for the game</span>
<span class="n">num_guesses</span> <span class="o">=</span> <span class="mi">0</span>
<span class="n">user_guess</span> <span class="o">=</span> <span class="o">-</span><span class="mi">1</span>
<span class="n">upper_bound</span> <span class="o">=</span> <span class="mi">100</span>
<span class="n">lower_bound</span> <span class="o">=</span> <span class="mi">0</span>

<span class="c1">#generates a random number</span>
<span class="n">number</span> <span class="o">=</span> <span class="n">random</span><span class="o">.</span><span class="n">randint</span><span class="p">(</span><span class="mi">0</span><span class="p">,</span><span class="mi">100</span><span class="p">)</span>

<span class="c1"># print(number)     #for testing purposes</span>

<span class="nb">print</span><span class="p">(</span><span class="sa">f</span><span class="s2">&quot;I&#39;m thinking of a number between 0 and 100.&quot;</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">number</span><span class="p">)</span>

<span class="c1">#Write a function that gets a guess from the user using input()</span>
<span class="k">def</span> <span class="nf">guess</span><span class="p">():</span>
    <span class="n">num</span> <span class="o">=</span> <span class="nb">input</span><span class="p">(</span><span class="s2">&quot;Input your guess&quot;</span><span class="p">)</span>
    <span class="c1">#add something here</span>
    <span class="k">return</span> <span class="n">num</span> <span class="c1">#add something here </span>

<span class="c1">#Change the print statements to give feedback on whether the player guessed too high or too low</span>
<span class="k">def</span> <span class="nf">search</span><span class="p">(</span><span class="n">number</span><span class="p">,</span> <span class="n">guess</span><span class="p">):</span>
    <span class="k">global</span> <span class="n">lower_bound</span><span class="p">,</span> <span class="n">upper_bound</span>
    <span class="k">if</span> <span class="nb">int</span><span class="p">(</span><span class="n">guess</span><span class="p">)</span> <span class="o">&lt;</span> <span class="nb">int</span><span class="p">(</span><span class="n">number</span><span class="p">):</span>
        <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Too low, try again! :)&quot;</span><span class="p">)</span> <span class="c1">#change this</span>
        <span class="n">lower_bound</span> <span class="o">=</span> <span class="n">guess</span>
        <span class="k">return</span> <span class="n">lower_bound</span><span class="p">,</span> <span class="n">upper_bound</span>
    <span class="k">elif</span> <span class="nb">int</span><span class="p">(</span><span class="n">guess</span><span class="p">)</span> <span class="o">&gt;</span> <span class="nb">int</span><span class="p">(</span><span class="n">number</span><span class="p">):</span>
        <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Too high, try again! :D&quot;</span><span class="p">)</span> <span class="c1">#change this</span>
        <span class="n">upper_bound</span> <span class="o">=</span> <span class="n">guess</span>
        <span class="k">return</span> <span class="n">lower_bound</span><span class="p">,</span> <span class="n">upper_bound</span>
    <span class="k">else</span><span class="p">:</span>
        <span class="n">upper_bound</span><span class="p">,</span> <span class="n">lower_bound</span> <span class="o">=</span> <span class="n">guess</span><span class="p">,</span> <span class="n">guess</span>
        <span class="k">return</span> <span class="n">lower_bound</span><span class="p">,</span> <span class="n">upper_bound</span> 

<span class="k">while</span> <span class="n">user_guess</span> <span class="o">!=</span> <span class="n">number</span><span class="p">:</span>
    <span class="n">user_guess</span> <span class="o">=</span> <span class="n">guess</span><span class="p">()</span>
    <span class="n">num_guesses</span> <span class="o">+=</span> <span class="mi">1</span>
    <span class="nb">print</span><span class="p">(</span><span class="sa">f</span><span class="s2">&quot;You guessed </span><span class="si">{</span><span class="n">user_guess</span><span class="si">}</span><span class="s2">.&quot;</span><span class="p">)</span>
    <span class="n">lower_bound</span><span class="p">,</span> <span class="n">upper_bound</span> <span class="o">=</span> <span class="n">search</span><span class="p">(</span><span class="n">number</span><span class="p">,</span> <span class="n">user_guess</span><span class="p">)</span>
    <span class="k">if</span> <span class="nb">int</span><span class="p">(</span><span class="n">upper_bound</span><span class="p">)</span> <span class="o">==</span> <span class="nb">int</span><span class="p">(</span><span class="n">number</span><span class="p">):</span>
        <span class="k">break</span>
    <span class="k">else</span><span class="p">:</span>
        <span class="nb">print</span><span class="p">(</span><span class="sa">f</span><span class="s2">&quot;Guess a number between </span><span class="si">{</span><span class="n">lower_bound</span><span class="si">}</span><span class="s2"> and </span><span class="si">{</span><span class="n">upper_bound</span><span class="si">}</span><span class="s2">.&quot;</span><span class="p">)</span>


<span class="nb">print</span><span class="p">(</span><span class="sa">f</span><span class="s2">&quot;You guessed the number in </span><span class="si">{</span><span class="n">num_guesses</span><span class="si">}</span><span class="s2"> guesses!&quot;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>I&#39;m thinking of a number between 0 and 100.
92
You guessed 10.
Too low, try again! :)
Guess a number between 10 and 100.
You guessed 99.
Too high, try again! :D
Guess a number between 10 and 99.
You guessed 92.
You guessed the number in 3 guesses!
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Hacks-3.11">Hacks 3.11<a class="anchor-link" href="#Hacks-3.11"> </a></h2><p>1) calculate the middle index and create a binary tree for each of these lists
12, 14, 43, 57, 79, 80, 99
92, 43, 74, 66, 30, 12, 1
7, 13, 96, 111, 33, 84, 60</p>
<p>Answer: Below</p>
<html>
{% include image.html height="350px" file="https://user-images.githubusercontent.com/109186517/206798761-327bf96a-39cd-44b4-895c-f199fe474ca2.png" %}
</html><p>2) Using one of the sets of numbers from the question above, what would be the second number looked at in a binary search if the number is more than the middle number?
Set 1: 80, Set 2: 74, Set 3: 96</p>
<p>Answer: Set 1: 80, Set 2: 74, Set 3: 96</p>
<html>
{% include image.html height="350px" file="https://user-images.githubusercontent.com/109186517/206799034-22733d09-e6dd-48da-bb87-e814bd9d50b0.png" %}
</html><p>3) Which of the following lists can NOT a binary search be used in order to find a targeted value?</p>
<p>a. ["amy", "beverly", "christian", "devin"]</p>
<p>b. [-1, 2, 6, 9, 19]</p>
<p>c. [3, 2, 8, 12, 99]</p>
<p>d. ["xylophone", "snowman", "snake", "doorbell", "author"]</p>
<p>Answer: C</p>
<html>
{% include image.html height="350px" file="https://user-images.githubusercontent.com/109186517/206799124-9133bf25-8781-4127-86d2-f43a0ea4f55a.png" %}
</html>
</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">numListOne</span> <span class="o">=</span> <span class="p">[</span><span class="mi">12</span><span class="p">,</span><span class="mi">14</span><span class="p">,</span><span class="mi">44</span><span class="p">,</span><span class="mi">57</span><span class="p">,</span><span class="mi">79</span><span class="p">,</span><span class="mi">80</span><span class="p">,</span><span class="mi">99</span><span class="p">]</span>
<span class="n">numListTwo</span> <span class="o">=</span> <span class="p">[</span><span class="mi">92</span><span class="p">,</span><span class="mi">43</span><span class="p">,</span><span class="mi">74</span><span class="p">,</span><span class="mi">66</span><span class="p">,</span><span class="mi">30</span><span class="p">,</span><span class="mi">12</span><span class="p">,</span><span class="mi">1</span><span class="p">]</span>
<span class="n">numListThree</span> <span class="o">=</span> <span class="p">[</span><span class="mi">7</span><span class="p">,</span><span class="mi">13</span><span class="p">,</span><span class="mi">96</span><span class="p">,</span><span class="mi">111</span><span class="p">,</span><span class="mi">33</span><span class="p">,</span><span class="mi">84</span><span class="p">,</span><span class="mi">60</span><span class="p">]</span>
<span class="n">numLists</span> <span class="o">=</span> <span class="p">[</span><span class="n">numListOne</span><span class="p">,</span> <span class="n">numListTwo</span><span class="p">,</span> <span class="n">numListThree</span><span class="p">]</span>
<span class="k">for</span> <span class="n">x</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">numLists</span><span class="p">)):</span>
    <span class="n">numLists</span><span class="p">[</span><span class="n">x</span><span class="p">]</span><span class="o">.</span><span class="n">sort</span><span class="p">()</span>
    <span class="n">middle</span> <span class="o">=</span> <span class="nb">int</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">numLists</span><span class="p">[</span><span class="n">x</span><span class="p">])</span><span class="o">/</span><span class="mi">2</span><span class="p">)</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Middle Index of List #&quot;</span><span class="p">,</span><span class="n">x</span><span class="o">+</span><span class="mi">1</span><span class="p">,</span><span class="s2">&quot;is&quot;</span><span class="p">,</span><span class="n">numLists</span><span class="p">[</span><span class="n">x</span><span class="p">][</span><span class="n">middle</span><span class="p">])</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>Middle Index of List # 1 is 57
Middle Index of List # 2 is 43
Middle Index of List # 3 is 60
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

</div>
 

