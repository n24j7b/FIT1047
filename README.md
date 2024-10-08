java c
FIT1047   Introduction to computer systems,   networks and   security - S2   2024
Assignment 2 –   Processes and   MARIE   Programming
Purpose
Processes and programs are what makes computers   do   what   we   want   them   to   do.   In the first   part of this assignment, students will investigate the   processes         running on their computers. The second part   is   about   programming   in   MARIE         assembly language. This will allow students to demonstrate   their
comprehension of the fundamental way a processor works.
The assignment   relates to   Unit   Learning Outcomes 2, 3 and 4.
Your task
Part   1a: Submit your reflections. See details   below.
Part   1b: Write a short   report describing the processes   running   on your   computer.
Part   1c:   Disassemble and add comments to a   MARIE   program.
Part   1d: Write a   MARIE   program that can display bitmap   numbers.
Part 2:   In-class   In-person   Interview   (week 8 applied session)
Value
25% of your total marks for the   unit
The assignment is marked   out   of 60   marks.
Word   Limit
See individual   instructions
Due   Date
Part   1a-1d:   11:55   PM   Friday 30 August 2024
Part 2:   Interview conducted during Week 8 your official   allocated   Applied Session
Submission
●         Via   Moodle Assignment Submission.
●          DRAFT submission is not   assessed.   Re-check   your   submission   in   Moodle.
●          Turnitin will be used for similarity checking   of all   submissions.   Ignore   Turnitin warning or error messages for .mas files   or other
non-document files.
●          DRAFT   upload confirmation email from Turnitin   is   not a   submission. You   must click the submit button to accept terms   and   conditions   in   Moodle.
●          This   is an individual assignment (group work   is   not   permitted).
●          In this assessment, you   must   not use   generative   artificial   intelligence   (AI)   to generate any materials or content   in   relation to the   assessment   task.
●          Turnitin and   MOSS will be used for similarity   checking   of all   submissions.   This   is an individual assignment (group work   is   not   permitted).
●          You will   need to explain and extend your code   in an   interview.   (Part   2)
INSTRUCTIONS
This assignment has five parts.   Make sure you   read the   instructions   carefully.For Part   1a, collect your reflections from each week’s   Ed   Lesson   and   create   a   single   PDF   document. You   can simply copy/paste your reflections, but   please add   headings for   each week.   Submit   the   PDF   through   the   Moodle Assignment activity.
For Part   1b-1d, you   need to submit files through the   Moodle Assignment activity.
Files are required via   Moodle Assignment Submission:
●   Part   1a: one pdf file (containing reflection from Week 4,   5   and   6)
●   Part   1b: one pdf file (containing answer)
●   Part   1c: one   .mas file for Part   1c
●   Part   1d: one   .mas file for Part   1d
You may see the following error message from   Turnitin. You   can   ignore   this   error   message!

