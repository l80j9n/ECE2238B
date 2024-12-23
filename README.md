java c
ECE2238B Homework Assignment 1 
Linear Electric Circuits 
Due:   2024 02   16 by   23:55
Instructions 
This ﬁrst homework problem covers questions about linear electric circuits.   It   focuses on calculating transient   response and on using nodal and loop analysis techniques to solve dc and ac circuits.
•      Each of you has an unique copy of the homework assignment   (i.e., this document) delivered to your Drop- box on   OWL.
•      Please upload your answers to the “Homework 1” Tests  Quizzes assessment on OWL.
•      The submission form. on OWL does not include any questions, only ﬁelds to upload your answers.   As there   are many variations on each question, you will need to ahve your assignment paper   (i.e.   this document) handy to answer the questions.
•      Feel free to work in groups, but be sure to upload the answers for your questions, as that is how your work   will be graded.
1 First Order Transients [8 Marks] 
Consider the circuit shown below. You may assume the switch has been held in the position shown for a long   time, then thrown in the direction shown by the arrow at t = 0.

1.      Calculate ix   and vC   for t < 0. [2 marks] 
2.      Calculate   ix   and   vC      as   t   → ∞   . [2 marks] 
3.      Calculate ix   at the instant t = 0. [2 marks] 
4.      Calculate the equivalent resistance Req, as seen by the capacitor, and the time constant τ for the circuit   when   t   ≥ 0. [2 marks] 
2 Second Order Transients [10 Marks] 
Consider the circuit shown below. You may assume the switch has been held in the position shown for a long   time, then thrown in the direction shown by the arrow at t = 0. 

1.      Calculate   vC   (t) and   iL   (t) for   t   < 0. [2 marks] 
2.      Calculate   vC   (t) and   iL   (t) for   t   → ∞   . [2 marks] 
3.      This circuit has either the capacitor and inductor in series or in parallel with each other, so ω0   given by:

and ζ is given by one of:
or  
where Req   is the equivalent resistance seen by the capacitor and inductor together.   Calculate ω0   and Req   .   Which is the appropriate deﬁnition of ζ for your circuit?   Use that to calculate ζ   .
4.      What is the appropriate damping regime for t ≥ 0 in your circuit? [1 marks] 
(Note:   Base your answer on ζ rounded to at least two decimal places.   If the result is within 土0.005 of two
diﬀerent damping regimes and you aren’t sure which way to round,   just pick one — I’ll accept either
answer as correct.   Most of you, however, have a circuit with a ζ that is clearly within only one damping   regime.)
5.      Based on position of the switch and the damping regime, iL   for t ≥ 0 is given by one of:

or                                                   = exp   (—ζω0t) [B1   cos   (ωdt) + B2   sin   (ωdt)] + B3
or                                                      =   (D1   + D2t)   exp   (—ω0t) + D3
Find all the remaining unknown quantities in the expression for iL   for t ≥ 0 as appropriate for your circuit.   (I.e., if your circuit is overdamped, ﬁnd constants A1, A2, and A3.) [2 marks] (Note:   代 写ECE2238B Homework Assignment 1 Linear Electric Circuits 2024C/C++
代做程序编程语言If you are confused   by the third constant A3   /B3   /D3, recognize that all time-dependent parts of the   above expressions disappear as t   →   ∞,   but depending on your circuit, vC (t   →   ∞   ) or iL   (t   →   ∞   ) could be      non-zero.)
3 Nodal Analysis [9 Marks] 
Consider the following circuit. We will solve this circuit using nodal analysis.   The nodes are already labelled.

1.      Does this circuit   have any supernodes?   If it does, identify them. [1 mark] 
2.      Nodal analysis is most easily performed using conductances.   Calculate the conductance of all resistors,   accurate to two decimal places   (in units of mS = kΩ-1). [1 mark] 
3.      Write the four nodal equations.   These equations are either KCL-type equations of the form.
0 = ± (Gx    + Gy   )   vq ± (Gy    + Gz   )   vp ± · · · 
or voltage balance-type equations of the form.
VS      =   vq ± vp ± · · · 
for conductances Gx, Gy, Gz, voltage source VS   , and nodes   p and q.   Please provide these equations symboli-   cally   (i.e., write “Gx” for conductance Gx   rather than “1.35   mS”). [2 marks]
4.      Write the nodal equations in matrix form.   Please write these equations numerically, and omit the units   (all voltages should be in V, all currents should be in mA, and all conductances should be in mS = kΩ-1). [2 marks] 
5.      Solve the nodal equations to obtain the node voltages. [2 marks] 
6.      Calculate the current ix. [1 mark] 
4 Loop Analysis [12 Marks] 
Consider the following circuit.   This is an AC circuit with   ω   =   100.0   krad/s.   We will solve this circuit using loop   analysis.   The loops are already labelled.

1.      Does this circuit have any superloops?   If it does, identify them. [1 mark] 
2.      For an AC circuit we need impedances.   Calculate the impedance of all resistors, capacitors, and inductors,   accurate to two decimal places   (in units of kΩ). [2 marks] 
3.      Write the four loop equations in phasor notation.   These equations are either KVL-type equations of the   form.
0 = ± (Zx   + Zy   )   iq ± (Zy      + Zz   )   ip ±
· · · or current balance-type equations of the form.
IS    =   iq ± ip ± · · · 
for impedances Zx, Zy, Zz, current source IS   , and loops   p and q.   Please provide these equations symboli-         cally   (i.~e., write “Zx” for impedance Zx   rather than “(1.23 —   0.78j)   kΩ”, and   just write “iq” for loop current   phasor iq   ). [2 marks] 
4.      Write the loop equations in matrix form.   Please write these equations numerically, and omit the units   (all   voltages should be in   V, all currents should be in mA, and all impedances should be in kΩ).   Complex val-   ues should be written in rectilinear form   (x +   jy). [2 marks] 
5.      Solve the   ~loop equations to obtain the loop current phasors.   Please express these current phasors in polar   notation, iq    = Iq   \θq, where Iq   is in mA and θq   is the phase angle in rad. [3 marks] 
6.      Calculate the voltage vx   (t) as a function of time. [2 marks] 







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
