# lab-5---file-i-o-solved
**TO GET THIS SOLUTION VISIT:** [Lab 5 – File I/O Solved](https://www.ankitcodinghub.com/product/lab-5-file-i-o-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;11476&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Lab 5 – File I\/O Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<h1>Overview</h1>
For this assignment, you are going to load a series of files containing data and search the loaded data for specific criteria. That might sound a bit dry, but the files contain information about LEGO sets, and everyone loves LEGO! The structure of this assignment is a bit open-ended; you can solve this problem in any way that you see fit. That is the first part of the lab, which is worth <strong>20</strong> points. You will submit this portion on <strong>zyBooks</strong>, just like the previous assignments.

The second part of the lab involves interacting with the terminal, and providing <strong><u>command-line arguments</u></strong> to your application. You are going to use the <em>filename</em> as <strong>command-line argument</strong> of <em>main()</em>. To achieve this, you will modify the <strong>main.cpp</strong> file. This portion will be worth <strong>5</strong> points, and you will submit this via Canvas.

<h2>Description</h2>
First things first, the files: There are <strong>3</strong> main files that you will be loading in this assignment:

<ul>
<li><em>csv </em></li>
<li><em>csv </em></li>
<li><em>csv </em></li>
</ul>
In addition, there are <strong>3</strong> sample files included with this document. Use those to test your loading process. The 3 larger files (on zyBooks, without “SAMPLE_” in the filename) are in the exact same format, the sample files have just been reduced to a handful of entries, so you could easily test as you go.

The data that you will be loading is information about a LEGO set:

<ol>
<li><em>Its set number </em></li>
<li><em>The theme it comes from (City, Technic, Star Wars, etc.) </em></li>
<li><em>The name of the set </em></li>
<li><em>How many parts and mini-figures it contains (if any) </em></li>
<li><em>Its price in US dollars</em></li>
</ol>
Your goal is to read this from 1 of those 3 files (or all of them at once), store it, and then search it based on a few different criteria.

<strong>Main.cpp</strong> is only required for this assignment, <em>but</em> you are free to write any class/functions that you see fit to assist you solve this problem. Main.cpp has some structure to it already to help you get started. Take some time to <strong><em><u>think</u></em></strong> about how you might go about this before diving in.

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong><strong>&nbsp;</strong>

<h1>Searches</h1>
The different searches you will perform will be based on a <em>menu</em> that might look like this:

<ol>
<li>Most expensive</li>
<li>Largest piece count</li>
<li>Search for set name containing… 4. Search themes…</li>
<li>Part count information 6. Price information</li>
<li>Minifigure information</li>
<li>If you bought one of everything…</li>
</ol>
&nbsp;

<table width="623">
<tbody>
<tr>
<td width="312"><strong>Most Expensive </strong>

<strong>&nbsp;</strong>

From the sets that were loaded, which is the most expensive?
</td>
<td width="312">The most expensive set is:

&nbsp;

<em>Name:</em> Super Awesome Building Set

<em>Number:</em> 99923

<em>Theme:</em> City

<em>Price:</em> $21.99

<em>Minifigures:</em> 4

<em>Piece count:</em> 286
</td>
</tr>
<tr>
<td width="312"><strong>Largest piece count </strong>

<strong>&nbsp;</strong>

From the sets that were loaded, which has the most parts?
</td>
<td width="312">The set with the highest parts count:

&nbsp;

<em>Name:</em> Really Big Set

<em>Number:</em> 22231

<em>Theme: </em>Technic

<em>Price:</em> $249.99

<em>Minifigures:</em> 0

<em>Piece count:</em> 5211
</td>
</tr>
<tr>
<td width="312"><strong>Search for set names containing… </strong>

<strong>&nbsp;</strong>

Get a string as input from the user. Then search all sets and their names to see if they contain the search term.

&nbsp;

There could be a lot of sets matching the search term, so show them in a more concise, list format with the <em>set ID</em>, <em>name</em>, and <em>price</em>. If no sets are found, report that as well.
</td>
<td width="312">Sets matching “Fire Station”:

&nbsp;

49281 Fire Station $19.99

9381 Big Fire Station $49.99

&nbsp;

<strong>-OR- </strong>

<strong>&nbsp;</strong>

No sets found matching that search term
</td>
</tr>
<tr>
<td width="312"><strong>Search for set themes containing… </strong>

<strong>&nbsp;</strong>

Ditto<a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a>, but for the theme of the set instead
</td>
<td width="312">Sets matching “City”:

&nbsp;

1234 Police Station $29.99

49281 Fire Station $19.99

// And TONS more… LEGO City is huge!!

&nbsp;
</td>
</tr>
<tr>
<td width="312"><strong>Part count information </strong>

&nbsp;
</td>
<td width="312">Average part count for 601 sets: 492

&nbsp;
</td>
</tr>
<tr>
<td width="312">Show the average parts for all the loaded sets which have non-zero values, and show the largest/smallest sets as well</td>
<td width="312">Set with the smallest part count:

[Set data goes here]

&nbsp;

Set with the largest part count: [Set data goes here]
</td>
</tr>
<tr>
<td width="312"><strong>Price information </strong>

<strong>&nbsp;</strong>

Ditto, but for prices: Average, Minimum &amp;

Maximum
</td>
<td width="312">Average price information for 601 sets: $500

&nbsp;

Set with the minimum price:

[Set data goes here]

&nbsp;

Set with the maximum price: [Set data goes here]
</td>
</tr>
<tr>
<td width="312"><strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>Mini-figure information </strong>

<strong>&nbsp;</strong>

Ditto, but for mini-figures
</td>
<td width="312"></td>
</tr>
<tr>
<td width="312"><strong>If you bought one of everything… </strong>

&nbsp;

How much would it costs? How many parts and mini-figures would you have?
</td>
<td width="312">If you bought one of everything…

&nbsp;

It would cost: $9999.99

You would have 200207 pieces in your collection You would have an army of 3000 mini-figures!
</td>
</tr>
</tbody>
</table>
<strong>&nbsp;</strong>

<h2>Reading Files</h2>
When reading a text file, all of the data typically gets read in as a string. If the final storage variable isn’t a string (such as a person’s age, or the price of something), you must convert it. In the <em>&lt;string&gt;</em> header file, there are a number of functions to help you convert. These function converts a STRING_TO_SOMETHING, and are named like <em>stoi</em> (string to integer), <em>stof</em> (string to float), etc.

The implementation of some of these functions may throw an exception of type “invalid_argument” if the conversion process fails, so you may want to encapsulate these operations in <em>try/catch</em> blocks, and use a default value if you catch an exception—if the number can’t be converted, (in this case) it’s because a value wasn’t there, so what would be a good value to use in the absence of anything else? Refer back to the section on Exceptions in your textbook if you need to.

<h1>Terminal</h1>
The reasoning behind interacting with the terminal is to increase your flexibility and exposure. It’s a great idea to utilize an IDE for enormous projects. However, there will be times where you will be required to use the terminal as a developer. You will live in the terminal world while enrolled in Operating Systems. The below definition gives a brief synopsis:

&nbsp;

“The command-line shell is a text-based user interface for your operating system. Unlike a GUI shell, which uses a graphical representation of the system’s services and resources, the command-line shell uses only text. It is the fundamental interface between you and the operating system, and in many cases offer you more direct control over the system processes.”

&nbsp;

Your goal in this portion of the lab is to pass in the <em>filename</em> when running your program. To achieve this, you can do the following:

<ol>
<li>Open up terminal and navigate to your project directory to compile it using <em>g++</em>
<ol>
<li>Refer to the <em>Windows Subsystem for Linux (WSL)</em> <strong>page</strong> in Canvas</li>
</ol>
</li>
<li>Run your program and pass in the filename as a parameter
<ol>
<li>E. “<em>./main.out</em> <strong>lab5_sample.txt</strong>”</li>
<li>You should <em>throw -1</em> if the file doesn’t exist.</li>
</ol>
</li>
</ol>
&nbsp;

From this, you should observe that testing is much faster. Make sure to refer to the <em>Useful Resources </em>section as it contains helpful articles.

&nbsp;

&nbsp;
