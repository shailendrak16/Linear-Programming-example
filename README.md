# Linear-Programming-example

Overview
The primary OR-Tools linear optimization solver is Glop, Google's linear programming system. 
It's fast, memory efficient, and numerically stable. The next section shows how to use Glop to solve a simple linear problem in all of the supported languages.


A simple example
Here's a simple example of a linear programming problem.

Maximize 3x + 4y subject to the following constraints:

x + 2y	≤	14

3x – y	≥	0

x – y	≤	2

Both the objective function, 3x + 4y, and the constraints are given by linear expressions, which makes this a linear problem.

The constraints define the feasible region, which is the triangle shown below, including its interior.


The following sections explain how to solve the problem.

