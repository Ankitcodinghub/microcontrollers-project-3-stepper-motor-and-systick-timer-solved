# microcontrollers-project-3-stepper-motor-and-systick-timer-solved
**TO GET THIS SOLUTION VISIT:** [Microcontrollers Project 3-Stepper Motor and SysTick Timer Solved](https://www.ankitcodinghub.com/product/microcontrollers-project-3-stepper-motor-and-systick-timer-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101248&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Microcontrollers Project 3-Stepper Motor and SysTick Timer Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Stepper Motor and SysTick Timer

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol>
<li>Understand the basic concept of system timer (SysTick)</li>
<li>Learn how to use SysTick to create a time delay function</li>
<li>Understand the basic procedure of interrupt handling</li>
<li>Understand the limitation of GPIO output current, and learn to use Darlington
transistor arrays to perform high-current driving with low input current
</li>
<li>Understand the usage of full stepping and half stepping to control the speed and
position of a stepper motor
</li>
</ol>
Project Submission.

<ol>
<li>Zip your whole project folder and submit it on Blackboard.

If your submission does not contain the whole project, 50% of the total points will be deducted.

If your code cannot be compiled or built successfully, 50% of the total points will be deducted.</li>
<li>Write a README document (in PDF format) to briefly
<ol>
<li>describe the basic structure of your project,</li>
<li>explain how to test your project to demonstrate that it works correctly,</li>
<li>describe your test procedure and results and use some pictures to show your
test. (optionally, you can make a video to demonstrate how you have tested your project.)
</li>
</ol>
</li>
</ol>
Project Assignment

Write a Keil uVision 5 project with C code to generate delay by SysTick timer interrupt which will control the rotation speed of a stepper motor. Your code needs to use two different buttons of the joystick to give two different speeds to the stepper motor.

Press the up button of the joystick to turn the stepper motor exactly 360 degrees clockwise by using half-stepping, and press the down button to turn the motor exactly 180 degrees counter-clockwise by using half-stepping.

Interfacing the stepper motor requires four pins. You should select the following four pins to control the stepper motor: PB 2, PB 6, PB 3, and PB 7. The textbook provides a connection diagram for stepper motor Mabuchi #PF35T, which is very similar to the diagram below.

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Note that the four output pins should be configured as open-drain. In your project, you can output the following bit sequence for either full stepping or half stepping. Full stepping bit sequence has 4 output bit combinations continuously looping, and half stepping bit sequence has 8 output bit combinations continuously looping.

Between any two bit combinations in a bit sequence, your code needs to generate a certain amount of time delay by using SysTick’s delay function (recall it is in an example project). For example, to output the first bit combination in the full stepping bit sequence, i.e., 􏰀 = 1, 􏰀􏰁=0, 􏰂 = 1, 􏰂􏰁=0, your code needs to output PB2=1, PB3=0, PB6=1, and PB7=0.

Full Stepping Bit Sequence (this sequence includes 4 pulses, i.e., 4 step angles, then 512=2048/4 such sequences will make outside shaft rotate 360 degrees).

􏰀1100 􏰀̅ 0 0 1 1 􏰂1001 􏰂􏰃 0 1 1 0

Half Stepping Bit Sequence (this sequence includes 8 pulses, still has 4 step angles due to half stepping, so 512=2048/4 such sequences will make outside shaft rotate 360 degrees).

􏰀11100000 􏰀̅ 0 0 0 0 1 1 1 0 􏰂10000011 􏰂􏰃 0 0 1 1 1 0 0 0

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Grading Rubric

<ol>
<li>(10 pts) for README document.</li>
<li>(40 pts) for your project code to implement the above assigned task.</li>
</ol>
Preparation

<ol>
<li>Read the textbook Chapter 16 Stepper Motor</li>
<li>Watch video tutorial: How the Stepper motors are made and how they operate
(Credit goes to pcbheaven)

<ol>
<li>Part 1 (5 minutes): http://www.youtube.com/watch?v=MHdz3c6KLrg</li>
<li>Part 2 (8 minutes): http://www.youtube.com/watch?v=t-3VnLadIbc</li>
</ol>
</li>
<li>Read Chapter 11.7 System Timer</li>
<li>Processor Clock. You may use the example project’s system clock code, which gives
80MHz clock signal. For your reference, four different clock sources can be used to drive the system clock (SYSCLK):
</li>
</ol>
a) 16MHz HSI (high-speed internal) oscillator clock

b) 4-48MHzHSE(high-speedexternal)oscillatorclock

c) PLL (phase-locked loop) clock that is clocked by HSI, HSE, and MSI. d) MSI(multispeedinternal)oscillatorclock

Stepper Motor

The motor set in your lab kit has a ULN2003 Darlington Array.

4

1/64

DC resistance per phase 50Ω±7%(25°C) Pull in torque &gt;300gf.cm / 5VDC 100pp

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Motor model

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
28BYJ-48

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Number of phases

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Rated voltage

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
5V DC

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Geared reduction ratio

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
The gear ratio is:

</div>
<div class="column">
image from forum.arduino.cc 31 × 32 × 26 × 22 = 63.68395

11 × 10 × 9 × 9

</div>
</div>
<div class="layoutArea">
<div class="column">
If the output shaft rotates 1 resolution (gear with 31 teeth in the figure), the internal shaft (gear with 9 teeth in the middle) must rotate approximately 64 resolutions.

<ul>
<li> &nbsp;Internal motor: 32 steps per revolution</li>
<li> &nbsp;Great reduction ratio: 1/63.68395, approximately 1/64</li>
<li> &nbsp;Thus, it takes 32 × 64 = 2048 steps per revolution for the output shaft
Warning: Motor Overheating

The motor constantly draws electrical currents. The motor will be overheated if you leave the power on for an extended period. Make sure to disconnect the power (Vcc) to the Darlington array if you are not debugging/testing it.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
