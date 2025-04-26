# csci-3070u-analysis-and-design-of-algorithms-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [CSCI 3070U:  Analysis and Design of Algorithms Assignment:     #2 Solved](https://www.ankitcodinghub.com/product/csci-3070u-analysis-and-design-of-algorithms-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;71308&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;&nbsp; &nbsp;CSCI 3070U:&nbsp; Analysis and Design of Algorithms  Assignment: &nbsp;&nbsp;&nbsp; #2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
&nbsp;

&nbsp;

<strong>Topic:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>Recurrences, heaps, heapsort, dynamic programming

<strong>&nbsp;</strong>

<h1>Part 1</h1>
For this part of the assignment, you will implement the heap data structure, and use it to implement a heap sort in Java, C, C++, Python (or another approved programming language).

&nbsp;

The heap data structure will need at a minimum the 5 operations discussed during the lectures, as shown below.&nbsp; You can rename these operations away from the naming conventions of the MIT textbook, as long as it is clear what each of them does.

<ul>
<li>BUILD-MAX-HEAP:&nbsp; &nbsp;&nbsp;&nbsp; Takes an arbitrary array and builds it into a max heap</li>
<li>MAX-HEAPIFY:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Takes an almost-heap with one violation, and fixes the violation</li>
<li>HEAP-MAXIMUM:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Returns the largest element in the max heap</li>
<li>HEAP-EXTRACT-MAX:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Removes and returns the largest element in the max heap</li>
<li>MAX-HEAP-INSERT:&nbsp;&nbsp;&nbsp; Inserts a new element into the heap, preserving the heap property</li>
</ul>
&nbsp;

In addition to these operations, you should also implement two display methods, for testing purposes.

<ul>
<li>printAsArray:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Prints the array representation (e.g. [16,14,10,8,7,3,9,1,4,2])</li>
<li>printAsTree:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Prints the heap as a sideways tree, as shown below:</li>
</ul>
&nbsp;

9

10

3

16

7

2

14

4

8

1

&nbsp;

Hint: For printAsTree, you’ll find it easier to write the function recursively including a depth argument (which indicates how far to the right to indent the output).&nbsp; Recursion will be used to print the left and right subtrees (with a incremented depth).

&nbsp;

The implementation of hashsort() will be a function that takes an arbitrary array, and sorts it using a heap.&nbsp; Be sure to include testing code, where you create a heap from an arbitrary array, use buildheap, and then heapsort the array (printing the array before and after), as well as testing the other operations mentioned above.

<h1>Part 2</h1>
Read the first 20 or so slides of the document from Stanford NLP group on Minimum Edit Distance (MED):

&nbsp;

<a href="http://www.stanford.edu/class/cs124/lec/med.pdf">http://www.stanford.edu/class/cs124/lec/med.pdf</a>

&nbsp;

Using this technique, implement this algorithm using Dynamic Programming in an approved programming language.&nbsp; Include some testing code to try it out on a few string pairs:

<ul>
<li>spoof/stool</li>
<li>podiatrist/pediatrician</li>
<li>blaming/conning</li>
</ul>
&nbsp;
