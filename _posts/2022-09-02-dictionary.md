---
keywords: fastai
title: Lists, Dictionaries, & Iterations
badges: true
comments: true
author: Ethan Tran
categories: [fastpages, jupyter, dictionary, dictionaries, lists, functions, for loop, while loop, recursive]
nb_path: _notebooks/2022-09-02-dictionary.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-09-02-dictionary.ipynb
-->

<div class="container" id="notebook-container">
        
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Lists,-Dictionaries,-&amp;-Iterations-(input)">Lists, Dictionaries, &amp; Iterations (input)<a class="anchor-link" href="#Lists,-Dictionaries,-&amp;-Iterations-(input)"> </a></h2><ol>
<li>Using a list, I can set-up the to-be list of vocabulary</li>
<li>The list goes up to 6 inputs thus, the range is equates to 6</li>
<li>The "Word" and "Definition" are set as inputs that can be set by the user</li>
<li>The "Vocabulary" is the final product as a result of the user's inputs</li>
</ol>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">Vocabulary</span> <span class="o">=</span> <span class="p">{}</span>

<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">6</span><span class="p">):</span>
    <span class="n">Word</span> <span class="o">=</span> <span class="nb">input</span><span class="p">(</span><span class="s2">&quot; &quot;</span><span class="p">)</span>
    <span class="n">Definition</span> <span class="o">=</span> <span class="nb">input</span><span class="p">(</span><span class="s2">&quot; &quot;</span><span class="p">)</span>

    <span class="n">Vocabulary</span><span class="p">[</span><span class="n">Word</span><span class="p">]</span> <span class="o">=</span> <span class="n">Definition</span>