Part 2   is an   in-class   interview during your allocated Applied Class   in Week 8.   Instructions   will   be   available   in   Moodle and communicated via an announcement   post.
Part   1a:   Reflection (Hurdle - you   MUST submit   it   in order to   pass this   assignment!)
Complete your reflection activities   in Week 4 to Week 6   Ed   Lesson   and   copy/paste them   into   a   pdf file.   Each week the   reflection   must   have at   least   100 words (relevant and   meaningful to the   specific   week).
Failure to submit all   relevant    week’s reflections (missing all   submissions      or   incomplete submissions) will   result   in your assignment   1   having a maximum mark   of49% only.   For example,   if the overall combined   mark   is 61/100,   it will   be scaled to   49/100.   If   the overall combined   mark   is 44/100 then it will   remain as   44/100.
You   may   use this template:
https://docs.google.com/document/d/18UIEJQeyarYW1pl8oDEaf--ubCdJ5LDf-9_jSLbGxrE/edi   t?usp=sharing      to write down your reflection.
Part   1b:   Process (10 marks   total)
For this task, write a brief report about   processes that you   observe   running   on   your   computer. You can use one of the following tools   (depending on your   operating system): On Windows, use   the   Task   Manager
On   macOS, use the Activity   Monitor
On   Linux,   use a command   line tool   like   htop, top, or the   ps command   Answer the following questions:
1.   Briefly describe the columns displayed   by the tool you   use that   relate to   a)   memory usage and   b) CPU usage of a   process. What can   you   say   about   the   overall   memory   usage of all   processes, compared to the   RAM installed in   your   computer?   Include graphs or charts for the comparison.   (5   marks)
2.   Pick a   process you   perhaps don’t   know   much about, or which you did   not   expect to   find   running on your computer. Try to find out and   describe   briefly what   it   does.   (5      marks)
Include a screenshot of your processes in the   report   along with   CPU/memory   usage   graphs and/or charts. The screenshot should show between   5   and   10   processes.   The   word   limit for this   part (both questions together)   is 500 words   (about   1   page,   not   including   images   and   tables).
Submit your report for this   part (Part   1b) as a   PDF file   (independent   of the   other   parts)   in   Moodle.
Part   1c:   MARIE   Disassembly (20 marks   total)
Follow the link on   Moodle to access your personalised   MARIE   memory   screenshot   for   this   task.
Important: Your memory screenshot   is different from the one other students   are   working on. Only download the file while you are correctly   logged   into   Moodle   with   your own student account.
Task   1:   Disassemble the   memory   (10   marks)
Based on the   memory contents, recreate the   MARIE program   that   corresponds   to   your personalised   memory screenshot. This   is called “disassembling” the machine   code,   since   it   is the opposite operation of “assembling” the   MARIE code   into the   binary   memory   contents.
For each   memory cell, decode the instruction and   (if applicable) the   address   that   the   memory cell   is encoding. You can make the following   assumptions:
- There   is exactly one   Halt   instruction   in the code
-   Every   memory   location after the   Halt   instruction contains data
- Any   memory   location that contains the value 0   is data (even   before   the   Halt   instruction)
Here   is an example of a   memory screenshot and the corresponding   decoded   MARIE   program:

