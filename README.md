# cos418-assignment-1-part-1-intro-to-go-solved
**TO GET THIS SOLUTION VISIT:** [COS418 Assignment 1 (Part 1): Intro to Go Solved](https://www.ankitcodinghub.com/product/cos418-assignment-1-part-1-intro-to-go-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;53873&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COS418 Assignment 1 (Part 1): Intro to Go Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (4 votes)    </div>
    </div>
<h2><a id="user-content-introduction" class="anchor" href="https://github.com/theoliao1998/Distributed-Systems/tree/master/1-1%20Intro%20to%20Go#introduction" aria-hidden="true"></a>Introduction</h2>
In this assignment you will solve two short problems as a way to familiarize yourself with the Go programming language. We expect you to already have a basic knowledge of the language. If you’re starting from nothing, we highly recommend going through the&nbsp;<a href="https://tour.golang.org/list" rel="nofollow">Golang tour</a>&nbsp;before you begin this assignment. Get started by&nbsp;<a href="https://golang.org/doc/install" rel="nofollow">installing Go</a>&nbsp;on your machine.

<h2><a id="user-content-software" class="anchor" href="https://github.com/theoliao1998/Distributed-Systems/tree/master/1-1%20Intro%20to%20Go#software" aria-hidden="true"></a>Software</h2>
You will find the code the same directory. The two problems that you need to solve are in&nbsp;<tt>q1.go</tt>&nbsp;and&nbsp;<tt>q2.go</tt>. You should only add code to places that say&nbsp;<tt>TODO: implement me</tt>. Do not change any of the function signatures as our testing framework uses them.

<b>Q1 – Top K words:</b>&nbsp;The task is to find the&nbsp;<tt>K</tt>&nbsp;most common words in a given document. To exclude common words such as “a” and “the”, the user of your program should be able to specify the minimum character threshold for a word. Word matching is case insensitive and punctuations should be removed. You can find more details on what qualifies as a word in the comments in the code.

<b>Q2 – Parallel sum:</b>&nbsp;The task is to implement a function that sums a list of numbers in a file in parallel. For this problem you are required to use goroutines (the&nbsp;<tt>go</tt>&nbsp;keyword) and channels to pass messages across the goroutines. While it is possible to just sum all the numbers sequentially, the point of this problem is to familiarize yourself with the synchronization mechanisms in Go.

<h3><a id="user-content-testing" class="anchor" href="https://github.com/theoliao1998/Distributed-Systems/tree/master/1-1%20Intro%20to%20Go#testing" aria-hidden="true"></a>Testing</h3>
Our grading uses the tests in&nbsp;<tt>q1_test.go</tt>&nbsp;and&nbsp;<tt>q2_test.go</tt>&nbsp;provided to you. To test the correctness of your code, run the following:

<pre>  $ cd assignment1-1
  $ go test
</pre>
If all tests pass, you should see the following output:

<pre>  $ go test
  PASS
  ok      /path/to/assignment1-1   0.009s
</pre>
<h3><a id="user-content-submitting-assignment" class="anchor" href="https://github.com/theoliao1998/Distributed-Systems/tree/master/1-1%20Intro%20to%20Go#submitting-assignment" aria-hidden="true"></a>Submitting Assignment</h3>
Now you need to submit your assignment. Commit your change and push it to the remote repository by doing the following:

<div class="highlight highlight-source-shell">
<pre>$ git commit -am <span class="pl-s"><span class="pl-pds">"</span>[you fill me in]<span class="pl-pds">"</span></span>
$ git tag -a -m <span class="pl-s"><span class="pl-pds">"</span>i finished assignment 1-1<span class="pl-pds">"</span></span> a11-handin
$ git push origin master
$ git push origin a11-handin</pre>
</div>
