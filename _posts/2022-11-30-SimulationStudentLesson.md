---
keywords: fastai
description: Student Lesson by Alexa, Ava, Lydia, and Sri
title: Simulations- Unit 3 Section 16 Lesson
toc: true
comments: true
permalink: /studentlesson/simulations
categories: [lesson8]
nb_path: _notebooks/2022-11-30-SimulationStudentLesson.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-11-30-SimulationStudentLesson.ipynb
-->

<div class="container" id="notebook-container">
        
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="3.16-Intro-to-Simulations---Alexa">3.16 Intro to Simulations - Alexa<a class="anchor-link" href="#3.16-Intro-to-Simulations---Alexa"> </a></h1><ul>
<li>What is a <strong>simulation</strong>?<ul>
<li>A simulation is an imitation of a situation or process</li>
<li>Aka a <u>virtual experiment </u></li>
</ul>
</li>
</ul>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Guiding-questions-for-a-simulation:">Guiding questions for a simulation:<a class="anchor-link" href="#Guiding-questions-for-a-simulation:"> </a></h1>
<pre><code>- What makes it a simulation?
- What are it’s advantages and disadvantages? 
- In your opinion, would an experiment be better in this situation?</code></pre>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Examples-of-Simulations:">Examples of Simulations:<a class="anchor-link" href="#Examples-of-Simulations:"> </a></h1><p>Simulations are used all the time over many different industries</p>
<ul>
<li>testing safety of a car</li>
<li>games</li>
<li>testing the efficiency of a parking lot</li>
<li>testing a new train route</li>
</ul>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Simulation-vs.-Experiment">Simulation vs. Experiment<a class="anchor-link" href="#Simulation-vs.-Experiment"> </a></h1><ul>
<li><strong>Experiment</strong> definition: procedure undertaken to make a discovery, test a hypothesis, or demonstrate a known fact</li>
</ul>
<p>So, why use a simulation?</p>
<ul>
<li><strong>Advantages</strong>: <ul>
<li>Can be safer</li>
<li>More cost-effective</li>
<li>More efficient </li>
<li>More data in less time</li>
</ul>
</li>
<li><strong>Disadvantages</strong>:<ul>
<li>Not as accurate as experiments</li>
<li>outside factors not included (ex: in rolling dice simulation gravity and air resistance)</li>
</ul>
</li>
<li>When do you <u>not</u> use a simulation?<ul>
<li>when a situation already has set results/data (won't change) </li>
<li>examples: a score in a game, most purchased food, average yearly wage</li>
</ul>
</li>
</ul>
<p>leads into real life game example:</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><hr></p>
<hr>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="A-Real-Life-Example:-Four-Corners---Lydia-&amp;-Ava">A Real Life Example: Four Corners - Lydia &amp; Ava<a class="anchor-link" href="#A-Real-Life-Example:-Four-Corners---Lydia-&amp;-Ava"> </a></h1><ul>
<li>an example of a simulation and experiment = the game of 4 corners</li>
<li>games are simulations!</li>
<li>We are going to play a round of 4 corners here in class.<ul>
<li>This game is a real life version of our simulation.</li>
<li>Mr. Mortensen will be the person in the middle choosing corners.</li>
<li>Everyone will choose a corner, and if your corner is chosen, you are out!</li>
</ul>
</li>
</ul>
<h3 id="The-rules-of-the-game:">The rules of the game:<a class="anchor-link" href="#The-rules-of-the-game:"> </a></h3><ol>
<li>a person stands in the center of a room and the 4 coners are labeled 1-4</li>
<li>Every player chooses a corner while the person in the middle closes their eyes</li>
<li>person in the middle chooses/calls out a number when instructed</li>
<li>every player in the chosen corner is now out</li>
<li>contine until there is a winner!</li>
</ol>
<h3 id="Let's-play!">Let's play!<a class="anchor-link" href="#Let's-play!"> </a></h3>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="Below-is-the-simulation-of-the-four-corners-game!">Below is the simulation of the four corners game!<a class="anchor-link" href="#Below-is-the-simulation-of-the-four-corners-game!"> </a></h3>
</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">random</span>

<span class="n">status</span> <span class="o">=</span> <span class="s2">&quot;in&quot;</span>
<span class="k">while</span> <span class="n">status</span> <span class="o">!=</span> <span class="s2">&quot;out&quot;</span><span class="p">:</span>
    <span class="n">chooseCorner</span> <span class="o">=</span> <span class="nb">input</span><span class="p">(</span><span class="s2">&quot;What corner do you choose?&quot;</span><span class="p">)</span>

    <span class="n">corner</span> <span class="o">=</span> <span class="n">random</span><span class="o">.</span><span class="n">randint</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span><span class="mi">4</span><span class="p">)</span>

    <span class="k">if</span> <span class="nb">int</span><span class="p">(</span><span class="n">chooseCorner</span><span class="p">)</span> <span class="o">==</span> <span class="n">corner</span><span class="p">:</span>
        <span class="n">status</span> <span class="o">=</span> <span class="s2">&quot;out&quot;</span>
        <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;You chose corner number &quot;</span> <span class="o">+</span> <span class="n">chooseCorner</span> <span class="o">+</span> <span class="s2">&quot; and you&#39;re OUT&quot;</span><span class="p">)</span>
    <span class="k">else</span><span class="p">:</span>
        <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;You chose corner number &quot;</span> <span class="o">+</span> <span class="n">chooseCorner</span> <span class="o">+</span> <span class="s2">&quot; and are still in!&quot;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>You chose corner number 2 and are still in!
