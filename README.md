# cmpen331-computer-organization-and-design-lab-5-solved
**TO GET THIS SOLUTION VISIT:** [CMPEN331 Computer Organization and Design, Lab 5 Solved](https://www.ankitcodinghub.com/product/cmpen331-computer-organization-and-design-lab-5-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;85583&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMPEN331 Computer Organization&nbsp;and&nbsp;Design, Lab 5&nbsp;Solved&nbsp;&nbsp;&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
This lab introduces the idea of the pipelining technique for building a fast CPU. The students will obtain experience with the design implementation and testing of the first four stages (Instruction Fetch, Instruction Decode, Instruction Execute, Memory) of the five-stage pipelined CPU using the Xilinx design package for FPGAs. It is assumed that students are familiar with the operation of the Xilinx design package for Field Programmable Gate Arrays (FPGAs) through the Xilinix tutorial available in the class website.

&nbsp;

<ol>
<li><strong>Pipelining </strong></li>
</ol>
&nbsp;

As described in lab 4

&nbsp;

<ol start="2">
<li><strong>Circuits of the Instruction Fetch Stage </strong></li>
</ol>
&nbsp;

As described in lab 4

&nbsp;

<ol start="3">
<li><strong>Circuits of the Instruction Decode Stage </strong></li>
</ol>
&nbsp;

As described in lab 4

&nbsp;

<ol start="4">
<li><strong>Circuits of the Execution Stage </strong></li>
</ol>
<strong>&nbsp;</strong>

As described in lab 5

<strong>&nbsp;</strong>

<ol start="5">
<li><strong>Circuits of the Memory Access Stage </strong></li>
</ol>
&nbsp;

As described in lab 5

&nbsp;

<h1>6.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Circuits of the Write Back Stage</h1>
Referring to Figure 1, in the fifth cycle the first instruction entered the WB stage. The memory data is selected and will be written into the register file at the end of the cycle. All the control signal have a prefix “w”. The second instruction entered the MEM stage; the third instruction entered the EXE stage; the fourth instruction is being decoded in the ID stage; and the fifth instruction is being fetched in the IF stage. All the six pipeline registers are updated at the end of the cycle (the destination register is considered as the six pipeline register). Then the first instruction is committed. In each of the forth coming clock cycles, an instruction will be commited and a new instruction will enter the pipeline. We use the structure shown in Figure 1 as a baseline for the design of our pipelined CPU.

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

Figure 1 Pipeline write back (WB) stage

&nbsp;

&nbsp;

<ol start="7">
<li>Table 1 lists the names and usages of the 32 registers in the register file.</li>
</ol>
&nbsp;

Table 1 MIPS general purpose register

&nbsp;

&nbsp;

<table width="523">
<tbody>
<tr>
<td width="174">$zero</td>
<td width="174">0</td>
<td width="174">Constant 0</td>
</tr>
<tr>
<td width="174">$at</td>
<td width="174">1</td>
<td width="174">Reserved for assembler</td>
</tr>
<tr>
<td width="174">$v0, $v1</td>
<td width="174">2, 3</td>
<td width="174">Function return values</td>
</tr>
<tr>
<td width="174">$a0 – $a3</td>
<td width="174">4 – 7</td>
<td width="174">Function argument values</td>
</tr>
<tr>
<td width="174">$t0 – $t7</td>
<td width="174">8 – 15</td>
<td width="174">Temporary (caller saved)</td>
</tr>
<tr>
<td width="174">$s0 – $s7</td>
<td width="174">16 – 23</td>
<td width="174">Temporary (callee saved)</td>
</tr>
<tr>
<td width="174">$t8, $t9</td>
<td width="174">24, 25</td>
<td width="174">Temporary (caller saved)</td>
</tr>
<tr>
<td width="174">$k0, $k1</td>
<td width="174">26, 27</td>
<td width="174">Reserved for OS Kernel</td>
</tr>
<tr>
<td width="174">$gp</td>
<td width="174">28</td>
<td width="174">Pointer to Global Area</td>
</tr>
<tr>
<td width="174">$sp</td>
<td width="174">29</td>
<td width="174">Stack Pointer</td>
</tr>
<tr>
<td width="174">$fp</td>
<td width="174">30</td>
<td width="174">Frame Pointer</td>
</tr>
<tr>
<td width="174">$ra</td>
<td width="174">31</td>
<td width="174">Return Address</td>
</tr>
</tbody>
</table>
&nbsp;

&nbsp;

<ol start="8">
<li>Table 2 lists some MIPS instructions that will be implemented in our CPU</li>
</ol>
&nbsp;

Table 2 MIPS integration instruction

&nbsp;

&nbsp;

&nbsp;

<ol start="9">
<li>Initialize the first 10 words of the Data memory with the following HEX values:</li>
</ol>
A00000AA

10000011

20000022

30000033

40000044

50000055

60000066

70000077

80000088

90000099

&nbsp;

<ol start="10">
<li>Write a Verilog code that implement the following instructions using the design shown in Figure 1. Write a Verilog test bench to verify your code: (You have to show all the signals written into and out from the MEM/WB register and the inputs to the Regfile block in your simulation outputs)</li>
</ol>
&nbsp;

instruction &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; comment

lw $2, 00($1)&nbsp; # $2 ßß memory[$1+00]; load x[0]&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; lw $3, 04($1)&nbsp; # $3 ßß memory[$1+04]; load x[1] lw $4, 08($1)&nbsp; # $4 ßß memory[$1+08]; load x[2] lw $5, 12($1)&nbsp;&nbsp; # $5 ßß memory[$1+12]; load x[3] add $6, $2, $10

&nbsp;

Assume that the register $1 has the value of 0

&nbsp;

&nbsp;

&nbsp;

&nbsp;

<ol start="11">
<li>Write a report that contains the following:
<ol>
<li>Your Verilog design code. Use:</li>
<li>Device: XC7Z010- CLG400 -1 or choose any other FPGA type. You can use Arria II if you are using Quartus II software.</li>
<li>Your Verilog® Test Bench design code. Add “`timescale 1ns/1ps” as the first line of your test bench file.</li>
<li>The waveforms resulting from the verification of your design with ModelSim showing all the signals written in and out from the MEM/WB register and the inputs to the Regfile block.</li>
<li>The design schematics from the Xilinx synthesis of your design. Do not use any area constraints. &nbsp;&nbsp; Snapshot of the I/O Planning and</li>
<li>Snapshot of the floor planning</li>
</ol>
</li>
</ol>
&nbsp;

<ol start="12">
<li>REPORT FORMAT: Free form, but it must be:
<ol>
<li>One report per student.</li>
<li>Have a cover sheet with identification: Title, Class, Your Name, etc.</li>
<li>Using Microsoft word and it should be uploaded in word format not PDF. If you know LaTex, you should upload the Tex file in addition to the PDF file.</li>
<li>Double spaced</li>
</ol>
</li>
</ol>
&nbsp;

<ol start="13">
<li><strong>You have to upload the whole project design file zipped with the word file. </strong></li>
</ol>
<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<ol start="14">
<li><strong>For students who took this class as an (honor option).</strong> <strong>In addition to all of the above requirements, you need to design the following:</strong></li>
</ol>
&nbsp;

In order to focus our attention on the WB stage easily, the baseline CPU shown in Figure 1 is redrawn by putting the register file on the WB stage where the execution result of an instruction is written as shown in Figure 2. The state of the art content can be read correctly in the ID stage after it is written at the end of its WB stage. Data hazards occur in the code example shown in Figure 3. You need to add the required components to solve the hazard problem and do forwarding if needed.

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

Figure 2 Writing result to the register file in the write back stage

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

Figure 3 Data hazard examples

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<ol start="15">
<li>Initialize the first 11 words of the register (Regfile block) with the following HEX values:</li>
</ol>
00000000

A00000AA

10000011

20000022

30000033

40000044

50000055

60000066

70000077

80000088

90000099

&nbsp;

<ol start="16">
<li>Write a Verilog code that implement the instructions using the design shown in <strong>Figure 3</strong>. Write a Verilog test bench to verify your code: (You have to show qa and qb signals that output from the Regfile block in your simulation outputs)</li>
</ol>
&nbsp;

&nbsp;

<ol start="17">
<li>Write a report that contains the following:
<ol>
<li>Your Verilog design code. Use:</li>
<li>Device: Zyboboard (XC7Z010- -1CLG400C)</li>
<li>Your Verilog® Test Bench design code. Add “`timescale 1ns/1ps” as the first line of your test bench file.</li>
<li>The waveforms resulting from the verification of your design with ModelSim showing all the signals written in and out from the MEM/WB register and the inputs to the Regfile block.</li>
<li>The design schematics from the Xilinx synthesis of your design. Do not use any area constraints. &nbsp;&nbsp; Snapshot of the I/O Planning and</li>
<li>Snapshot of the floor planning</li>
<li>Generate the bitstream.</li>
<li>The design should be free from errors when synthesized, implemented and generated of bit stream.</li>
</ol>
</li>
</ol>
<strong>&nbsp;</strong>

<ol start="18">
<li><strong>You have to upload the whole project design file zipped with the word file. </strong></li>
</ol>
&nbsp;
