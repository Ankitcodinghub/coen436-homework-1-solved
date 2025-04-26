# coen436-homework-1-solved
**TO GET THIS SOLUTION VISIT:** [COEN436 Homework 1 Solved](https://www.ankitcodinghub.com/product/coen436-homework-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101668&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COEN436 Homework 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
An operating system’s pid manager is responsible for managing process identifiers. When a process is first created, it is assigned a unique pid by the pid manager. The pid is returned to the pid manager when the process completes execution, and the manager may later reassign this pid. What is most important here is to recognize that process identifiers must be unique; no two active processes can have the same pid.

When a process is created, the operating systems asks the PIDManager for a pid for that process.

&nbsp;

<h1>Programming assignment tasks</h1>
<ol>
<li>Create a new project in</li>
<li>In the src folder create a new package called concordia.processmanagement</li>
<li>In the new package, create the class PIDManager that will be responsible for allocating process id’s. The class should declare two constants to identify the range of possible pid values:</li>
</ol>
static final int MIN_PID = 300 static final int MAX_PID = 500

The class should implement the following methods:

void allocateMap()throws Exception—Creates and initializes a data structure for representing pids; throws Exception if unsuccessful

int allocatePid() throws Exception—Allocates and returns a pid; throws Exception if unable to allocate a pid (all pids are in use)

void releasePid(int pid)—Releases a pid

&nbsp;

You may use any data structure of your choice to represent the availability of process identifiers. One strategy is to adopt what Linux has done and use an array of bits in which a value of 0 at position indicates that a process id of value is available and a value of 1 indicates that the process id is currently in use. (check the <a href="https://docs.oracle.com/javase/8/docs/api/java/util/BitSet.html">BitSet </a>class in JAVA)

<ol start="4">
<li>Create a class to represent a Process Control For now, the control block should only contain the PID and the process status.</li>
<li>Create a JAVA interface to allow operations on processes. (Right click, new Java Class and then select interface in IntelliJ)</li>
</ol>
The interface should declare the following methods of the API:

int createProcess() throws Exception&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Creates a process (by creating its process control block) and adds it to the ready queue. Returns the PID of the process created. Throws exception if unable to create the process (for example if no PID are available)

&nbsp;

&nbsp;

void terminateProcess(int pid) throws Exception&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Terminates the process with the specified pid. Throws exception if the process doesn’t exist.

&nbsp;

<ol start="6">
<li>Create the class that implements the interface from step 5. When a process is created, it should ask for a PID to the PIDManager, creates a process control block and add it to a <a href="https://docs.oracle.com/javase/8/docs/api/java/util/Queue.html">queue </a>(the ready queue). When a process is terminated, it should release the PID and remove the process control block from the</li>
<li>In the main class (outside of the processcontrol package), create three scenarios to test your implementation. For example, create a process and print its PID. Terminate that Create as many processes as ID’s available and then create one one more process, you should get an error. Create as many processes as ID’s available and then terminate one process. Create one new process, there should be no error. Create one more process. There should be an error. Terminate all processes.</li>
<li>You will demonstrate your assignment to the TA after the due</li>
</ol>
&nbsp;

[5points] BONUS: Create your own exceptions to handle errors.

<h1>Deliverable</h1>
You should submit a .zip folder with the following files

<ol>
<li>A two-page pdf file including your answers to ALL questions in the</li>
<li>A pdf file including a two-page report of the programming assignment with the following sections:
<ol>
<li>High level description of the code (description of the methods/functions/threads/data structures and the flow of the program). You can use UML class and sequence diagrams or any other tool or natural language description.</li>
<li>A detailed conclusion, discussing you Please include the answer to What problems did you face?</li>
</ol>
</li>
</ol>
&nbsp;