You chose corner number 3 and are still in!
You chose corner number 4 and you&#39;re OUT
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="Comparing-Experiment-to-Simulation-Code:">Comparing Experiment to Simulation Code:<a class="anchor-link" href="#Comparing-Experiment-to-Simulation-Code:"> </a></h3><ul>
<li>Mr. Mortensen (person in the middle) = random.randint</li>
<li>if statement = if player is out</li>
<li>else = safe/continue</li>
<li>while loop = repeats process until there is a winner of the game</li>
</ul>
<h3 id="DEBRIEF-QUESTIONS:">DEBRIEF QUESTIONS:<a class="anchor-link" href="#DEBRIEF-QUESTIONS:"> </a></h3><ol>
<li>Why is it better to code simulations than experiement in real life?</li>
<li>What makes this game a simulation?</li>
<li>What are its advantages and disadvantages?</li>
<li>Would an experiment be better in this situation? (raise hands for each team)</li>
</ol>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><hr></p>
<hr>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Hack-#1">Hack #1<a class="anchor-link" href="#Hack-#1"> </a></h2><ul>
<li>Create an idea for a simulation and describe it (you don’t actually have to code it just think about/answer the guiding questions).</li>
</ul>
<p>To test the safety of a car, a simulation can be ran to test out different outcomes depending on the force of the crash. A simulation of this would help to reduce the costs and effects of physically performing crash tests for a car.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Hack-#2-(collegeboard-based-questions)">Hack #2 (collegeboard based questions)<a class="anchor-link" href="#Hack-#2-(collegeboard-based-questions)"> </a></h2><ul>
<li>Simulations Quiz (either screenshot or paste quiz in your notebook):</li>
</ul>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">questions_number</span> <span class="o">=</span> <span class="mi">6</span>
<span class="n">answers_correct</span> <span class="o">=</span> <span class="mi">0</span>
<span class="n">questions</span> <span class="o">=</span> <span class="p">[</span>
    <span class="s2">&quot;True or False: Simulations will always have the same result. </span><span class="se">\n</span><span class="s2"> A: True, </span><span class="se">\n</span><span class="s2"> B: False&quot;</span><span class="p">,</span>
    <span class="s2">&quot;True or False: A simulation has results that are more accurate than an experiment </span><span class="se">\n</span><span class="s2"> A: True, </span><span class="se">\n</span><span class="s2"> B: False&quot;</span><span class="p">,</span>
    <span class="s2">&quot;True or False: A simulation can model real world events that are not practical for experiments </span><span class="se">\n</span><span class="s2"> A: True, </span><span class="se">\n</span><span class="s2"> B: False&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Which one of these is FALSE regarding simulations </span><span class="se">\n</span><span class="s2"> A: Reduces Costs, </span><span class="se">\n</span><span class="s2"> B: Is safer than real life experiments, </span><span class="se">\n</span><span class="s2"> C: More Efficient, </span><span class="se">\n</span><span class="s2"> D: More accurate than real life experiments&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Which of the following scenarios would be the LEAST beneficial to have as a simulation </span><span class="se">\n</span><span class="s2"> A: A retail company wants to identify the item which sold the most on their website, </span><span class="se">\n</span><span class="s2"> B: A restaurant wants to determine if the use of robots will increase efficiency, </span><span class="se">\n</span><span class="s2"> C: An insurance company wants to study the impact of rain on car accidents, </span><span class="se">\n</span><span class="s2"> D: A sports car company wants to study design changes to their new bike design &quot;</span><span class="p">,</span>
    <span class="s2">&quot;Which of the following is better to do as a simulation than as a calculation </span><span class="se">\n</span><span class="s2"> A: Keeping score at a basketball game, </span><span class="se">\n</span><span class="s2"> B: Keeping track of how many games a person has won, </span><span class="se">\n</span><span class="s2"> C: Determining the average grade for a group of tests, </span><span class="se">\n</span><span class="s2"> D: Studying the impact of carbon emissions on the environment&quot;</span>
<span class="p">]</span>
<span class="n">question_answers</span> <span class="o">=</span> <span class="p">[</span>
    <span class="s2">&quot;B&quot;</span><span class="p">,</span>
    <span class="s2">&quot;B&quot;</span><span class="p">,</span>
    <span class="s2">&quot;A&quot;</span><span class="p">,</span>
    <span class="s2">&quot;D&quot;</span><span class="p">,</span>
    <span class="s2">&quot;A&quot;</span><span class="p">,</span>
    <span class="s2">&quot;D&quot;</span>
<span class="p">]</span>

