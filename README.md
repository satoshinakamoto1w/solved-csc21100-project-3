Download Link: https://assignmentchef.com/product/solved-csc21100-project-3
<br>
<span class="kksr-muted">Rate this product</span>

In this project, students are expected to use the Xilinx ISE Design Suite (Webpack edition) 14.7 to complete the following tasks.

Please read the instructions carefully. Failing to follow the instructions would lead to significant point deductions.

Task 1: 2-to-4 Decoder

A 2-to-4 decoder operates according to the following function table.

Implement a 2-to-4 decoder in VHDL using structural design: Please adopt the following as the entity declaration.

Note that, many logic gates are defined in the UNISIM library. In order to use these gates, you need to add the following lines in your VHDL program to include the UNISIM library.

Write a test-bench program and run simulations to validate your design: Use the given test cases below in your test-bench program. Pay attention to the signal names, signal values, and the time.

Deliverable(s):

Requirement(s):

(1) You must follow the structural design method. (2) You must follow the submission guidelines.

Note: no points will be given if any of the requirements are not satisfied.

Rubric (Report)

<ol>

 <li>1.1.  Use your own language to describe the function of the module to be implemented in VHDL. (1 point)</li>

 <li>1.2.  Include your VHDL entity declaration(s), architecture definition(s) and the testbench program. (1 point)</li>

 <li>1.3.  Show simulation results (e.g. the waveforms). Explain the outcome of each test case with screenshots. Show why the simulation result is correct. (1 point)</li>

</ol>

Rubric (Source Code)

<ol start="4">

 <li>1.4.  Can compile without any errors. (1 point)</li>

 <li>1.5.  Can run simulations without any errors. (1 point)</li>

</ol>

Task 2: 3-to-8 Decoder (7 points)

Implement a 3-to-8 decoder using the 2-to-4 decoder you have implemented in Task 1. The input to the 3-to-8 decoder should be labeled as A. It needs to be a 3- bit bus. The output should be labeled as O, which is an 8-bit bus. Please use the following entity declaration for the 3-to-8 decoder.

Note that: (1) please adopt the structural design approach; (2) in addition to the 2- to-4 decoders, you also need to include some logic gates to make it work.

3|Page

In order to use the 2-to-4 decoder from Task 1, you will need to declare the 2-to-4 decoder as a component in the VDHL architecture definition of the 3-to-8 decoder:

Then you can use the decoder like this:

Once you successfully completed the implementation of the VHDL module, write a test-bench program and run simulations to validate your design. Use the given test cases below in your test-bench program. Pay attention to the signal names, signal values, and the time.

Deliverable(s):

Requirement(s):

(1) You must follow the structural design method. (2) You must use the module(s) implemented before. (3) You must follow the submission guidelines.

Note: no points will be given if any of the requirements are not satisfied.

Rubric (Report)

<ol>

 <li>2.1  Use your own language to describe the function of the module to be implemented in VHDL. (1 point)</li>

 <li>2.2  Draw a circuit diagram of the module to show the design. (1 point)</li>

 <li>2.3  Include your VHDL entity declaration(s), architecture definition(s) and thetestbench program. (1 point)</li>

 <li>2.4  Show simulation results (e.g. the waveforms). Use the simulation results toexplain why the implemented circuit is working correctly. (2 points)</li>

</ol>