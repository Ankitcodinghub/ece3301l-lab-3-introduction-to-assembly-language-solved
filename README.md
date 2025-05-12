# ece3301l-lab-3-introduction-to-assembly-language-solved
**TO GET THIS SOLUTION VISIT:** [ECE3301L LAB 3-Introduction to Assembly language Solved](https://www.ankitcodinghub.com/product/ece3301l-lab-3-introduction-to-assembly-language-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91488&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECE3301L LAB 3-Introduction to Assembly language Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Introduction to Assembly language

In this lab, we are going to write in Assembly language instead of C language.

PART 1)

As you are familiar by now with the use of MPLAB X, you will need to do the same to compile an assembly program as follows:

<ol>
<li>1) &nbsp;Go to the Projects box.</li>
<li>2) &nbsp;Select the project Lab3p1</li>
<li>3) &nbsp;Right click and scroll down to ‘Copy’ and click on it</li>
<li>4) &nbsp;A box will appear with the name of the original project. Change the name of the Project
to be ‘lab3p1’ to create part 1) of lab3
</li>
<li>5) &nbsp;The project location should be with the new directory lab3\Part1</li>
<li>6) &nbsp;Select the button ‘Copy’ to create the new project</li>
<li>7) &nbsp;Once the new project is created, go to that project in the ‘Projects’ area and right click on
that new project and scroll down to ‘Set as Main Project’ and click on that. After that, the

project name should be in bold
</li>
<li>8) &nbsp;Go back and select that project again and right click on it</li>
<li>9) &nbsp;Scroll all the way down to ‘Properties’</li>
<li>10) &nbsp;A new window will pop up. On the right side under the ‘Compiler Toolchain’, instead of
selecting the XC8 compiler, you will need to select the ‘mpasm’ option. select a version

of the assembler under ‘mpasm’ and hit ‘OK’
</li>
<li>11) &nbsp;We are not going to use the C source code but instead the Assembly source code. Now
you are at the step to add the new file, do File&gt;New File. A new window will appear. Select ‘Assembler’ then ‘AssemblyFile.asm’ and hit Next. You will need to enter the new file name. In this case, I would call it ‘Lab3p1’. Hit Finish.
</li>
</ol>
The next phase is to create the assembly file. Copy the following text and paste into the file.

; THIS FIRST ASSEMBLY LANGUAGE PROGRAM WILL FLASH AN LED CONNECTED

; TO THE PINS 0 THROUGH 3 OF PORT B

#include&lt;P18F4620.inc&gt;

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
config config config config

; Constant declarations

Delay1 equ Delay2 equ

ORG

; CODE STARTS FROM THE NEXT LINE

</div>
</div>
<div class="layoutArea">
<div class="column">
START:

MOVLW MOVWF

MOVLW MOVWF

MAIN_LOOP:

MOVLW MOVWF

CALL

MOVLW MOVWF

CALL

GOTO

DELAY_ONE_SEC: MOVLW

MOVWF

LOOP_1_OUTER: NOP

MOVLW MOVWF

</div>
<div class="column">
0x0F ADCON1

0x00 TRISB

0x05 PORTB

DELAY_ONE_SEC

0x0A PORTB

DELAY_ONE_SEC MAIN_LOOP

Delay1 0x28

Delay2 0x29

</div>
<div class="column">
<ul>
<li>; &nbsp;Load W with 0x0F0</li>
<li>; &nbsp;Make ADCON1 to be all digital</li>
<li>; &nbsp;Load W with 0x00</li>
<li>; &nbsp;Make PORT B as outputs</li>
<li>; &nbsp;Load W with value 0x05</li>
<li>; &nbsp;Output to PORT B
;
</li>
<li>; &nbsp;delay one second</li>
<li>; &nbsp;Load W with value 0x0A</li>
<li>; &nbsp;Output to PORT B (flipping the LEDs)</li>
<li>; &nbsp;delay one second</li>
<li>; &nbsp;go back to repeat the main loop</li>
<li>; &nbsp;Load constant Delay1 into W</li>
<li>; &nbsp;Load W to memory 0x21</li>
<li>; &nbsp;Do nothing</li>
<li>; &nbsp;Load constant Delay2 into W</li>
<li>; &nbsp;Load W to memory 0x29</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
0x0000

</div>
</div>
<div class="layoutArea">
<div class="column">
OSC = INTIO67 WDT = OFF LVP = OFF BOREN = OFF

</div>
</div>
<div class="layoutArea">
<div class="column">
0xFF 0xFF

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
LOOP_1_INNER: NOP

DECF 0x29,F

BNZ LOOP_1_INNER

DECF 0x28,F

BNZ LOOP_1_OUTER RETURN

END

PART 2)

</div>
<div class="column">
; Do nothing

; Decrement memory location 0x20 ; If value not zero, go back to

; Decrement memory location 0x28 ; If value not zero, go back to

</div>
</div>
<div class="layoutArea">
<div class="column">
The first project is to implement the assembly code that is equivalent to part 1) of lab #2. In short, we are to read the four switches connected to PORT A and display them to the LEDs connected to PORTB.