<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Welcome to the Simulations Quiz!&quot;</span><span class="p">)</span>

<span class="k">def</span> <span class="nf">ask_question</span> <span class="p">(</span><span class="n">question</span><span class="p">,</span> <span class="n">answer</span><span class="p">):</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;</span><span class="se">\n</span><span class="s2">&quot;</span><span class="p">,</span> <span class="n">question</span><span class="p">)</span>
    <span class="n">user_answer</span> <span class="o">=</span> <span class="nb">input</span><span class="p">(</span><span class="n">question</span><span class="p">)</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;You said: &quot;</span><span class="p">,</span> <span class="n">user_answer</span><span class="p">)</span>

    <span class="k">if</span> <span class="n">user_answer</span> <span class="o">==</span> <span class="n">answer</span><span class="p">:</span>
        <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Correct!&quot;</span><span class="p">)</span>
        <span class="k">global</span> <span class="n">answers_correct</span>
        <span class="n">answers_correct</span> <span class="o">=</span> <span class="n">answers_correct</span> <span class="o">+</span> <span class="mi">1</span>
    <span class="k">else</span><span class="p">:</span>
        <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;You are incorrect&quot;</span><span class="p">)</span>
    
<span class="k">for</span> <span class="n">num</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="n">questions_number</span><span class="p">):</span>
    <span class="n">ask_question</span><span class="p">(</span><span class="n">questions</span><span class="p">[</span><span class="n">num</span><span class="p">],</span> <span class="n">question_answers</span><span class="p">[</span><span class="n">num</span><span class="p">])</span>

<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;You scored: &quot;</span><span class="p">,</span> <span class="n">answers_correct</span><span class="p">,</span> <span class="s2">&quot;/6&quot;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>Welcome to the Simulations Quiz!

 True or False: Simulations will always have the same result. 
 A: True, 
 B: False
You said:  B
Correct!

 True or False: A simulation has results that are more accurate than an experiment 
 A: True, 
 B: False
You said:  B
Correct!

 True or False: A simulation can model real world events that are not practical for experiments 
 A: True, 
 B: False
You said:  A
Correct!

 Which one of these is FALSE regarding simulations 
 A: Reduces Costs, 
 B: Is safer than real life experiments, 
 C: More Efficient, 
 D: More accurate than real life experiments
You said:  D
Correct!

 Which of the following scenarios would be the LEAST beneficial to have as a simulation 
 A: A retail company wants to identify the item which sold the most on their website, 
 B: A restaurant wants to determine if the use of robots will increase efficiency, 
 C: An insurance company wants to study the impact of rain on car accidents, 
 D: A sports car company wants to study design changes to their new bike design 
You said:  A
Correct!

 Which of the following is better to do as a simulation than as a calculation 
 A: Keeping score at a basketball game, 
 B: Keeping track of how many games a person has won, 
 C: Determining the average grade for a group of tests, 
 D: Studying the impact of carbon emissions on the environment