<span class="nb">print</span><span class="p">(</span><span class="n">Vocabulary</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>{&#39;Sequence&#39;: &#39;Two or more lines of code&#39;, &#39;Key&#39;: &#39;A mix of fields used to take and sort rows from a given criteria&#39;, &#39;Value&#39;: &#39;Representation of an entity that can be changed by a given program&#39;, &#39;Import&#39;: &#39;A command that is used to add additional functions that have been previously developed&#39;, &#39;If&#39;: &#39;A command that is used to determine whether a response is correct or incorrect based on previously set expressions/conditions&#39;, &#39;Expression&#39;: &#39;Used in an if statement to determine whether a given command is right or wrong&#39;}
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Personalized-InfoDB-(for-+-while-loops-&amp;-recursive-function)">Personalized InfoDB (for + while loops &amp; recursive function)<a class="anchor-link" href="#Personalized-InfoDB-(for-+-while-loops-&amp;-recursive-function)"> </a></h2><ol>
<li>Set InfoDB as a list</li>
<li>Using the ".append" expression, I can personalize (add) to my lists</li>
<li>Set up the data structure of the lists</li>
<li>Print the data structure to prepare it before formatting</li>
<li>The "for_loop" takes the data from "InfoDB" until the list is empty</li>
<li>Using the "while_loop," the function will count through the elements of the list from zero until the end</li>
<li>The "recursive_loop" will continue to run itself within the given "if" statement until the end of the program  </li>
</ol>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">InfoDb</span> <span class="o">=</span> <span class="p">[]</span>

<span class="n">InfoDb</span><span class="o">.</span><span class="n">append</span><span class="p">({</span>
    <span class="s2">&quot;FirstName&quot;</span><span class="p">:</span> <span class="s2">&quot;Ethan&quot;</span><span class="p">,</span>
    <span class="s2">&quot;LastName&quot;</span><span class="p">:</span> <span class="s2">&quot;Tran&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Birth_Month&quot;</span><span class="p">:</span> <span class="s2">&quot;May&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Sports&quot;</span><span class="p">:</span> <span class="p">[</span><span class="s2">&quot;Basketball&quot;</span> <span class="p">,</span> <span class="s2">&quot;Track&quot;</span><span class="p">]</span>
<span class="p">})</span>

<span class="n">InfoDb</span><span class="o">.</span><span class="n">append</span><span class="p">({</span>
    <span class="s2">&quot;FirstName&quot;</span><span class="p">:</span> <span class="s2">&quot;Sean&quot;</span><span class="p">,</span>
    <span class="s2">&quot;LastName&quot;</span><span class="p">:</span> <span class="s2">&quot;Tran&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Birth_Month&quot;</span><span class="p">:</span> <span class="s2">&quot;December&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Sports&quot;</span> <span class="p">:</span> <span class="p">[</span><span class="s2">&quot;Basketball&quot;</span> <span class="p">,</span> <span class="s2">&quot;Track&quot;</span> <span class="p">,</span> <span class="s2">&quot;Volleyball&quot;</span><span class="p">]</span>
<span class="p">})</span>

<span class="k">def</span> <span class="nf">print_data</span><span class="p">(</span><span class="n">person</span><span class="p">):</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Name &quot;</span> <span class="o">+</span> <span class="n">person</span><span class="p">[</span><span class="s2">&quot;FirstName&quot;</span><span class="p">]</span> <span class="o">+</span> <span class="n">person</span><span class="p">[</span><span class="s2">&quot;LastName&quot;</span><span class="p">])</span> 
    <span class="nb">print</span><span class="p">(</span><span class="n">person</span><span class="p">[</span><span class="s2">&quot;Birth_Month&quot;</span><span class="p">]</span> <span class="o">+</span> <span class="n">person</span><span class="p">[</span><span class="s2">&quot;Sports&quot;</span><span class="p">])</span>
<span class="nb">print</span><span class="p">(</span><span class="n">InfoDb</span><span class="p">)</span>

<span class="k">def</span> <span class="nf">for_loop</span><span class="p">():</span>
    <span class="k">for</span> <span class="n">person</span> <span class="ow">in</span> <span class="n">InfoDB</span><span class="p">:</span>
        <span class="n">print_data</span><span class="p">(</span><span class="n">person</span><span class="p">)</span>

<span class="k">def</span> <span class="nf">while_loop</span><span class="p">():</span>
    <span class="n">i</span> <span class="o">=</span> <span class="mi">0</span>
    <span class="k">while</span> <span class="n">i</span> <span class="o">&lt;</span> <span class="nb">len</span><span class="p">(</span><span class="n">InfoDb</span><span class="p">):</span>
        <span class="n">print_data</span><span class="p">(</span><span class="n">InfoDb</span><span class="p">[</span><span class="n">i</span><span class="p">])</span>
        <span class="n">i</span> <span class="o">=</span> <span class="n">i</span> <span class="o">+</span> <span class="mi">1</span>

<span class="k">def</span> <span class="nf">recursive</span><span class="p">(</span><span class="n">index</span><span class="p">):</span>
    <span class="k">if</span> <span class="n">index</span> <span class="o">&gt;=</span> <span class="nb">len</span><span class="p">(</span><span class="n">InfoDb</span><span class="p">):</span>
        <span class="k">return</span>

    <span class="n">print_data</span><span class="p">(</span><span class="n">InfoDB</span><span class="p">[</span><span class="n">index</span><span class="p">])</span>

    <span class="k">return</span> <span class="n">recursive</span><span class="p">(</span><span class="n">index</span> <span class="o">+</span> <span class="mi">1</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>[{&#39;FirstName&#39;: &#39;Ethan&#39;, &#39;LastName&#39;: &#39;Tran&#39;, &#39;Birth_Month&#39;: &#39;May&#39;, &#39;Sports&#39;: [&#39;Basketball&#39;, &#39;Track&#39;]}, {&#39;FirstName&#39;: &#39;Sean&#39;, &#39;LastName&#39;: &#39;Tran&#39;, &#39;Birth_Month&#39;: &#39;December&#39;, &#39;Sports&#39;: [&#39;Basketball&#39;, &#39;Track&#39;, &#39;Volleyball&#39;]}]
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Quiz-using-lists,-dictionaries,-and-iterations">Quiz using lists, dictionaries, and iterations<a class="anchor-link" href="#Quiz-using-lists,-dictionaries,-and-iterations"> </a></h2><ol>
<li>Uses input to allow the questions to be answered</li>
<li>A questions dictionary and answers dictionary are each set</li>
<li>A while_loop allows data to be pulled from the dictionaries (named lists for the variables) until the number of questions and answers hit zero</li>
</ol>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">getpass</span><span class="o">,</span> <span class="nn">sys</span>
<span class="kn">import</span> <span class="nn">random</span>

<span class="c1"># Function to layout the questions and answers </span>
<span class="k">def</span> <span class="nf">ask_question</span> <span class="p">(</span><span class="n">question</span><span class="p">,</span> <span class="n">answer</span><span class="p">):</span>

<span class="c1"># Allow answers to be typed in through input &amp; print the questions and answers</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">question</span><span class="p">)</span>
    <span class="n">ans</span> <span class="o">=</span> <span class="nb">input</span><span class="p">(</span><span class="n">question</span><span class="p">)</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">ans</span><span class="p">)</span>
   

<span class="c1"># Print &quot;Correct!&quot;&quot; and add 1 point (through return) per correct answer </span>
    <span class="k">if</span> <span class="n">ans</span> <span class="o">==</span> <span class="n">answer</span><span class="p">:</span>
        <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Correct!&quot;</span><span class="p">)</span>
        <span class="k">return</span> <span class="mi">1</span>

<span class="c1"># Print &quot;Wrong&quot; when an answer is incorrect and return 0 points</span>
    <span class="k">else</span><span class="p">:</span>
        <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Wrong&quot;</span><span class="p">)</span>
        <span class="k">return</span> <span class="mi">0</span>

<span class="c1"># A list of my questions and answers using the previously added &quot;ask_question&quot; function</span>
<span class="n">question_list</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;Who was the first emperor of Imperial China?&quot;</span> <span class="p">,</span> <span class="s2">&quot;What is 5 x 8?&quot;</span> <span class="p">,</span> <span class="s2">&quot;How many states are there in the United States of America?&quot;</span> <span class="p">,</span> <span class="s2">&quot;What command is used to include other functions that were previously developed?&quot;</span> <span class="p">,</span> <span class="s2">&quot;What command is used to evaluate correct or incorrect response in this example?&quot;</span> <span class="p">,</span> <span class="s2">&quot;Each &#39;if&#39; command contains an &#39;_________&#39; to determine a true or false condition?&quot;</span> <span class="p">,</span> <span class="s2">&quot;What iterates a sequence until the code is over?&quot;</span> <span class="p">,</span> <span class="s2">&quot;What repeats a block of code as long as the expression remains true?&quot;</span><span class="p">]</span>
<span class="n">answer_list</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;Qin&quot;</span><span class="p">,</span> <span class="s2">&quot;40&quot;</span><span class="p">,</span> <span class="s2">&quot;50&quot;</span> <span class="p">,</span> <span class="s2">&quot;import&quot;</span> <span class="p">,</span> <span class="s2">&quot;if&quot;</span> <span class="p">,</span> <span class="s2">&quot;expression&quot;</span> <span class="p">,</span> <span class="s2">&quot;for_loop&quot;</span> <span class="p">,</span> <span class="s2">&quot;while_loop&quot;</span><span class="p">]</span>

<span class="c1"># Set points to 0 at the start of the quiz</span>
<span class="n">points</span> <span class="o">=</span> <span class="mi">0</span>

<span class="c1"># If the length of the quiz is greater than 0, then random questions will be chosen from the &quot;question_list&quot; set</span>
<span class="k">while</span> <span class="nb">len</span><span class="p">(</span><span class="n">question_list</span><span class="p">)</span> <span class="o">&gt;</span> <span class="mi">0</span><span class="p">:</span>
    <span class="n">index</span> <span class="o">=</span> <span class="n">random</span><span class="o">.</span><span class="n">randint</span><span class="p">(</span><span class="mi">0</span><span class="p">,</span> <span class="nb">len</span><span class="p">(</span><span class="n">question_list</span><span class="p">)</span> <span class="o">-</span> <span class="mi">1</span><span class="p">)</span>
    
<span class="c1"># The points system where a point is rewarded for each correct answer    </span>
    <span class="n">points</span> <span class="o">=</span> <span class="n">points</span> <span class="o">+</span> <span class="n">ask_question</span><span class="p">(</span><span class="n">question_list</span><span class="p">[</span><span class="n">index</span><span class="p">],</span> <span class="n">answer_list</span><span class="p">[</span><span class="n">index</span><span class="p">])</span>
    
<span class="c1"># If a question or answer has already been used, then it shall be deleted    </span>
    <span class="k">del</span> <span class="n">question_list</span><span class="p">[</span><span class="n">index</span><span class="p">]</span>
    <span class="k">del</span> <span class="n">answer_list</span><span class="p">[</span><span class="n">index</span><span class="p">]</span>

<span class="c1"># Calculating score using the points system and dividing it by the total number of questions (6)</span>
<span class="n">score</span> <span class="o">=</span> <span class="p">(</span><span class="n">points</span> <span class="o">/</span> <span class="mi">6</span><span class="p">)</span>

<span class="c1"># Calculating the percentage of correct answers by multiplying the score by 100</span>
<span class="n">percent</span> <span class="o">=</span> <span class="p">(</span><span class="n">score</span> <span class="o">*</span> <span class="mi">100</span><span class="p">)</span>

<span class="c1"># Printing the percentage, and formatting the percentage in a way where two decimals can be shown (through &quot;{:.2f}&quot;)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;</span><span class="si">{:.2f}</span><span class="s2">&quot;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="n">percent</span><span class="p">)</span> <span class="o">+</span> <span class="s2">&quot;%&quot;</span><span class="p">)</span>

<span class="c1"># Adding final remarks based upon the users given scores</span>
<span class="k">if</span> <span class="n">points</span> <span class="o">&gt;=</span> <span class="mi">5</span><span class="p">:</span>
         <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Your total score is: &quot;</span><span class="p">,</span> <span class="n">points</span><span class="p">,</span> <span class="s2">&quot;out of 6. Congratulations!&quot;</span><span class="p">)</span>

<span class="k">elif</span> <span class="n">points</span> <span class="o">==</span> <span class="mi">4</span><span class="p">:</span>
         <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Your total score is: &quot;</span><span class="p">,</span> <span class="n">points</span><span class="p">,</span> <span class="s2">&quot;out of 6. Not bad, keep working! &quot;</span> <span class="p">)</span>

<span class="k">else</span><span class="p">:</span>
         <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Your total score is: &quot;</span><span class="p">,</span> <span class="n">points</span><span class="p">,</span> <span class="s2">&quot;out of 6. Its okay, better luck next time!&quot;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

</div>
 
