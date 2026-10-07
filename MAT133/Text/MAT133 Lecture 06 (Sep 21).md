# MAT133 Lecture 06 (Sep 21)

Source: `MAT133/Lecture Notes/MAT133 Lecture 06 (Sep 21).pdf` (16 pages)

--- Page 1 ---
LEC 0601: Find your pod
Front Screens
TUT 0601
TUT 0602
TUT 0605
TUT 0701
TUT 0702
TUT 1301
TUT 1302
TUT 1303
TUT 1304
1
--- Page 2 ---
MAT133 Calculus and Linear Algebra for Commerce Sep 21, 2026
Lecture 6 Instantaneous Rate of Change
Big Question
•How can we describe a rate of change in a single instant?
--- Page 3 ---
Warm-up: Safe Road Design
Driving speed is an important factor in road safety. It affects the severity
of a crash and is also related to the risk of being involved in a crash.
You’ve been tasked to study a particular common crash site on a road to
find how speed relates to risk of crashes. You have video footage showing
cars driving through the crash site and the 100 metres leading up to it.
0 100distance (m)
Site
Discussion Question
Using nothing but this video footage, how might you estimate the speed of
each car at the crash site? (Assume you have no odometers, sensors, or AI to
help you!)
3
--- Page 4 ---
Safe Road Design
One Possible method:In the video, label the location that’s 100 metres
before the crash site. Measure the time it takes for the car to travel those
100 metres. Use this information.
Poll Question
If the car takes 5 seconds to travel these 100 metres, what can you say about
the car’s speedexactlyas it passes through the crash site? (This car doesn’t
crash.)
A >20 m/s
B <20 m/s
C = 20 m/s
D I don’t know.
Discussion Question
Can you suggest an improvement on the method described?
4
--- Page 5 ---
Safe Road Design
Improve the precision:Let’s use the video to collect data at more times,
especially closer to timet= 5 seconds.
Timet(s) 0 4 4.9 4.99 4.999 5 5.001 5.01 5.1 6
Distancex(m) 0 64 96.04 99.6 99.95 100 100.04 100.4 104.4 144
Discussion Question
How can we use this data to improve our estimate for the speed of the car at
timet= 5 seconds? Come up with at least two methods. Using a method
discussed by your group, find an estimate.
5
--- Page 6 ---
Instantaneous velocity
We can use our idea from the previous slide todefineinstantaneous velocity.
Definition
Theinstantaneous velocityof an object at timetis defined to be thelimit
of the of the object over shorter
and shorter time intervals containingt.
6
--- Page 7 ---
Instantaneous velocity using the graph
Let’s suppose that we can also use the video to plot a graph of the car’s
position as a function of time, shown in the Desmos graph linked below.
https://www.desmos.com/calculator/e84ktt0goy
Discussion Question
(a) Adjust the positions of the two points so that the slope of the secant line
represents the average velocity over the first 5s. (The average velocity is
min the left panel.)
(b) Make further adjustments to the graph to more accurately estimate the
velocity of the car exactly att= 5s.
7
--- Page 8 ---
Why do we care about velocity?
Why velocity?
•We will often seek to apply calculus to commerce and social
sciences in this course!
•However, physical motion is easier for us to conceptualize, as
humans.
•We’ll often use physical metaphors as we think about other
applications.
8
--- Page 9 ---
Instantaneous Rates of Change
More generally, we can define an instantaneous rate of change for any function,
even if it doesn’t represent the position of an object.
Definition
Theinstantaneous rate of changeof a functionfata, is defined to be the
limit of the offover shorter and
shorter intervals containinga.
We denote the instantaneous rate of change offataby .
9
--- Page 10 ---
Limiting secant lines geometrically
Geometrically:We can sketch a secant line through the points (a,f(a)) and
(b,f(b)). As we takebcloser and closer toa, the slope of the secant line will
approachf ′(a).
a b
y=f(x)
secant line
∆x
∆y
x
y
a b
y=f(x)
secant line
∆x
∆y
x
y
a b
y=f(x)
secant line
∆x
∆y
x
y
Here, ∆x=b−aand ∆y=f(b)−f(a).
Note:We could also use two points on either side of (a,f(a)). 10
--- Page 11 ---
Limiting secant lines geometrically
Geometrically:As the two points get closer and closer to (a,f(a)), the secant
line looks more and more like the linetangentto the graph offatx=a.
a
y=f(x)
Line tangent
tof(x) atx=a
x
y
The instantaneous rate of change offatais equal to the slope of the
tangent lineatx=a.
11
--- Page 12 ---
Estimating the slope of a tangent line at a point
The graph of a functiony=f(x) is shown below.
1 2 3
1
2
y=f(x)
x
y
Poll Question
Without doing any calculations, rank the following numbers from least to
greatest.
f ′(1),f ′(2),f ′(3)
Which one is smallest? A f ′(1) B f ′(2) C f ′(3)
12
--- Page 13 ---
Estimating the slope of a tangent line at a point
1 2 3
1
2
y= ln(x)
x
y The graph off(x) = ln(x) is shown
on the left.
https://www.desmos.com/calculator/dwyvr6nc67
Discussion Question
Use the graphto estimate the value off ′(1). How could you make your
estimate more accurate?
After Class
Approximate the values off ′(1),f ′(2) andf ′(3).
13
--- Page 14 ---
Summary: Approximating Instantaneous Rates of Change
Discussion Question
For each representation of a function, what methods do we have to
approximate instantaneous rates of change?
Tables Graphs
Formulas Words
14
--- Page 15 ---
To Do
To do before next class:
•Try questions 1-3 from the Week 2 Checkpoint Workbook.
•Please read section 2.1 carefully and do problems 1-10 from HW 2
(available on WileyPlus and due on Tuesday Sep 29 at 10pm)
•Drop-in study hours have started and the Math Learning Centre is open.
•Got questions? The Piazza discussion board is now up and running.
Have a great day!
15
--- Page 16 ---
For the Curious
Below is the graph ofy=
√
x 2 +x 4.
https://www.desmos.com/calculator/ax1b8we9rj
−3 −2 −1 1 2 3
−1
1
2
3
y=
√
x 2 +x 4
x
y
After Class
Use Desmos to Zoom in to the graph at the point withx= 0. What do you
notice?
16