You said:  D
Correct!
You scored:  6 /6
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><hr></p>
<hr>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Rolling-a-Dice-Example---Sri">Rolling a Dice Example - Sri<a class="anchor-link" href="#Rolling-a-Dice-Example---Sri"> </a></h1>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Below is a simulation of rolling dice! Examine the code and think about how this simulation works and its purpose!</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">parse_input</span><span class="p">(</span><span class="n">input_string</span><span class="p">):</span>
    <span class="k">if</span> <span class="n">input_string</span><span class="o">.</span><span class="n">strip</span><span class="p">()</span> <span class="ow">in</span> <span class="p">{</span><span class="s2">&quot;1&quot;</span><span class="p">,</span> <span class="s2">&quot;2&quot;</span><span class="p">,</span> <span class="s2">&quot;3&quot;</span><span class="p">,</span><span class="s2">&quot;4&quot;</span><span class="p">,</span> <span class="s2">&quot;5&quot;</span><span class="p">,</span> <span class="s2">&quot;6&quot;</span><span class="p">}:</span>
        <span class="k">return</span> <span class="nb">int</span><span class="p">(</span><span class="n">input_string</span><span class="p">)</span>
    <span class="k">else</span><span class="p">:</span>
        <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Please enter a number from 1 to 6.&quot;</span><span class="p">)</span>
        <span class="k">raise</span> <span class="ne">SystemExit</span><span class="p">(</span><span class="mi">1</span><span class="p">)</span>

<span class="kn">import</span> <span class="nn">random</span>

<span class="k">def</span> <span class="nf">roll_dice</span><span class="p">(</span><span class="n">num_dice</span><span class="p">):</span>
    <span class="n">roll_results</span> <span class="o">=</span> <span class="p">[]</span>
    <span class="k">for</span> <span class="n">_</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="n">num_dice</span><span class="p">):</span>
        <span class="n">roll</span> <span class="o">=</span> <span class="n">random</span><span class="o">.</span><span class="n">randint</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span> <span class="mi">6</span><span class="p">)</span>
        <span class="n">roll_results</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">roll</span><span class="p">)</span>
    <span class="k">return</span> <span class="n">roll_results</span>


<span class="n">num_dice_input</span> <span class="o">=</span> <span class="nb">input</span><span class="p">(</span><span class="s2">&quot;How many dice do you want to roll? [1-6] &quot;</span><span class="p">)</span>
<span class="n">num_dice</span> <span class="o">=</span> <span class="n">parse_input</span><span class="p">(</span><span class="n">num_dice_input</span><span class="p">)</span>
<span class="n">roll_results</span> <span class="o">=</span> <span class="n">roll_dice</span><span class="p">(</span><span class="n">num_dice</span><span class="p">)</span>

<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;you rolled:&quot;</span><span class="p">,</span> <span class="n">roll_results</span><span class="p">)</span> 
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>you rolled: [5, 1, 2]
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><hr></p>
<hr>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Game-of-Life---Lydia-&amp;-Ava">Game of Life - Lydia &amp; Ava<a class="anchor-link" href="#Game-of-Life---Lydia-&amp;-Ava"> </a></h1><p>Below is a simulation of the Game of Life, originally written by John Horton Conway. Mr. Mortensen has this game on the APCSP site and we think that it is a great example of an interactive simulation.</p>
<h3 id="What-it-is">What it is<a class="anchor-link" href="#What-it-is"> </a></h3><ul>
<li>This game is an unpredictable cellular automaton</li>
<li>automaton = simulates and imitates human life, hence why this is called the game of life</li>
<li>After creating the initial configuration, the game evolves without pattern</li>
</ul>
<h3 id="How-it-works">How it works<a class="anchor-link" href="#How-it-works"> </a></h3><ul>
<li>Cells in this game are alive or dead, similar to binary where they are on or off</li>
<li>The user created an initial configuration of cells on the grid, and presses play (tap the squares on the grid)</li>
<li>a cells's status (alive or dead, on or off) depends on the surrounding 8 cells status (surrounding 8 boxes). Here are the rules:<ul>
<li>The birth rule= a dead cell (blue box) that is surrounded by at least 3 alive cells (yellow boxes), will become alive</li>
<li>The death rule= an alive cell (yellow) with no or only one surviving cell around it dies (becomes blue)</li>
<li>Cell survival= an alive cell (yellow) with 2 or 3 alive neighboring cells will stay alive</li>
</ul>
</li>
</ul>
<h3 id="Try-it-Out!">Try it Out!<a class="anchor-link" href="#Try-it-Out!"> </a></h3><p>Use the grid below to create cell figurations, press play, and watch your cells die, live, and move around!</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>{% comment %}
Conway's Game of Life <a href="https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life">https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life</a>
{% endcomment %}</p>
<style>
    #container {
    display: grid;
    }

    .cell {
    border: 1px solid black;
    }
