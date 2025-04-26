# assignment-5-disk-scheduling-simulation-csc-139-operating-system-principles-solved
**TO GET THIS SOLUTION VISIT:** [Assignment 5: Disk Scheduling Simulation CSC 139 Operating System Principles Solved](https://www.ankitcodinghub.com/product/assignment-5-disk-scheduling-simulation-csc-139-operating-system-principles-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;12823&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;&nbsp;Assignment 5: Disk Scheduling Simulation CSC 139 Operating System Principles Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<h1>1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Objectives</h1>
In this assignment, you will implement three different algorithms for scheduling the disk head on a hard disk. That is, you will simulate the motion of the disk head by taking a set of requests for cylinders/tracks to read and then determining the order in which they will be read. You will then report the total “distance” the disk head had to travel.

<h1>2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Description</h1>
The disk scheduling algorithms to implement in this assignment are first-come-first-served (FCFS), shortestseek-time-first (SSTF), and LOOK. The detailed algorithms are already described in class slides and textbook Chapter 10.

2.1&nbsp;&nbsp;&nbsp;&nbsp; Part A

Write a C program called <em>fcfs.c </em>that implements the FCFS disk scheduling algorithm. Assume the disk arm starts at cylinder/track 50. The set of “requests” to the disk (cylinders/tracks to be read) should be provided as command-line arguments to your program (note: it is safe for your program to assume that the inputs are all well-formed integers between 0 and 100). The output of your program should show the order in which the cylinders/tracks are read, and the total distance traveled. For instance, if your program were executed like this:

./fcfs 5 28 10 7 39 20 45 67 36 35, then the output should look like this:

Reading track 5

Reading track 28

Reading track 10

Reading track 7

Reading track 39

Reading track 20

Reading track 45

Reading track 67

Reading track 36

Reading track 35

Total distance: 219

1

2.2&nbsp;&nbsp;&nbsp;&nbsp; Part B

Write a C program called <em>sstf.c </em>that implements the SSTF disk scheduling algorithm. As in Part A, the set of “requests” to the disk (cylinders/tracks to be read) should be provided as command-line arguments to your program, and the output of your program should show the order in which the cylinders/tracks are read, and the total distance traveled. Assume the disk arm starts at cylinder/track 50.

Note: the SSTF algorithm looks for the track closest to where the disk arm currently is positioned, not to where it started. In the case where two tracks are both equally as close to the current position, you can choose either one (the higher one or the lower one), as long as it’s a “local” decision (i.e., you do not consider what you’ll do after that).

2.3&nbsp;&nbsp;&nbsp;&nbsp; Part C

Write a C program called <em>look.c </em>that implements the LOOK disk scheduling algorithm. As in Parts A and B, the set of “requests” to the disk (cylinders/tracks to be read) should be provided as command-line arguments to your program, and the output of your program should show the order in which the cylinders/tracks are read, and the total distance traveled. Assume the disk arm starts at cylinder/track 50.

Note: assume that the disk arm is moving down at the start of your program.

<h1>3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Deliverables</h1>
Make sure your code can be compiled and work on Athena server correctly. Upload to Canvas the following: • All source codes/files that you have added/modified and the demonstrative results.

<ul>
<li>A README.TXT file that briefly describes each file, how to compile the file(s), and how to run the file.</li>
<li>These files should be placed in a directory called &lt;ECS username&gt;-asgmt5.</li>
<li>Use tar command to place all the files in a single file called &lt;ECS username&gt;-asgmt5.tar.</li>
</ul>
Assuming you are in the directory &lt;ECS username&gt;-asgmt5 do the following:

<ul>
<li>Goto the parent directory: cd ..</li>
<li>tar the files:</li>
</ul>
tar -cvf &lt;ECS username&gt;-asgmt5.tar ./&lt;ECS username&gt;-asgmt5

<ul>
<li>Verify the files have been placed in a tar file:</li>
</ul>
tar -tvf &lt;ECS username&gt;-asgmt5.tar

<ul>
<li>Compress the files using gzip: gzip &lt;ECS username&gt;-asgmt5.tar</li>
<li>Verify that the gzipped file exists: ls &lt;ECS username&gt;-asgmt5.tar.gz</li>
</ul>
2