C Code:

ADCON1 = 0x0f; TRISA = 0xff; TRISB = 0x00;

while (1) {

IN = PORTA &amp; 0x0F; PORTB = IN;

}

Compile and run the following program (make sure that this is in a new folder called lab3p2):

; THIS SECOND ASSEMBLY LANGUAGE PROGRAM WILL READ THE VALUES OF ; ALL THE BITS 0-3 OF PORT A AND OUTPUT THEM

; TO THE PINS 0 THROUGH 3 OF PORT B

#include &lt;P18F4620.inc&gt;

</div>
</div>
<div class="layoutArea">
<div class="column">
config config config config

ORG START:

</div>
<div class="column">
OSC = INTIO67 WDT = OFF LVP=OFF BOREN = OFF

0x0000

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
MOVLW MOVWF

MOVLW MOVWF

MOVLW MOVWF

MAIN_LOOP:

MOVF ANDLW MOVWF

GOTO END

</div>
<div class="column">
0x0F ADCON1

0xFF TRISA

0x00 TRISB

PORTA, W 0x0F PORTB

MAIN_LOOP

</div>
<div class="column">
; Load W with 0x0F0

; Make ADCON1 to be all digital

; Load W with 0xFF

; Set PORT A as all inputs

; Load W with 0x00

; Make PORT B as outputs

; Start of While LOOP

; Read from PORT A and move it into W ; Mask with 0x0F

; Move from W to PORT B

; Loop forever

</div>
</div>
<div class="layoutArea">
<div class="column">
After you have compiled and downloaded the program into the board, change one switch at a time and check that the corresponding LED does change according to the logic state of the switch.

PART 3)

Next, your team will implement part 2) of Lab #2 in assembly.

Take the provided code in the above Part 1) and modify it to control the RGB LED D1 connected to PORTC. Just use the c code done in Lab #2 part 2) as reference and change it into assembly based on the example code provided above.

PART 4)

We will implement now the part 3) of Lab #2. We do need to write an infinite loop with an internal loop that count from 0 to 7 and then repeat itself while outputting that count to PORTB and then call a subroutine to delay 1 second.

The following program will implement the FOR loop by using an up counter saved at the location 0x20 and it is used as an index for the color to be outputted to the PORT. In addition, it will use another counter at location 0x21h that is initialized with the value of 08h at the start. The counter at 0x20 will be incremented by 1 each time through the loop while the counter 0x21 will be decremented by 1. The counter 0x21 will be initialized with the value of 8. When it reaches the value of 0, the FOR loop is completed.

The subroutine DELAY_ONE_SEC is called once a color is outputted to the port for the purpose of creating a long delay to allow the color to be displayed for a good amount of time.

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
#include &lt;P18F4620.inc&gt; config OSC = INTIO67 config WDT = OFF config LVP = OFF

</div>
</div>
<div class="layoutArea">
<div class="column">
config BOREN =

ORG 0x0000

; CODE STARTS START:

ORG

START: MOVLW

MOVWF

MOVLW MOVWF

MOVLW MOVWF

MOVLW MOVWF

MAIN_LOOP: MOVLW

MOVWF MOVLW MOVWF

FOR_LOOP: MOVF

MOVWF CALL

INCF DECF BNZ

GOTO

END

</div>
<div class="column">
OFF

FROM THE NEXT LINE 0x0000

0x0F ADCON1

0xFF TRISA

0x00 TRISB

0x00 TRISC

<pre>     0x00
     0x20
     0x08
     0x21
</pre>
0x20,W

PORTC

DELA Y_ONE_SEC

0x20,F 0x21,F FOR_LOOP

MAIN_LOOP

</div>
<div class="column">
; Load W with 0x0F0

; Make ADCON1 to be all digital

; Load W with 0xFF

; Set PORT A as all inputs

; Load W with 0x00

; Make PORT B as outputs

; Load W with 0x00

; Make PORT C as outputs

; start of While LOOP ;loadWwith0

; store W to location 0x20 ;loadWwith08

; store W to location 0x21

; read content of 0x20 into W ; output W to PORT C

; wait one sec

; increment location 0x20 by 1

; decrement location 0x21 by 1

; if not equal, then (0x21) not equal to 0 ; go back to FOR_LOOP

; go back to While LOOP

</div>
</div>
<div class="layoutArea">
<div class="column">
Remember to add the code under ‘DELAY_ONE_SEC’ from part 1) of this lab to the above code (before ‘END’).

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
PART 5)

Modify part 4) to add the handling of the additional LED on D2 to display all the colors shown on part 4) of Lab #2.

PART 6)

From the array generated on part 5) of Lab #2, fill in a sequence of 8 values on 8 consecutive locations and then use the indirect addressing mode (with the registers FSRxL and INDFx) to fetch the color value to be outputted to the PORT(s) associated with the LEDs D2 and D3. Use the code from Part 4) to add the change.

</div>
</div>
</div>
