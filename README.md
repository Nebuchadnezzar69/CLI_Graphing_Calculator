# CLI_Graphing_Calculator
A graphing calculator design for text based command line interface

Newest Draft
XXXXXOXXXXX
XXXXXOXXXXX
OOO00+00O0O
XXXXXOXXXXX
XXXXXOXXXXX

Program will check the locations of each coorsinate point based on an odd number of dimensions of the grid
if its not odd, It will be requested to be odd.

example 
user: Give me x^2 on a 7x13 grid (Tall and Wide respectively)

there will be 7 lists made

     For each list
          find the Wide elements that will be made, all filled with X or some filler
          Use the median finding algorithm to find the middle number
          use that median number to change that number element in all the lists to 0
      
      An algorithm will find the number (Tall) that splits it in the middle (in this case 4) and designated that as the X-axis, which means
          It changes all its contents to Zero
          It finds the number of elements in the list and uses the odd algorithm to find the median number.
          It changes that number element to a plus sign, which is the origin
Every element in the list corresponds to a coordinate
I need to read each list from left to right, starting from the first one.
I read the first list. 
Given Wide and Tall, I create WideCoord and TallCoord lists
Read Coordinate from WideCoord and TallCoord and fill element in 
(Figure out an algorithm to figure out what the first coordinate pair is given the previous process and the use of Wide and Tall as variables)
Algorithm returns first coordinate pair
Test Coordinate pair, is it in X^2?
If so,	
	Put an Asterisk or filler in place of the first or     next element.
If not,
	Leave the x, and move on to the next element
Keep doing this until you've reached the end of the list, then stop and do the same for each list until all of the display lists are filled.
Print each list in its own line to display the graph.
