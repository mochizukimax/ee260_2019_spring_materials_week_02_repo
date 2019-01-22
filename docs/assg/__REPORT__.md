---
title: week2assg
author: Max Mochizuki
partner:
date: 01/21/2019
---

In the report, complete the following.
- Explain the objective of the problem.
- Give your solution.
- Include all your project codes in the [codes/assg](../../codes/assg) folder,
  if required.
- Explain your code snippets, if required.
- Include screenshots of the simulations in this folder, and insert them into
  the markdown file, if required.
- Explain why the simulations are correct, if required.

You can embed math equations into Github Markdown file using a [web service](https://www.codecogs.com/latex/eqneditor.php)

## (5 pts)
What is a digital signal and how does it differ from an analog signal? Give two
everyday examples of digital phenomena (e.g., a window can be open or closed) and
two everyday examples of analog phenomena. 

A digital signal can only have specific values within a finite set of possible values, while 
an analog signal is continuous and contain an infinite range of possible values. Two examples 
of digital signals are light switches, which can be on/off, and the keys on a keybaord which 
can be pressed or not pressed. Two examples of an analog signal are microphones which can record 
a range of sounds, and a clock where the "hands" of the clock are continuously moving and changing.

## (5 pts)
Assume that a signal is encoded using 12 bits. Assume that many of the encodings
turn out to be either 000000000000, 000000000001, or 111111111111. We
thus decide to create compressed encodings by representing 000000000000 as
00, 000000000001 as 01, and 111111111111 as 10. 11 means that an
uncompressed encoding follows. Using this encoding scheme, decompress the following encoded stream:

00 00 01 10 11 010101010101 00 00 10 10

000000000000 000000000000 
000000000001 111111111111 
111111111110 010101010101
000000000000 000000000000
111111111111 111111111111

## (5 pts) Wakerly, Problem 2.2 (a)-(c)
Convert the following octal numbers into binary and hexadecimal:
- a. <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;${100011010001}_{2}&space;\\&space;${8D1}_{16}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;${100011010001}_{2}&space;\\&space;${8D1}_{16}" title="${100011010001}_{2} \\ ${8D1}_{16}" /></a>
- b. <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;${1111111010110011001}_{2}&space;\\&space;${7F599}_{16}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;${1111111010110011001}_{2}&space;\\&space;${7F599}_{16}" title="${1111111010110011001}_{2} \\ ${7F599}_{16}" /></a>
- c. <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;${101011011100011100}_{2}&space;\\&space;${2B71C}_{16}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;${101011011100011100}_{2}&space;\\&space;${2B71C}_{16}" title="${101011011100011100}_{2} \\ ${2B71C}_{16}" /></a>

## (5 pts) Wakerly, Problem 2.5 (a)-(f)
Convert the following numbers into decimal:
- a. <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;${93}_{10}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;${93}_{10}" title="${93}_{10}" /></a>
- b. <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;${62990}_{10}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;${62990}_{10}" title="${62990}_{10}" /></a>
- c. <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;${177}_{10}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;${177}_{10}" title="${177}_{10}" /></a>
- d. <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;${54.359375}_{10}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;${54.359375}_{10}" title="${54.359375}_{10}" /></a>
- e. <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;${21.5625}_{10}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;${21.5625}_{10}" title="${21.5625}_{10}" /></a>
- f. <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;${64694}_{10}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;${64694}_{10}" title="${64694}_{10}" /></a>

## (5 pts) Wakerly, Problem 2.7 (a)-(b)
Add the following pairs of binary numbers, showing all carries:
- a.  
<a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;\begin{matrix}&space;&&space;110011&space;\\&space;&plus;&space;&&space;011001&space;\\&space;=&space;&&space;1001100&space;\end{matrix}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;\begin{matrix}&space;&&space;110011&space;\\&space;&plus;&space;&&space;011001&space;\\&space;=&space;&&space;1001100&space;\end{matrix}" title="\begin{matrix} & 110011 \\ + & 011001 \\ = & 1001100 \end{matrix}" /></a>
- b.  
<a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;\begin{matrix}&space;&&space;101110&space;\\&space;&plus;&space;&&space;100101&space;\\&space;=&space;&&space;1010011&space;\end{matrix}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;\begin{matrix}&space;&&space;101110&space;\\&space;&plus;&space;&&space;100101&space;\\&space;=&space;&&space;1010011&space;\end{matrix}" title="\begin{matrix} & 101110 \\ + & 100101 \\ = & 1010011 \end{matrix}" /></a>

## (5 pts) Wakerly, Problem 2.9 (a)-(b)
Add the following pairs of octal numbers:
- a.  
<a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;\begin{matrix}&space;&&space;1362&space;\\&space;&plus;&space;&&space;4231&space;\\&space;=&space;&&space;5613&space;\end{matrix}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;\begin{matrix}&space;&&space;1362&space;\\&space;&plus;&space;&&space;4231&space;\\&space;=&space;&&space;5613&space;\end{matrix}" title="\begin{matrix} & 1362 \\ + & 4231 \\ = & 5613 \end{matrix}" /></a>
- b.  
<a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;\begin{matrix}&space;&&space;47135&space;\\&space;&plus;&space;&&space;05145&space;\\&space;=&space;&&space;54302&space;\end{matrix}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;\begin{matrix}&space;&&space;47135&space;\\&space;&plus;&space;&&space;05145&space;\\&space;=&space;&&space;54302&space;\end{matrix}" title="\begin{matrix} & 47135 \\ + & 05145 \\ = & 54302 \end{matrix}" /></a>

## (5 pts)
Convert the following decimal numbers to binary numbers using the divide-by-2
method:
- a. 19

19/2 = 1
8/2 = 1
4/2 = 0
2/2 = 0
2/1 = 1
10011

- b. 30

30/2 = 0
15/2 = 1
7/2 = 1
3/2 = 1
1/2 = 1
11110

## (5 pts)
Convert the decimal number 128 to the following number systems:
<a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;{10000000}_{2}&space;\\&space;{80}_{16}&space;\\&space;{11202}_{3}&space;\\&space;{1003}_{5}&space;\\&space;{88}_{15}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;{10000000}_{2}&space;\\&space;{80}_{16}&space;\\&space;{11202}_{3}&space;\\&space;{1003}_{5}&space;\\&space;{88}_{15}" title="{10000000}_{2} \\ {80}_{16} \\ {11202}_{3} \\ {1003}_{5} \\ {88}_{15}" /></a>
