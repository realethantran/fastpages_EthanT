---
keywords: fastai
title: Algorithms
badges: true
comments: true
author: Ethan Tran
categories: [algorithms, truth tables]
nb_path: _notebooks/2022-12-15-Algorithms.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-12-15-Algorithms.ipynb
-->

<div class="container" id="notebook-container">
        
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Notes/Vocabulary">Notes/Vocabulary<a class="anchor-link" href="#Notes/Vocabulary"> </a></h2><p>Truth Tables:
Truth tables are a type of mathematical table used in logic and computer science to display the truth-values of logical expressions. A truth table has one column for each input variable (for example, a, b, and c) and one final column showing all of the possible results of the expression for each combination of inputs. In other words, a truth table shows the output of a logical expression for every possible combination of input values. The output column of a truth table is often referred to as the "truth value" column because it shows the truth-value of the logical expression for each combination of inputs.</p>
<p>Procedures/Functions:
A procedure or function is a set of instructions that a computer can execute in order to accomplish a given task. Procedures and functions are a fundamental component of computer programming, and are used to break complex tasks into smaller, more manageable pieces. Generally, a procedure or function will take some input, perform some processing on the input, and return some output. Procedures and functions can be written in any programming language, though they are most commonly written in high-level languages such as C++, Java, and Python.</p>
<p>Sequences of Code:
A sequence of code is a set of instructions written in a programming language that can be executed by a computer. Sequences of code can range from simple commands to complex algorithms. Sequences of code are written to accomplish a specific task, such as sorting a list of numbers or displaying a user interface. Sequences of code are generally written in a programming language such as C++, Java, or Python.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><strong>Example</strong></p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">xor</span><span class="p">(</span><span class="n">x</span><span class="p">,</span><span class="n">y</span><span class="p">):</span> 
  <span class="k">return</span> <span class="p">(</span><span class="n">x</span> <span class="ow">or</span> <span class="n">y</span><span class="p">)</span> <span class="ow">and</span> <span class="ow">not</span> <span class="p">(</span><span class="n">x</span> <span class="ow">and</span> <span class="n">y</span><span class="p">)</span> 
 
<span class="c1"># The boolean function</span>
<span class="k">def</span> <span class="nf">F</span><span class="p">(</span><span class="n">A</span><span class="p">,</span> <span class="n">B</span><span class="p">,</span> <span class="n">C</span><span class="p">,</span> <span class="n">D</span><span class="p">):</span> 
  <span class="n">P</span> <span class="o">=</span> <span class="n">xor</span><span class="p">(</span><span class="n">A</span><span class="p">,</span> <span class="n">B</span><span class="p">)</span> 
  <span class="n">Q</span> <span class="o">=</span> <span class="n">xor</span><span class="p">(</span><span class="n">C</span><span class="p">,</span> <span class="n">D</span><span class="p">)</span> 
  <span class="n">R</span> <span class="o">=</span> <span class="n">xor</span><span class="p">(</span><span class="n">P</span><span class="p">,</span> <span class="n">Q</span><span class="p">)</span> 
  <span class="k">return</span> <span class="n">R</span> 
 
<span class="c1"># Translates between &#39;T&#39;/&#39;F&#39; and True/False: </span>
<span class="k">def</span> <span class="nf">f</span><span class="p">(</span><span class="n">a</span><span class="p">,</span><span class="n">b</span><span class="p">,</span><span class="n">c</span><span class="p">,</span><span class="n">d</span><span class="p">):</span> 
  <span class="n">t</span> <span class="o">=</span> <span class="s1">&#39;T&#39;</span> 
  <span class="p">(</span><span class="n">A</span><span class="p">,</span><span class="n">B</span><span class="p">,</span><span class="n">C</span><span class="p">,</span><span class="n">D</span><span class="p">)</span> <span class="o">=</span> <span class="p">(</span><span class="n">a</span><span class="o">==</span><span class="n">t</span><span class="p">,</span> <span class="n">b</span><span class="o">==</span><span class="n">t</span><span class="p">,</span> <span class="n">c</span><span class="o">==</span><span class="n">t</span><span class="p">,</span> <span class="n">d</span><span class="o">==</span><span class="n">t</span><span class="p">)</span> 
  <span class="n">R</span> <span class="o">=</span> <span class="n">F</span><span class="p">(</span><span class="n">A</span><span class="p">,</span> <span class="n">B</span><span class="p">,</span> <span class="n">C</span><span class="p">,</span> <span class="n">D</span><span class="p">)</span> 
  <span class="k">return</span> <span class="s2">&quot;FT&quot;</span><span class="p">[</span><span class="n">R</span><span class="p">]</span> 
 
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Truth Table&quot;</span><span class="p">)</span> 
<span class="nb">print</span><span class="p">()</span> 
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;A B C D | f(A,B,C,D)&quot;</span><span class="p">)</span> 
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;========|===========&quot;</span><span class="p">)</span> 
<span class="n">r</span> <span class="o">=</span> <span class="s2">&quot;TF&quot;</span> 
<span class="k">for</span> <span class="n">a</span> <span class="ow">in</span> <span class="n">r</span><span class="p">:</span> 
  <span class="k">for</span> <span class="n">b</span> <span class="ow">in</span> <span class="n">r</span><span class="p">:</span> 
    <span class="k">for</span> <span class="n">c</span> <span class="ow">in</span> <span class="n">r</span><span class="p">:</span> 
      <span class="k">for</span> <span class="n">d</span> <span class="ow">in</span> <span class="n">r</span><span class="p">:</span> 
        <span class="nb">print</span><span class="p">(</span><span class="n">a</span><span class="p">,</span> <span class="n">b</span><span class="p">,</span> <span class="n">c</span><span class="p">,</span> <span class="n">d</span><span class="p">,</span> <span class="s2">&quot;|    &quot;</span><span class="p">,</span> <span class="n">f</span><span class="p">(</span><span class="n">a</span><span class="p">,</span> <span class="n">b</span><span class="p">,</span> <span class="n">c</span><span class="p">,</span> <span class="n">d</span><span class="p">))</span> 
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>Truth Table

A B C D | f(A,B,C,D)
========|===========
T T T T |     F
T T T F |     T
T T F T |     T
T T F F |     F
T F T T |     T
T F T F |     F
T F F T |     F
T F F F |     T
F T T T |     T
F T T F |     F
F T F T |     F
F T F F |     T
F F T T |     F
F F T F |     T
F F F T |     T
F F F F |     F
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

</div>
 