Disassembled program:
Input
Add   005   Output
Jump   000   Halt
DEC   10
Note: You   need to decode the actual   instructions.   E.g. for the first   memory location,   HEX   5000   would   not   be a valid answer. The contents of all   memory that follows   the   Halt   instruction   is   considered to   be data. Therefore,   DEC   10   is the correct decoding of location   5   (instead   of JnS   00A), and   HEX 00A would also   be correct. You don’t   need to   list   all   the   locations   containing zeros starting from address 006 (these will be   filled with   zeros   by   the   assembler   anyway).
Tip: You can verify that your disassembled code   is correct   by   entering   it   into the   MARIE   simulator, assembling   it and comparing the memory contents   to   the   screenshot   you   started   from.
Task 2: Add   labels   (5   marks)
Now   update the   program you decoded   in Task 2.1.   Removing all   hard-coded   memory   addresses   by adding labels to replace all   memory   locations that   are   used   as   addresses in the   program   instructions.   Labels should   have   meaningful   names   in the context of what   the   program does (i.e.,   not just A,   B, C).   For the example above, this   could   result   in the following program:
MainLoop,   Input
Add Ten
Output
Jump   MainLoop
Halt
Ten,   DEC   10
Task 3: Add comments   (5   marks)
Comment the code based on your understanding   of what   it does.   Comments   should describe the function of the different   parts.   E.g.,   if you   identify a subroutine   in the code, add   a comment at the start of the subroutine that describes what   it   does,   and whether   it   takes any arguments.
For this   part (Part   1c), you   need to submit one   .mas file containing your final   code.   Do   not submit one   .mas file per each subtask!
Part   1d:   MARIE   Programming (22 marks total)
In this task you will develop a   MARIE application that draws   numbers   on   the   screen. We   will   break   it down   into steps for you.Note:   This   part   is for students who want to achieve a   Distinction or   High   Distinction   mark   in   this   assignment. In order   to receive   any    marks   for   this    part,   you   must   reach   at   least   a   Credit grade for   Parts   1, 2   and   3.
Each task requires you to write code and documentation.   On   Moodle,   you   wil代 写FIT1047 Introduction to computer systems, networks and security - S2 2024 Assignment 2R
代做程序编程语言l   find   a   template for the code (or click this to download). Your submission   must   be   based on   this template,   i.e., you must   add implementations of your own   subroutines   into   the template. The template already contains the main   program that   calls the   subroutines.
Your code must contain readable comments   and   meaningful   labels for   your   tutor /   marker to understand the logic flow of your program   (e.g.   the   purpose   of a   subroutine,   jump   /   skip   cond statement etc.).In-class    interview   (Part   2):   You   will    be   required   to   join   an   interview   to   demonstrate   your   code   to   your   tutor   during   your   applied   session   in   week   8   (after   the   submission   deadline).   Failure   to   demonstrate   will lead   to   zero   marks   being   awarded   for   the   entire Part 1d, regardless    of   your   submission in Moodle. In addition,   during   the   interview   (Part   2),   you   will   also   need   to   answer further   questions   about   your   submitted   code (see   below for details).
Code similarity: We use tools such as   MOSS and   Turnitin to   check   for   collaboration   and   copying between students.   If you copy parts of your code from   other   students,   or you   let   them copy   parts of your code, this will result   in a   report to   the Academic   Integrity   team. As   a   result, you may   receive a   penalty such as 0   marks for the   entire   assignment,   0   marks   for the whole   unit, or in severe cases (such   as   contract   cheating),   suspension   or   expulsion from   Monash   University.
Rubric: The   marking rubric on   Moodle provides details for the   marking. A   correctly working   MARIE   program that covers all tasks and is well   documented will   receive full   marks.
Missing/incomplete documentation will   result   in a loss of up to   ¼   of the task’s   marks.
Introduction:   Bit-mapped   displays
So far, the only output capability we   have seen   in the   MARIE system   is   using   the   Output   instruction, which will   print a single   16-bit value.   Many computers of course are   capable of   displaying arbitrary graphics, often   in   high resolution and great   colour   depth.   In   the   lectures on   input/output systems, we   have seen that one way to   implement this   is to   map   a certain location of the   memory to an output   device.   I.e., writing to   that   memory   location      (using e.g. a Store   instruction) causes the output   to   happen.In   the   simplest form. of graphics   hardware, we can dedicate   part of the   RAM to be   graphics   memory.   Each   memory cell corresponds to a pixel on screen, and the value   in the   memory   cell   encodes   the   colour of the   pixel.   That   way,   we   can   create   arbitrary   graphics   by   simply   writing values into the   memory.
The   MARIE simulator has a feature called Display, which you   access from   the   list   of tabs   that also shows the output   log,   RTL   log   etc:

The display shows the   memory from address   F00 to address   FFF as   a   16x16   pixel   screen. The value   in the   memory locations represents the colour of the   pixels. We   will   only   use   the colours   black,   represented as 0, and white,   represented   as   FFFF. When you start   the   MARIE   simulator and assemble your code, the memory starting from   location   F00   is   (usually) filled with zeroes, which   means that the display   is black.   Let’s now   change   the   contents   of   the memory using some   Store   instructions:Load WhiteStore   0F80Store   0F81Store   0F82Store   0F83Halt
White,   HEX   FFFF
After running this program, the display   will   look   like   this:
   
