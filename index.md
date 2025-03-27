---
layout: home
title: CS6421 Distributed Systems
---

<link rel="shortcut icon" type="image/x-icon" href="./favicon.ico">

<div class="wrapper" markdown="0"><div class="footer-col-wrapper">
<div class="footer-col two-col-2">
	<ul class="contact-list">
		<li><b>Prof. Roozbeh Haghnazar</b></li>
		<li><a href="mailto:roozbeh@gwu.edu">roozbeh@gwu.edu</a></li>
		<li>Office Hours: Will be announced, check #office-hours</li>
		<!--<li>Section 10 & 11</li>-->
	</ul>
	</div>
</div></div>

> This course will be an in-depth study of the algorithmic and implementation challenges in building large scale distributed applications. Topics include distributed coordination, scheduling, consistency issues, and fault tolerance algorithms. The course will cover how fundamental distributed systems concepts are applied to cloud computing environments. The course will mix algorithmic concepts and practical implementations; substantial programming experience is required.




## Announcements ##
- We will make decision about the exams in the first session
- The [Final Project](./project/) Milestones will be announced.
- If you have feedback for us, please [fill out this anonymous form!](https://forms.gle/5RpcjzQwMvMpURNT9)
- Check the [Syllabus](syllabus/) for more info.
- Both sections 80 and 81 of CSCI 6421 will meet together *as one class*. You can register for either section with no difference. 
- You can use use Python and Go to get your projects and assignments done.
- We will use Distributed Systems 3rd edition (https://www.distributed-systems.net/index.php/books/ds3/) as the main reference. Also there are additional papers which are published in high ranked journals that you can find them in the slides each week. 
- We use [Slack](https://distributedsy-exa1318.slack.com) to communicate and discuss about the topic, assignments and project.



<hr>

## Schedule  ##

All deadlines are 11:59PM Eastern Time

<div style="font-size:90%">

<table>
	<thead>
		<tr>
			<th style="text-align:center" colspan="2">Part 1: Building Blocks</th>
		</tr>
	</thead>
	<tr>
		<td style="width:20%">
			<b>Overview</b>
			<br>1/16/2025
		</td>
		<td>
			<a href="./slides/1-Introduction.pdf">Lecture Slides</a> -- 
			Please read <a href="project/">Final Project Instruction and Milestones</a>
		</td>
	</tr>
	<tr>
		<td style="text-align:right">
			<i>Tasks:</i>
		</td>
		<td>
			<a href="https://join.slack.com/t/distributedsy-icw6571/shared_invite/zt-2ybinyppx-yzSqLHt__OvdKve3ehIxYg">Join Slack</a> today! -- <a href="https://docs.google.com/forms/d/e/1FAIpQLSdko_nuFljD2TYMv1zUNhhFSGTv0k1iqEjYCED6qZ6te0Y3Aw/viewform?usp=sharing">Student Survey</a> due Monday 02/28 
		</td>
	</tr>
	<tr>
		<td>
			<b>Scalable Execution</b>
			<br>1/23/2025
		</td>
		<td>
			<a href="./slides/2-Processes Threads VMs Containers.pdf">Lecture Slides </a>
		</td>
	</tr>
	<tr>
		<td style="text-align:right">
			<i>Tasks:</i>
		</td> 
		<td>
			<a href="./readings.html">Readings in Chapters 1, 3</a> -- Watch <a href="https://gwu.box.com/s/uykp9ouz6fqc8d3psmehq46swmn7i4gm">Azure HWaaS Video </a> -- <a href="hw1/"> HW1: Parallel Sum </a> due 03/06
		</td>
	</tr>
	<tr>
		<td>
			<b>Communication</b>
			<br>01/30/2025
		</td>
		<td>
			<a href="./slides/3-Communication.pdf">Lecture Slides </a>
		</td>
	</tr>
	<tr>
		<td style="text-align:right">
			<i>Tasks:</i>
		</td> 
		<td>
			<a href="./readings.pdf">Readings in Chapters 3, 4</a> -- Read <a href="http://research.google.com/archive/mapreduce-osdi04.pdf">MapReduce paper</a>
		</td>
	</tr>
	<tr>
		<td>
			<b>Architectures</b>
			<br>2/06/2025
		</td>
		<td>
			<a href="./slides/4-Architectures.pdf">Lecture Slides </a>
		</td>
	</tr>
	<tr>
		<td style="text-align:right">
			<i>Tasks:</i>
		</td> 
		<td>
			<a href="./readings.pdf">Readings in Chapter 2</a>  
		</td>
	</tr>
	<tr>
		<td>
			<b>Resource Management</b>
			<br>2/13/2025
		</td>
		<td>
			<a href="./slides/5-Scheduling and LB.pdf">Lecture Slides </a>
		</td>
	</tr>
	<tr>
		<td style="text-align:right">
			<i>Tasks:</i>
		</td> 	
	</tr>
	<tr>
		<td>
			<b>Resource Management 2</b>
			<br>2/20/2025
		</td>
		<td>
			<a href="./slides/6-Migration.pdf">Lecture Slides </a>
		</td>
	</tr>
	<tr>
		<td style="text-align:right">
			<i>Tasks:</i>
		</td> 
		<td>
			<!-- <a href="hw2/">HW2: Map Reduce</a> -10 points by 10/8 -- <a href="https://forms.gle/JreBDrJz2LVfX8A8A">Partner Feedback Form</a> -->
		</td>
	</tr>
</table>

<table>
	<thead>
		<tr>
			<th style="text-align:center" colspan="2">Part 2: Principles of Distributed Systems</th>
		</tr>
	</thead>
	<tr>
		<td style="width:20%">
			<b>Clocks and Timing</b>
			<br>2/27/2025
		</td>
		<td>
			<a href="./slides/7-8-Coordination.pdf">Lecture Slides </a> and <a href="https://youtu.be/IAI712Kk-O8">Video</a>
		</td>
	</tr>
	<tr>
		<td style="text-align:right">
			<i>Tasks:</i>
		</td>
		<td>
			<a href="./readings.pdf">Readings in Chapter 6</a>
		</td>
	</tr>
	<tr>
		<td>
			<b>Distributed Coordination</b>
			<br>3/06/2025
		</td>
		<td>
			<a href="./slides/7-8-Coordination.pdf">Lecture Slides </a>
		</td>
	</tr>
	<tr>
		<td style="text-align:right">
			<i>Tasks:</i>
		</td>
		<td>
			<a href="./readings.pdf">Readings in Chapter 6</a> and <a href="hw2/">HW2: Map Reduce</a> due 3/30 -- <a href="https://youtu.be/ZcaQ7yLAYwM">MapReduce Help Video</a>
		</td>
	</tr>
	<tr>
		<td>
			<b>Fault Tolerance</b>
			<br>3/13/2025
		</td>
		<td>
			<a href="./slides/9-FaultTolerance.pdf">Lecture Slides </a>
		</td>
	</tr>
	<tr>
		<td style="text-align:right">
			<i>Tasks:</i>
		</td>
		<td>
			<a href="./readings.pdf">Readings in Chapter 8</a> <!-- -- <a href="/project/#milestone-2-literature-review">Milestone 2: Literature Review</a> - 10/29 -->
		</td>
	</tr>
	<tr>
		<td>
			<b>Replication</b>
			<br>3/20/2025
		</td>
		<td>
			<a href="./slides/10-Consistency.pdf">Lecture Slides </a>   <a href="hw2/">HW2: Map Reduce</a> due 03/30 <!-- -- <a href="slides/10-consistency-problems.pdf">Consistency Problems Worksheet</a> -->
		</td>
	</tr>
	<tr>
		<td style="text-align:right">
			<i>Tasks:</i>
		</td>
		<td>
			<a href="./readings.pdf">Readings in Chapter 7</a> -- <a href="./project/#milestone-3-design-document">Milestone 3: Design Document</a> 
		</td>
	</tr>
	<tr>
		<td style="width:20%">
			<b>Performance Modeling</b>
			<br>3/27/2025
		</td>
		<td>
			<a href="./slides/11-Performance.pdf"> Lecture Slides </a>
		</td>
	</tr>
	<tr>
		<td style="text-align:right">
			<i>Tasks:</i>
		</td>
		<td>
			Work on your project! 
		</td>
	</tr>
	<tr>
		<td>
			<b>Cloud Computing</b>
			<br>4/03/2025
		</td>
		<td>
			<a href="./slides/12-CloudApps.pdf"> Lecture Slides </a>
		</td>
	</tr>
	<tr>
		<td style="text-align:right"><i>Tasks:</i></td><td>Work on your project! </td>
	</tr>
	<tr>
		<td>
			<b>Internet of Things and Big Data</b>
			<br>4/10/2025
		</td>
		<td>
			Lecture Slides
		</td>
	</tr>
	<tr>
		<td style="text-align:right">
			<i>Tasks:</i>
		</td>
		<td>
			<!-- <a href="/project/#milestone-4-final-report">Milestone 4: Final Report</a> - 12/14 -- <a href="/hw3/">Bonus HW3: Leader Election</a> - 12/10-->
		</td>
	</tr>
</table>

</div>
