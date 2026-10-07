# MAT133 Lecture 11 (Oct 2)

Source: `MAT133/Lecture Notes/MAT133 Lecture 11 (Oct 2).pdf` (14 pages)

--- Page 1 ---
MAT133 Calculus and Linear Algebra for Commerce Oct 2, 2026
Lecture 11 Marginal Cost and Revenue,
Focus on Theory: Limits and Derivatives
Big Questions
•Can we relate the derivative to the concepts of marginal cost and
revenue from economics?
•Can we find a more concise way of expressing the definition of the
derivative?
•What is a limit?
--- Page 2 ---
Warm up: The Cost of Producing Pendants
Graphed below is the cost function for producing amethyst pendants.
$
q(thousands)
10,000
20,000
1 2 3 4 5
C(q)
Poll Question
(a) Does it cost more to produce the A 500th or B 2000th pendant?
Note.The cost of producing the 500th pendant (i.e.pendant #500), is
not the cost of producing the first 500 pendants.
(b) At roughly which production levelq(in thousands) is the marginal cost
minimized? A 0 B 1 C 2 D 3.5
2
--- Page 3 ---
Profit when Producing Telephones
To produceqtelephones, a manufacturer’s cost isC(q). To sellqtele-
phones, the revenue isR(q). Suppose that:
C(300) = 5200,
C′(300) = 13,
R(300) = 8400,
R′(300) = 8.
Discussion Question
How muchprofitdoes the company make by selling 300 telephones?
Estimatethe company’s profit when producing
q= 301,299,310,and 290 telephones.
Poll Question
The company is currently producing and selling 300 telephones. In order to
generate more profit, they should...
A increase B decrease C not change
their sales. Assume they sell everything they produce. 3
--- Page 4 ---
Marginal cost, revenue and profit
Definition
Suppose that cost, revenue and profit of producingqunits of a good are
respectively:
C(q),R(q), π(q).
•Themarginal cost(MC) is defined by: .
•Themarginal revenue(MR) is defined by: .
•Similarly, themarginal profit(MP) is defined by: .
•The three quantities are related via:
4
--- Page 5 ---
Velocity of a Football
Suppose that a football kick is filmed. The ball crosses the half-way line
1 second after being kicked, and the distanced=g(t) in meters of the
ball from the half-way line is recorded in the table below as a function of
timetin seconds.
t 1 1.2 1.4 1.6 1.8 2 2.2
d 0.0 6.0 11.8 17.5 22.7 27.5 32.3
Discussion Question
Explain how we can make approximations of the ball’s velocity as it crosses
the half-way line that successively become more and more accurate.
5
--- Page 6 ---
Visualizing the Approximations
Our method is to take thelimitof the of
gover shorter and shorter intervals with 1 as an end point (i.e.intervals
containing 1).
1 1 +h
d=g(t)
secant line
∆t=h
∆d
t
d
1 1 +h
d=g(t)
secant line
∆t
∆d
t
d
We can express this idea more concisely usinglimit notation:
g′(1) =
6
--- Page 7 ---
More Generally
Suppose thaty=g(x) is any function. Then we can expressg ′(a) as a
limitof average rates of change:
a a+h
y=g(x)
secant line
∆x=h
∆y
x
y
a a+h
y=g(x)
secant line
∆x
∆y
x
y
Usinglimit notation:
g′(a) =
7
--- Page 8 ---
What is a limit?
Definition
We say thatf(x)has limitLasxapproachesaand write
lim
x→a
f(x) =L
provided that we can makef(x) as close toLas we like, by takingx
sufficiently close (but not equal) toa.
Iff(x) does not approach a single value asxapproachesa, then we say that
lim
x→a
f(x)doesn’t exist.
Poll Question
The graph of a functiony=f(x) is on the
right. Appealing to the above definition, does
fhave a limit asxapproaches 2? Explain.
A Yes B No C We can’t tell
y
x0
50
2
8
--- Page 9 ---
A Limit
Please set your calculator to radians mode (for instance, 360°becomes 2π).
Discussion Question
What isL= lim
x→0
sin(5x)
x (if it exists)?
To investigate, please use your calculator to fill in the table below.
x −0.1 −0.01 −0.001 0 0.001 0.01 0.1
sin(5x)
x
•Based on this data, we expect that lim
x→0
sin(5x)
x = if it exists.
After Class
Investigate the limit using Desmos.
9
--- Page 10 ---
Limits, limits, limits
Below is the graph ofy=g(x).
x
y
2
-8
1-1
Discussion Question
What are the following limits
(if they exist)? Explain using
the definition of a limit.
(a) lim
x→−2
g(x) =
(b) lim
x→0
g(x) =
(c) lim
x→2
g(x) =
(d) lim
x→4
g(x) =
10
--- Page 11 ---
Limit Definition of the Derivative
Definition
If the limit exists,the derivativef ′(a) of a functiony=f(x) at a point
x=ais the limit:
f′(a) = lim
h→0
f(a+h)−f(a)
h .
x
y
-4 -3 -2 -1 0 1 2 3 4
1
2
3
4
y=f(x) Discussion Question
Using the limit definition,
discuss how to find the following
derivatives, if they exist:
(a)f ′(2) =
(b)f ′(−1) =
(c)f ′(0) =
11
--- Page 12 ---
To Do
To do before next class:
•Complete Week 3 Checkpoint Workbook!
•Read the Focus on Theory section at the end of Chapter 2.
•Complete Homework 3.
•Week 3 Reflection Journal
•Work on the first draft of your Pod Project Report (due Tuesday,
Oct 6).
Have a great day!
12
--- Page 13 ---
Motivation for next time: Bike Share Toronto
If you have an annual membership with Bike Share Toronto, bike trips of
up to 30 minutes are free. However, if your trip lasts for longer than 30
minutes and up to an hour, a fee of$4 will be charged. If your trip lasts
for longer than 60 minutes and up to 90 minutes, you’ll be charged$8.
This pattern continues for each 30 minutes, up to 3 hours.
Discussion Question
Graph the fees as a functionfof trip time on the grid below.
0 30 60 90 120 150 180
0
4
8
12
16
20
Trip Time (min)
Fee ($)
What do you notice?
13
--- Page 14 ---
Continuity
Definition
The functionfiscontinuousatx=ciffis defined atx=cand
lim
x→c
f(x) =f(c).
A function is continuous on an interval (a,b) if it is continuous at every point
in the interval.
Discussion Question
The graph offis to the right.
At what points isfcontinuous?
x
y
2
-8
1-1
14