You can see that the first four pixels   in the   9th   row   have   now turned   white.
Task   1 Clearing the display   (4   points)
Write a subroutine SubClearDisplay that turns all pixels   in   the   graphics   memory white.
Remember that the graphics   memory ranges from address 0F00 to   address   0FFF,   and   that   white   pixels are   represented   by the value   FFFF.   Document your subroutine with comments.
Task 2   Painting a   number   (10   points)The template for this task contains data for bitmaps of the   digits   0-9,   stored   at the   label   Font.   Each digit consists of 3x5   pixels of data. The first 3 words   are   the   first   row   of   pixels,   the   next      3 words are the second   row, and so on.   For example,   the   digit   2   is   represented   as   0   0   FFFFFFFF   FFFF   0FFFF   0   FFFF0   FFFF   FFFF0   0   0
You can see the   pattern   here, the zeros “paint” the shape   of the   character   2   in   black, with   the   background in white   (FFFF).
Your task   is to write a subroutine called SubPaintDigit   that   paints a   digit   into the   graphics   memory. The start of the subroutine   needs to look   like   this:
PaintDigitCharacter,   HEX 0
PaintDigitDisplay,   HEX 0
SubPaintDigit,   HEX 0
In the   PaintDigitCharacter argument, we   pass the address of the first   pixel data   in the   font for   the digit we want to   paint.   In the   PaintDigitDisplay argument, we pass the   address   of the top-left corner where we want to start   painting   in the graphics memory.   For example,   to   paint      the digit 0, starting from the second   pixel   in the second   row, we   could   use   the   following   code:
Load   FontAddr
Store   PaintDigitCharacter
Load   Display22
Store   PaintDigitDisplay
JnS SubPaintDigit
Halt
Display22,   HEX 0F11
Note that the address 0F11 (label   Display22)   lies exactly   17 words   after the   start   of the graphics   memory. This   means we’re skipping the first   row (16 words) and the first   pixel   in   the   second row   (1 word).
Here we simply use   FontAddr to   refer to the first character (for   the   digit   0).   For   the other characters, we would   have to add a corresponding offset   into the font   memory.
In order to   paint a digit   in your subroutine, you can follow   this   “recipe”   :
- Your subroutine should contain two   nested   loops.
-   Each digit contains   15   pixels, so you   need to   loop through those   15   pixels,   load each
one from the font definition and store   it   into the graphics   memory. This   is   the   outer   loop of your subroutine.
- After each set of 3   pixels, you   need to start   in   the   next   row of the   graphics   display.   This   means that   if you were currently writing into graphics memory at   address X, you   now   need to continue writing at address X plus the width of the display minus the width   of   a character. This   is the   inner loop of your subroutine.
- Once you   have “copied” all   15   pixels from the font definition   into   the   graphics   memory, you can exit the   subroutine.
Your subroutine   needs to contain sufficient comments to enable someone   else   (like   the   person   marking your assignment) to understand the purpose of each   line   of your   code.
Task 3 Counting   down   (8   points)
Your final task   is to   implement a subroutine SubCountDown that clears the   screen   and then   counts down from 9 to 0, drawing those digits   on   the   bit-mapped   display   using   the subroutines developed in the   previous tasks.
In order to get full   marks, your code   needs to use   a   loop that   decrements   a   counter   and   calls SubPaintDigit   based on the value of the counter, rather than   a   sequence   of   instructions that calls SubPaintDigit with each digit’s address.   Use additional   subroutines to   structure   your   code   nicely.
You will   notice that   it would   be   nice for the countdown to wait for a fraction of a second   between digits. Think of a way you can achieve this, so   that   the   countdown   takes   (more   or less) exactly   10 seconds on your computer to execute.   Document   how you achieved   this   in   the code   comments.
A sample output video for this   part (part   1d) is   provided for your   reference:
https://drive.google.com/file/d/1NQPMNCuLoVxf7dD8omFqacS9SRCcefQC/view?usp=driv   e_link
For this   part (Part   1d), you   need to submit one   .mas file,   based on the   template,   containing the code for all subroutines.   Do   not submit one   .mas file per each subtask!
Part 2:   In-class   interview (8 marks   total)
You   need to demonstrate the code you submitted for   Part   1d Task   1–3 to   your   tutor   in   an   in-class   in-person   interview (to   be conducted during your official allocated Applied   session   in Week 8) after the submission deadline.   Failure to explain   how your   code works   will   result   in 0   points for the   individual tasks that you cannot demonstrate.In addition, you will   be asked to   modify the code you submitted   in   certain ways   and   explain how the   MARIE concepts work that you were required to   use for the   individual tasks.   These   additional questions add up to 8   points   for   this   part   (Task   4).
Failure to attend the   interview will   result   in 0   points for the entire   Part   1d and   Part 2,   regardless of your submission   in   Moodle.

   

         
加QQ：99515681  WX：codinghelp