</style><div class="container">
    <header class="pb-3 mb-4 border-bottom border-primary text-dark">
        <span class="fs-4">Remix of Game of Life</span>
    </header>
    <!-- Buttons that link to functions in javascript -->
    <button onclick="start()" id="start-btn">start</button>
    <button onclick="step()">step</button>
    <!-- Container drawn by JavaScript -->
    <div id="container" class="container py-4">
    </div>
</div><script>

// Constants
let GRID_SIZE = 40;
let CELL_SIZE = "15px";
let container = document.getElementById("container");

// Add CSS to container to make it a grid
container.style["grid-template-columns"] = `repeat(${GRID_SIZE}, ${CELL_SIZE})`;
// Add squares to grid
for(let i=0; i<GRID_SIZE*GRID_SIZE; i++) {
    let di = document.createElement('div');
    di.style['width'] = CELL_SIZE;
    di.style['height'] = CELL_SIZE;
    di.onclick = clicked; // setting event listener to clicked function
    di.ondragstart = dragged;
    di.ondragover = dragged;
    di.className = 'cell';
    di.id = 'cell-'+i;
    container.appendChild(di)
}


const CELLS = Array(GRID_SIZE).fill().map(() => Array(GRID_SIZE).fill(0)); // create 2D array filled with '0'
const safeindex = (x, y) => !(x < 0 || x >= GRID_SIZE || y<0 || y >= GRID_SIZE); // Anonymous function to check bounds of index
// safeindex(0,0) = true
// safeindex(-1,-1) = false, because -1 falls out of bounds


function safeGet(x, y) {
    if(!safeindex(x,y)) return 0;
    if(CELLS[y][x] === 0) return 0; // blank square
    if(CELLS[y][x] === 1) return 1; // filled square
    if(CELLS[y][x] === 2) return 0; // previously blank square
    if(CELLS[y][x] === 3) return 1; // previously filled square
    console.error("AHH"); // should never get here
}

// helper function to set a square on the grid
function setCell(n, v) {
    let row = Math.floor(n/GRID_SIZE);
    let col = n%GRID_SIZE;
    CELLS[row][col] = v;
}

// Helper function to toggle a cell by it's index
function toggleCell(n) {
    let row = Math.floor(n/GRID_SIZE);
    let col = n%GRID_SIZE;
    CELLS[row][col] = CELLS[row][col] === 0 ? 1 : 0;
}


// Call this every interval, it will look through our CELLS array and reflect its data on the grid
function updateContainer() {
    CELLS.forEach((arr, r) => {
    arr.forEach((val, c) => {
        let n = r*GRID_SIZE + c;
        if(val === 1) {
        document.getElementById("cell-"+n).style['background-color'] = 'yellow';
        }else {
        document.getElementById("cell-"+n).style['background-color'] = 'royalblue'
        }
    });
    })
}


// will be called whenever a cell is clicked
function clicked() {
    const id = parseInt(this.id.substring(5), 10); // the id of a cell is "cell-XX" where XX is the index
    toggleCell(id); // if a cell is clicked we will toggle it
    updateContainer();
}

// Same thing as clicked except tied to drag event
function dragged() {
    const id = parseInt(this.id.substring(5), 10);
    setCell(id, 1);
    updateContainer()
}

// Randomly setting cells to 1 in the grid
function randomInit(n) {
    let max = GRID_SIZE*GRID_SIZE;
    for(let i=0; i<n; i++) {
    setCell(Math.floor(Math.random()*max), 1)
    }
    updateContainer();
}

// check how many alive neighbors a cell has
function getNeighbors(x,y) {
    const l = x-1;
    const r = x+1;
    const u = y-1;
    const d = y+1;

    return safeGet(l, y) +
            safeGet(r, y) +
            safeGet(x, u) +
            safeGet(x, d) +
            safeGet(l, u) +
            safeGet(r, u) +
            safeGet(l, d) +
            safeGet(r, d);
}

