## Section 6.1
<u><font color = "#D2AFFF">Draw the graph represented by the following adjacency matrix</font></u>

![[Pasted image 20230504185329.png | 200]]

![[ExDraw1 - CS1300 Spring 2023 Homework 6 | 200]]

<u><font color = "#D2AFFF">Draw the directed graph represented by the following adjacency list.</font></u>

![[Pasted image 20230504185358.png | 200]]

![[ExDraw2 - CS1300 Spring 2023 Homework 6 | 200]]

## Section 6.2
<u><font color = "#D2AFFF">Write the list of nodes resulting from a preorder traversal, an inorder traversal, and a postorder traversal of the following tree.</font></u>

![[Pasted image 20230504190810.png | 200]]

	Preorder Traversal: a, b, e, h, d, f, c, g
	Inorder Traversal: d, b, e, h, f, a, c, g
	Postorder Traversal:d, f, h, e, b, g, c, a

## Section 8.2

<u><font color = "#D2AFFF">Write a truth function and construct a logic network using AND gates, OR gates, and inverters for each of the following Boolean expressions</font></u>

$x_1'$($x_2$) + ($x_1$ $x_2$)'

![[ExDraw3 - CS1300 Spring 2023 Homework 6 | 400]]

| $x_1$ | ($x_1$)' | $x_2$ | ($x_1$)'($x_2$) | ($x_1$$x_2$) | ($x_1$$x_2$)' | ($x_1$)'($x_2$)+($x_1$$x_2$) |
| ----- | -------- | ----- | --------------- | ------------ | ------------- | ---------------------------- |
| T     | F        | T     | F               | T            | F             | F                            |
| T     | F        | F     | F               | F            | T             | T                            |
| F     | T        | T     | T               | F            | T             | T                            |
| F     | T        | F     | F               | F            | T             | T                            |

<u><font color = "#D2AFFF">Write a Boolean expression and a truth function for the following logic network.</font></u>

![[Pasted image 20230504165457.png | 200]]

( ( $x_1'$ + $x_2$ ) * ($x_3$) )' 

<u><font color = "#D2AFFF">Find the canonical sum-of-products form for the truth functions in the given table</font></u>

![[Pasted image 20230504221950.png | 200]]

$x_1$ $x_2'$ $x_3$ + $x_1$ $x_2'$ $x_3'$ + $x_1'$ $x_2$ $x_3'$ 
