# MAT133 Lecture 08 (Sep 25)

Source: `MAT133/Lecture Notes/MAT133 Lecture 08 (Sep 25).pdf` (13 pages)

--- Page 1 ---
Warm up: Geometric properties of the derivative
Consider the function whose
graph is shown below.
1 2 3 4
−1
1
2
3
y=f(x)
x
y
Poll Question
Which of the following shows the
graph ofy=f ′(x)?
A
1 2 3 4
−2
2
x
y
B
1 2 3 4
−4
−2
2
xy
C
1 2 3 4
−2
−1
xy
1
--- Page 2 ---
MAT133 Calculus and Linear Algebra for Commerce Sep 25, 2026
Lecture 8 Interpretations of the Derivative
Big Questions
•How are units important in interpreting derivatives?
•How can we estimate the value of a function based on limited data?
•Ifxchanges “just a little bit”, how much willf(x) change?
--- Page 3 ---
Warm up: Geometric properties of the derivative
Consider the function whose
graph is shown below.
1 2 3 4
−1
1
2
3
y=f(x)
x
y
Poll Question
Which of the following shows the
graph ofy=f ′(x)?
A
1 2 3 4
−2
2
x
y
B
1 2 3 4
−4
−2
2
xy
C
1 2 3 4
−2
−1
xy
3
--- Page 4 ---
Interpretation and Units of the Derivative
Poll Question
LetCbe the cost in dollars required for producingqlitres of cold brew coffee.
Here,C=f(q).
(i) What are theunitsoff ′(2000)?
A litres B $/litre C $/day D litres/day
(ii) In non-technical terms, what is the meaning off ′(2000) = 4.5?
4
--- Page 5 ---
Leibniz Notation for the Derivative
In the last example,C=f(q).
Sincef ′(q)≈ , we writef ′(q) = .
This notation helps us remember the meaning of the derivative, as well as
its units. To specify the derivative at a point in this notation, we use a
vertical line:
f ′(2000) =
Discussion Question
LetFbe the amount of fuel Mr. Bean has used after drivingxkilometres,t
hours since he left home. Express the following using Leibniz notation:
(a) Mr. Bean’s car is using fuel at
a constant rate of 8 L/km.
(b) Two hours after he left home, he
was traveling at a speed of 100 km/h.
5
--- Page 6 ---
Mr. Bean
Mr. Bean drives erratically, often speeding up
and slowing down, but always driving down a
straight road in one direction. We know that1
hour after leaving home, he has travelled 70
km and his current speed is 36 km/h.
Discussion Question
(a) About how far is he from home 1.1h after leaving?
(b) If Mr. Bean’s distance from homex(in km) as a function of timet(in h)
is given byx=f(t), express his speed of 36 km/h in both prime and
Leibniz notation.
(c) Summarize the calculation you did in (a) using function notation.
6
--- Page 7 ---
Illustrating Our Solution
Below, we have started a (zoomed-in)distance-time graphfor Mr. Bean.
Time (hr)
x
Distance
(km)70
0.9 1 1.1
A
B
C
Poll Question
Which of the three pointsA,B,Ccould represent the estimate we made for
how far from home Mr. Bean is after 1.1h? Why?
A A B B C C D None are possible.
Conclusion:Our estimate lies on the to
the graph at . 7
--- Page 8 ---
Estimates more generally
a x
y=f(x)
tangent line
∆x
y
Poll Question
Suppose we only know the values off(a) andf ′(a) and thatxis close toa.
(a) Which of the following is approximately equal tof(x)−f(a)?
A f ′(a) B f ′(a)x C f ′(a)(x−a) D None
(b) Find an estimate forf(x) expressed in terms ofa,x,f(a) andf ′(a).
f(x)≈
8
--- Page 9 ---
Tangent Line Approximation: Local Linearity
a x
y=f(x)
tangent line
∆x
y
Definition
Suppose that we knowf(a) andf ′(a). As long as ∆x=x−aissmall, to
estimatef(x) we can use:
This is known as thetangent line approximation.
9
--- Page 10 ---
Tangent Line Approximation: Local Linearity
Suppose that the costy=f(x), in thou-
sands of dollars, of manufacturingxkilo-
grams of ibuprofen is shown on the right.
0 1 2 3 4 50
1
2
3
4
x(kg)
y(thousand$)
Poll Question
(a) It is known thatf(1) = 2.6 andf ′(1) = 0.6. Estimate the cost of
producing 1.15 kg of ibuprofen.
(b) Is your estimate an A overestimate or B underestimate? Why?
10
--- Page 11 ---
To Do
To do before next week:
•Please read Section 2.3.
•Finish the Week 2 Checkpoint Workbook.
•Finish Homework 2.
•The Week 2 Reflection Journal is due next Tuesday.
•Theindividual partandpod contractfor Project 1 are due next
Tuesday.
Have a great day!
11
--- Page 12 ---
Example: Rabbits
The populationPof a species of rabbits as a function of timetin years
since Jan 1, 2020 is shown in the table below.
Timet(years) 0 0.25 0.5 0.75 1
PopulationP 100 110 121 133 146
Poll Question
The rate of change dP
dt is approximately constant, becausePalways grows by
about 10% over each quarter year.
A True B False
12
--- Page 13 ---
Relative Rate of Change
Definition
LetQ=f(t). Therelative rate of changeofQwith respect tot, att=a
is defined as
Example 1
The area of Brazil’s rainforestR=f(t), in million acres, is a function of the
number of yearstsince 2000. Accordingwww.rain-tree.com,f(9) = 740
andf ′(9) =−2.7. Find and interpret the relative rate of change off(t) when
t= 9.
13