function step() {
    for(let y=0; y<GRID_SIZE; y++) {
        for(let x=0; x<GRID_SIZE; x++) { // for every square in the grid...

            const n = getNeighbors(x, y); // find how many alive neighbors it has
            const val = safeGet(x, y); // Get the value of the cell

            if(val === 0) { // if the cell is dead...
                if(n === 3) { // and it has three alive neighbors...
                    CELLS[y][x] = 2; // Make this cell come to life
                }
            } else { // If the cell is alive...
                if(n === 2 || n === 3) { // and it has ONLY 2 or ONLY 3 alive neighbors...
                    CELLS[y][x] = 3; // The cell gets to live another round
                }
            }

        }
    }

    // Run through every modified cell and convert it to either alive or dead
    for(let y=0; y<GRID_SIZE; y++) {
        for(let x=0; x<GRID_SIZE; x++) {
            CELLS[y][x] = Math.floor(CELLS[y][x]/2);
        }
    }

    updateContainer(); // call the update function to reflect changes in the
}


let paused = false;
const startbtn = document.getElementById("start-btn");

// used to toggle the animation
function togglePause() {
    paused = !paused;
    if(paused) {
    startbtn.innerHTML = "resume"
    } else {
    startbtn.innerHTML = "pause";
    }
}

// Used to start the animation
function start() {
    startbtn.innerHTML = "pause";
    startbtn.onclick = togglePause;

    // setInterval will call the function within it ever 100ms
    const interval = setInterval(function() {
    if(!paused) {
        step();
    }
    }, 100);
}

</script>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><hr></p>
<hr>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Hack-#3">Hack #3<a class="anchor-link" href="#Hack-#3"> </a></h2><ul>
<li>Describe the rolling dice simulation (answer guiding questions)</li>
</ul>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Hack-#4">Hack #4<a class="anchor-link" href="#Hack-#4"> </a></h2><ul>
<li>Add a feature onto the rolling dice simulation above <ul>
<li>ex: a 14-sided dice or expand the purpose of the simulation (hint: use conditionals to make dice part of a game/real life situation)</li>
</ul>
</li>
</ul>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><hr></p>
<hr>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Hacks-Overview">Hacks Overview<a class="anchor-link" href="#Hacks-Overview"> </a></h1>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="Use-these-guiding-questions-for-a-simulation:">Use these guiding questions for a simulation:<a class="anchor-link" href="#Use-these-guiding-questions-for-a-simulation:"> </a></h3>
<pre><code>- What makes it a simulation?
- What are it’s advantages and disadvantages? 
- In your opinion, would an experiment be better in this situation?

</code></pre>
<h3 id="Hack-#1-(0.3)">Hack #1 (0.3)<a class="anchor-link" href="#Hack-#1-(0.3)"> </a></h3><ul>
<li>Create an idea for a simulation and describe it (you don’t actually have to code it just think about/answer the guiding questions).</li>
</ul>
<h3 id="Hack-#2-(0.1)">Hack #2 (0.1)<a class="anchor-link" href="#Hack-#2-(0.1)"> </a></h3><ul>
<li>Simulations Quiz (either screenshot or paste quiz in your notebook)</li>
</ul>
<h3 id="Hack-#3-(0.2)">Hack #3 (0.2)<a class="anchor-link" href="#Hack-#3-(0.2)"> </a></h3><ul>
<li>Describe the rolling dice simulation (answer guiding questions)</li>
</ul>
<h3 id="Hack-#4-(0.3)">Hack #4 (0.3)<a class="anchor-link" href="#Hack-#4-(0.3)"> </a></h3><ul>
<li>Add a feature onto the rolling dice simulation above <ul>
<li>ex: a 14-sided dice or expand the purpose of the simulation (hint: use conditionals to make dice part of a game/real life situation)</li>
</ul>
</li>
</ul>
<h3 id="Extra-Credit-(0.1)">Extra Credit (0.1)<a class="anchor-link" href="#Extra-Credit-(0.1)"> </a></h3><ul>
<li>For the extra 0.1: try coding a simple simulation and describe it (guiding question)</li>
</ul>

</div>
</div>
</div>
</div>
 
