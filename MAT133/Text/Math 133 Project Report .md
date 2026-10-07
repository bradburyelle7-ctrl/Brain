# Math 133 Project Report 

Source: `MAT133/Project 1/Math 133 Project Report .pdf` (11 pages)

--- Page 1 ---
MAT133:
 
Calculus
 
and
 
Linear
 
Algebra
 
for
 
Commerce
 
Project
 
1
 
First
 
Draft
 
Cover
 
Page
 
Student
 
Names
 
and
 
Numbers:
 
1.
  
Dylan
 
Bradbury
 
     
1013401882
 
2.
  
Haofeng
 
Ye
 
     
1010444244
 
3.
  
Juan
 
Gonzalez
 
     
1012268635
 
4.
  
[Insert
 
Name]
 
     
[Student
 
Number]
 
 
What
 
is
 
your
 
pod’s
 
name?
 
B-T-W
 
 
What
 
is
 
your
 
research
 
question?
 
Does
 
Tesla's
 
stock
 
price
 
react
 
faster
 
or
 
slower
 
than
 
its
 
deliveries
 
grow?
 
 
In
 
your
 
data
 
set,
 
what
 
are
 
the
 
input
 
and
 
output
 
variables?
 
State
 
the
 
quantities
 
in
 
words,
 
including
 
units.
 
Input:
 
Time
 
●
 
Measured
 
in
 
months
 
(Stock
 
price)
 
●
 
Measured
 
in
 
quarters
 
(deliveries)
 
Output:
 
Tesla's
 
Stock
 
Price
 
●
 
Measured
 
in
 
USD
 
per
 
share
 
 
Tesla’s
 
Vehicle
 
Deliveries
 
●
 
Vehicles
 
delivered
 
per
 
quarter
 
 
 
Our
 
project
 
marking
 
team
 
will
 
provide
 
you
 
with
 
feedback
 
on
 
the
 
format,
 
labels,
 
and
 
readability
 
of
 
your
 
scatterplot.
 
In
 
addition
 
to
 
this,
 
you
 
may
 
request
 
feedback
 
on
 
one
 
other
 
element
 
of
 
your
 
report,
 
by
 
selecting
 
one
 
option
 
below:
 
○
  
Research
 
question
 
○
  
Suitability
 
of
 
Dataset
 
○
  
Interpretations
 
for
 
the
 
rates
 
of
 
change
 
***
 
○
  
Formatting
 
of
 
calculations
 
and
 
mathematical
 
symbols
 
○
  
Citations
 
 
--- Page 2 ---
Math
 
133
 
Project
 
Report
 
 
 
1.
 
Introduction
 
 
 
Research
 
Question
 
Does
 
Tesla’s
 
stock
 
price
 
react
 
faster
 
or
 
slower
 
than
 
its
 
deliveries
 
grow?
 
 
 
Background
 
  
How
 
Tesla
 
shares
 
fell
 
after
 
deliveries
 
dropped
 
8.5%
 
from
 
a
 
year
 
ago
[1]
.
 
Total
 
2024
 
Q1
 
deliveries:
 
386,810
 
compared
 
to
 
Total
 
2023
 
Q1
 
deliveries:
 
422,875.
 
This
 
led
 
to
 
TSLA’s
 
stock
 
price
 
falling
 
by
 
about
 
4.9%
 
on
 
April
 
2,
 
2024.
 
This
 
delivery
 
decline
 
was
 
due
 
to
 
production
 
disruptions,
 
shipping
 
disruptions
 
caused
 
by
 
the
 
Red
 
Sea
 
conflict,
 
and
 
an
 
arson
 
attack
 
that
 
caused
 
the
 
Berlin
 
factory
 
to
 
be
 
shut
 
down.
 
Weaker
 
demand
 
and
 
increasing
 
competition
 
from
 
Chinese
 
EV
 
companies,
 
were
 
both
 
major
 
factors
 
as
 
well.
 
 
 
 
The
 
Data
 
Set
 
  
Two
 
datasets
 
are
 
used
 
to
 
compare
 
how
 
Tesla’s
 
stock
 
price
 
reacts
 
with
 
its
 
vehicle
 
deliveries
 
from
 
January
 
2023
 
to
 
December
 
2025.
 
The
 
first
 
dataset
 
contains
 
TSLA’s
 
monthly
 
closing
 
stock
 
prices,
 
measured
 
in
 
USD
 
per
 
share,
 
using
 
the
 
closing
 
price
 
of
 
the
 
asset
 
on
 
the
 
last
 
trading
 
day
 
of
 
each
 
month.
 
The
 
second
 
dataset
 
contains
 
the
 
number
 
of
 
vehicles
 
Tesla
 
delivered
 
to
 
customers
 
worldwide
 
during
 
each
 
quarter,
 
measured
 
in
 
vehicles
 
delivered
 
per
 
quarter.
 
Table
 
1
 
shows
 
the
 
first
 
ten
 
months
 
of
 
the
 
monthly
 
stock
 
price
 
data,
 
while
 
table
 
2
 
shows
 
the
 
first
 
ten
 
quarters
 
of
 
the
 
quarterly
 
vehicle
 
deliveries
 
data.
 
 
 
  
The
 
input
 
variable
 
for
 
both
 
datasets
 
is
 
time.
 
For
 
the
 
stock
 
price
 
data,
 
time
 
is
 
measured
 
in
 
months
 
starting
 
from
 
January
 
2023.
 
For
 
the
 
quarterly
 
deliveries
 
data,
 
time
 
is
 
measured
 
in
 
quarters
 
starting
 
from
 
Q1
 
in
 
2023.
 
The
 
output
 
variables
 
are
 
Tesla’s
 
monthly
 
closing
 
stock
 
price,
 
measured
 
in
 
USD.
 
And
 
Tesla’s
 
quarterly
 
vehicle
 
deliveries,
 
measured
 
in
 
total
 
vehicles
 
delivered
 
to
 
customers
 
each
 
quarter.
 
Yahoo
 
finance
[2]
 
is
 
used
 
to
 
obtain
 
the
 
stock
 
price
 
data
 
which
 
records
 
historical
 
market
 
prices
 
and
 
also
 
Tesla’s
 
Investor
 
Relations
 
reports
[3]
,
 
where
 
Tesla
 
publishes
 
its
 
quarterly
 
production
 
and
 
delivery
 
results.
 
 
 
  
These
 
two
 
datasets
 
allow
 
us
 
to
 
directly
 
compare
 
what
 
investors
 
are
 
willing
 
to
 
pay
 
for
 
a
 
TSLA
 
share
 
compared
 
to
 
what
 
the
 
company
 
is
 
actually
 
delivering
 
to
 
customers.
 
I
 
chose
 
the
 
2023-2025
 
period
 
because
 
it
 
includes
 
several
 
significant
 
changes
 
in
 
both
 
datasets,
 
including
 
large
 
increases
 
and
 
decreases
 
in
 
stock
 
price
 
and
 
quarterly
 
deliveries.
 
 
 
--- Page 3 ---
Data
 
set
 
Source
 
Coverage
 
and
 
notes
 
TSLA
 
monthly
 
closing
 
prices
 
Yahoo
 
Finance
 
—
 
TSLA
 
Historical
 
Data
 
Jan
 
2023-Dec
 
2025.
 
Closing
 
prices
 
are
 
split-adjusted;
 
values
 
shown
 
in
 
USD.
 
Tesla
 
quarterly
 
deliveries
 
Tesla
 
Investor
 
Relations
 
Q1
 
2023-Q4
 
2025.
 
Total
 
vehicle
 
deliveries,
 
not
 
production.
 
 
 
Table
 
1
 
TSLA
 
Monthly
 
Closing
 
Price,
 
January–September
 
2023
 
Month
 
Date
 
Closing
 
price
 
($)
 
1
 
Jan
 
2023
 
173.22
 
2
 
Feb
 
2023
 
205.71
 
3
 
Mar
 
2023
 
207.46
 
4
 
Apr
 
2023
 
164.31
 
5
 
May
 
2023
 
203.93
 
6
 
Jun
 
2023
 
261.77
 
7
 
Jul
 
2023
 
267.43
 
8
 
Aug
 
2023
 
258.08
 
9
 
Sep
 
2023
 
250.22
 
10
 
Oct
 
2023
 
200.07
 
 
 
Table
 
2
 
Tesla
 
Quarterly
 
Vehicle
 
Deliveries,
 
Q1
 
2023–Q2
 
2025
 
Quarter
 
Period
 
Deliveries
 
(number
 
of
 
vehicles)
 
1
 
Q1
 
2023
 
422,875
 
2
 
Q2
 
2023
 
466,140
 
3
 
Q3
 
2023
 
435,059
 
4
 
Q4
 
2023
 
484,507
 
--- Page 4 ---
5
 
Q1
 
2024
 
386,810
 
6
 
Q2
 
2024
 
443,956
 
7
 
Q3
 
2024
 
462,890
 
8
 
Q4
 
2024
 
495,570
 
9
 
Q1
 
2025
 
336,681
 
10
 
Q2
 
2025
 
384,122
 
 
 
2.
 
Visual
 
Representation
 
of
 
the
 
Data
 
  
Figure
 
1
 
representing
 
Tesla’s
 
monthly
 
closing
 
prices
 
shows
 
a
 
clear
 
uptrend
 
but
 
highly
 
choppy
 
trend
 
within
 
the
 
time
 
period.
 
The
 
largest
 
early
 
increase
 
occurs
 
between
 
months
 
4
 
and
 
6,
 
where
 
the
 
price
 
rose
 
from
 
$164.31
 
to
 
$261.77,
 
almost
 
a
 
$100
 
increase,
 
followed
 
by
 
a
 
noticeable
 
decline
 
from
 
month
 
9
 
to
 
10
 
of
 
around
 
$50.
 
The
 
most
 
meaningful
 
increase
 
occurs
 
between
 
months
 
20
 
to
 
24
 
where
 
price
 
rose
 
from
 
$214.11
 
to
 
$403.84,
 
although
 
a
 
large
 
drop
 
occurs
 
directly
 
after
 
during
 
months
 
25
 
to
 
27.
 
Again
 
there
 
is
 
another
 
massive
 
movement
 
upwards
 
in
 
price
 
from
 
months
 
32
 
to
 
33,
 
before
 
settling
 
at
 
that
 
price
 
level.
 
During
 
specific
 
periods
 
I
 
mentioned,
 
the
 
steep
 
rises
 
suggest
 
that
 
the
 
stock
 
price
 
was
 
moving
 
more
 
quickly
 
than
 
quarterly
 
deliberations,
 
which
 
may
 
indicate
 
that
 
there
 
were
 
other
 
factors
 
in
 
investors'
 
expectations
 
during
 
those
 
times.
 
 
 

--- Page 5 ---
 
 
Figure
 
1:
 
Scatterplot
 
of
 
TSLA
 
Monthly
 
Closing
 
Price
 
 
 
  
Figure
 
2
 
representing
 
Tesla’s
 
quarterly
 
deliveries
 
shows
 
a
 
more
 
choppy
 
pattern
 
with
 
no
 
clear
 
overall
 
upward
 
or
 
downward
 
trend.
 
Deliveries
 
rose
 
from
 
423,000
 
to
 
466,000
 
in
 
quarter
 
3,
 
fell
 
slightly
 
in
 
quarter
 
3,
 
and
 
then
 
increased
 
to
 
about
 
485,000
 
in
 
quarter
 
4.
 
The
 
largest
 
declines
 
occur
 
at
 
quarter
 
5,
 
when
 
deliveries
 
fell
 
to
 
roughly
 
387,000
 
and
 
during
 
quarter
 
9,
 
when
 
they
 
dropped
 
from
 
495,000
 
to
 
336,000.
 
In
 
between
 
those
 
quarters
 
there
 
was
 
a
 
steady
 
increase
 
in
 
overall
 
deliveries.
 
Deliveries
 
then
 
rapidly
 
increased
 
during
 
quarter
 
11,
 
reaching
 
nearly
 
497,000
 
vehicles,
 
followed
 
by
 
a
 
pullback
 
to
 
418,000.
 
The
 
steep
 
increase
 
from
 
quarter
 
9
 
to
 
11
 
shows
 
that
 
the
 
rate
 
of
 
change
 
in
 
deliveries
 
was
 
much
 
faster
 
during
 
this
 
period
 
than
 
during
 
any
 
other
 
point
 
in
 
time
 
from
 
2023-2025.
 
Compared
 
with
 
the
 
stock
 
price
 
graph,
 
the
 
delivery
 
data
 
has
 
no
 
obvious
 
upward
 
trend,
 
which
 
suggests
 
Tesla's
 
stock
 
price
 
was
 
reacting
 
to
 
external
 
factors
 
beyond
 
its
 
current
 
vehicle
 
delivery
 
performance.
 
 
 
 
 
 
 
Figure
 
2:
 
Scatterplot
 
of
 
Tesla
 
Quarterly
 
Deliveries
 
 
  
Overall,
 
the
 
two
 
graphs
 
demonstrate
 
that
 
the
 
largest
 
movements
 
in
 
stock
 
price
 
and
 
vehicle
 
deliveries
 
don’t
 
always
 
occur
 
at
 
the
 
same
 
time.
 
This
 
difference
 
supports
 
my
 
research
 
question
 
because
 
it
 
suggests
 
that
 
the
 
stock
 
price
 
may
 
be
 
changing
 
due
 
to
 
external
 
factors
 
or
 
future
 
projection
 
rather
 
than
 
only
 
deliveries
 
data.
 
 
 
 
 
 
 
 

--- Page 6 ---
3.
 
Rates
 
of
 
Change
 
and
 
Discussion
 
 
 
Average
 
Rate
 
of
 
Change
 
  
To
 
calculate
 
the
 
average
 
rate
 
of
 
change
 
clearly,
 
I
 
will
 
use
 
the
 
entire
 
three
 
year
 
period
 
from
 
January
 
2023,
 
to
 
December
 
2025.
 
 
 
  
For
 
Tesla’s
 
stock
 
price,
 
the
 
average
 
rate
 
of
 
change
 
is
 
calculated
 
using
 
the
 
beginning
 
and
 
ending
 
prices.
 
 
 
(449.7
2
 
-
 
173.22)/(36-1)
 
=
 
$7.90
 
dollars/month
 
  
Tesla’s
 
stock
 
price
 
rose
 
by
 
an
 
average
 
rate
 
of
 
about
 
$7.90
 
per
 
month
 
over
 
the
 
2023
 
to
 
2025
 
period.
 
 
 
  
For
 
vehicle
 
deliveries,
 
the
 
average
 
rate
 
of
 
change
 
is:
 
(418227
 
-
 
422875)/(12-1)
 
=
 
-422.55
 
vehicles/quarter
 
 
  
Deliveries
 
decreased
 
by
 
an
 
average
 
rate
 
of
 
about
 
423
 
vehicles
 
per
 
quarter
 
over
 
the
 
same
 
period.
 
 
 
  
These
 
averages
 
show
 
that
 
while
 
price
 
increased
 
at
 
a
 
rather
 
steady
 
rate,
 
deliveries
 
were
 
nearly
 
flat
 
to
 
slightly
 
negative,
 
but
 
both
 
these
 
averages
 
hide
 
the
 
large
 
increases
 
and
 
decreases
 
that
 
occurred
 
within
 
the
 
3
 
year
 
time
 
span.
 
 
 
 
Instantaneous
 
Rate
 
of
 
Change
 
  
To
 
estimate
 
the
 
instantaneous
 
rate
 
of
 
change,
 
I
 
chose
 
to
 
use
 
April
 
2024
 
as
 
the
 
specific
 
point
 
because
 
it
 
falls
 
within
 
the
 
Q1
 
2024
 
period
 
discussed
 
in
 
the
 
CNBC
 
article.
  
 
For
 
Tesla’s
 
Stock
 
price,
 
the
 
instantaneous
 
rate
 
of
 
change
 
is:
 
 
 
(178.08
 
-
 
183.28)/1
 
=
 
-5.20
 
dollars/month
 
 
  
At
 
month
 
16
 
(April
 
2024),
 
Tesla’s
 
stock
 
price
 
was
 
falling
 
at
 
about
 
$5.20
 
per
 
month
 
based
 
on
 
the
 
following
 
month’s
 
price.
 
 
 
  
For
 
Tesla’s
 
quarterly
 
deliveries,
 
the
 
instantaneous
 
rate
 
of
 
change
 
is:
 
 
(386810
 
-
 
484507)/1
 
=
 
-97697
 
vehicles/quarter
 
 
 
  
Tesla
 
deliveries
 
fell
 
by
 
97,697
 
vehicles
 
from
 
Q4
 
2023
 
to
 
Q1
 
2024,
 
which
 
directly
 
matches
 
the
 
disappointing
 
Q1
 
result
 
discussed
 
in
 
the
 
article.
 
 
 
 
 
 
--- Page 7 ---
 
 
Relative
 
Rate
 
of
 
Change
 
  
For
 
Tesla’s
 
stock
 
price
 
in
 
April
 
2024,
 
the
 
estimated
 
rate
 
of
 
change
 
was
 
 
(178.08
 
-
 
183.28)/1
 
=
 
-5.20
 
dollars
 
per
 
month,
 
and
 
the
 
April
 
2024
 
stock
 
price
 
was
 
$183.28,
 
so
 
the
 
relative
 
rate
 
was
 
=-5.20/183.28 ×100
 
=
 
-2.84%
 
.
 
This
 
means
 
Tesla’s
 
stock
 
price
 
was
 
decreasing
 
at
 
a
 
rate
 
of
 
about
 
2.84%
 
of
 
its
 
April
 
value
 
per
 
month
 
based
 
on
 
the
 
change
 
to
 
May.
 
 
 
  
For
 
vehicle
 
deliveries,
 
Tesla
 
delivered
 
386,810
 
vehicles
 
in
 
Q1
 
2024
 
compared
 
with
 
484,507
 
in
 
Q4
 
2023,
 
giving
 
a
 
change
 
of
 
(386810
 
-
 
484507)/1
 
=
 
-97697
 
vehicles/quarter
 
Compared
 
with
 
the
 
Q1
 
2024
 
delivery
 
level,
 
the
 
relative
 
rate
 
was
 
-97,697/386,810×100
 
=
 
-25.26%.per
 
quarter,
 
meaning
 
the
 
delivery
 
decline
 
was
 
much
 
larger
 
relative
 
to
 
the
 
number
 
of
 
vehicles
 
being
 
delivered
 
than
 
the
 
stock
 
price
 
decline
 
was
 
relative
 
to
 
the
 
share
 
price.
 
 
 
 
 
 
 
Estimating
 
the
 
Derivative
 
  
The
 
derivative
 
was
 
estimated
 
by
 
calculating
 
the
 
rate
 
of
 
change
 
between
 
each
 
pair
 
of
 
consecutive
 
data
 
points.The
 
approximate
 
rates
 
of
 
change
 
were
 
calculated
 
using
 
difference
 
quotients
 
from
 
the
 
data
 
in
 
tables
 
3
 
and
 
4.
 
For
 
each
 
row,
 
I
 
used
 
the
 
right
 
hand
 
difference
 
by
 
subtracting
 
the
 
current
 
value
 
from
 
the
 
following
 
one
 
and
 
dividing
 
by
 
the
 
change
 
in
 
time.
 
For
 
example,
 
the
 
Tesla
 
stock
 
price
 
increased
 
from
 
$173.22
 
in
 
January
 
2023
 
to
 
$205.71
 
in
 
February
 
2023,
 
giving
 
an
 
approx
 
rate
 
of
 
change
 
of
 
$32.49
 
per
 
month.
 
For
 
the
 
final
 
row,
 
a
 
left
 
hand
 
difference
 
was
 
used
 
because
 
there
 
was
 
no
 
following
 
data
 
point.
 
The
 
same
 
method
 
was
 
used
 
for
 
vehicle
 
deliveries,
 
with
 
the
 
time
 
difference
 
adjusted
 
to
 
three
 
months
 
because
 
deliveries
 
were
 
reported
 
quarterly.
 
Figures
 
3
 
and
 
4
 
were
 
then
 
created
 
using
 
those
 
calculated
 
rates
 
of
 
change,
 
allowing
 
the
 
graphs
 
to
 
show
 
when
 
each
 
function
 
was
 
increasing
 
or
 
decreasing
 
and
 
how
 
rapidly
 
the
 
change
 
was.
 
 
 
 
 
Table
 
3
 
Estimated
 
Rates
 
of
 
Change
 
of
 
TSLA
 
Closing
 
Price,
 
January–September
 
2023
 
Month
 
Date
 
Closing
 
price
 
($)
 
Rate
 
of
 
change
 
($/month)
 
1
 
Jan
 
2023
 
173.22
 
32.49
 
2
 
Feb
 
2023
 
205.71
 
1.75
 
3
 
Mar
 
2023
 
207.46
 
−43.15
 
--- Page 8 ---
4
 
Apr
 
2023
 
164.31
 
39.62
 
5
 
May
 
2023
 
203.93
 
57.84
 
6
 
Jun
 
2023
 
261.77
 
5.66
 
7
 
Jul
 
2023
 
267.43
 
−9.35
 
8
 
Aug
 
2023
 
258.08
 
−7.86
 
9
 
Sep
 
2023
 
250.22
 
−49.38
 
10
 
Oct
 
2023
 
200.07
 
−50.15
 
Note.
 
Each
 
rate
 
is
 
estimated
 
using
 
a
 
right-hand
 
difference:
 
(next
 
period’s
 
value
 
−
 
this
 
period’s
 
value)
 
÷
 
1
 
period.
 
 
 
Table
 
4
 
Estimated
 
Rates
 
of
 
Change
 
of
 
Tesla
 
Quarterly
 
Deliveries,
 
Q1
 
2023–Q2
 
2025
 
Quarter
 
Period
 
Deliveries
 
(vehicles)
 
Rate
 
of
 
change
 
(vehicles/quarter)
 
1
 
Q1
 
2023
 
422,875
 
43,265
 
2
 
Q2
 
2023
 
466,140
 
−31,081
 
3
 
Q3
 
2023
 
435,059
 
49,448
 
4
 
Q4
 
2023
 
484,507
 
−97,697
 
5
 
Q1
 
2024
 
386,810
 
57,146
 
6
 
Q2
 
2024
 
443,956
 
18,934
 
7
 
Q3
 
2024
 
462,890
 
32,680
 
8
 
Q4
 
2024
 
495,570
 
−158,889
 
9
 
Q1
 
2025
 
336,681
 
47,441
 
10
 
Q2
 
2025
 
384,122
 
112,977
 
Note.
 
Each
 
rate
 
is
 
estimated
 
using
 
a
 
right-hand
 
difference:
 
(next
 
period’s
 
value
 
−
 
this
 
period’s
 
value)
 
÷
 
1
 
period.
 
 
 
 
--- Page 9 ---
Figure
 
3
 
shows
 
Tesla’s
 
monthly
 
price
 
rate
 
of
 
change
 
fluctuates.
 
The
 
largest
 
increase
 
occurs
 
around
 
month
 
32
 
at
 
about
 
$110
 
per
 
month,
 
while
 
the
 
largest
 
decrease
 
occurs
 
around
 
month
 
25
 
at
 
about
 
−$110
 
per
 
month.
 
 
 
Figure
 
3:
 
Scatterplot
 
of
 
rate
 
of
 
change
 
of
 
price
 
vs
 
Time
 
in
 
months
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 

--- Page 10 ---
Figure
 
4
 
shows
 
Tesla's
 
quarterly
 
delivery
 
rate
 
of
 
change
 
over
 
time.
 
The
 
largest
 
increase
 
occurs
 
at
 
quarter
 
10
 
at
 
about
 
110,000
 
vehicles
 
per
 
quarter,
 
and
 
the
 
largest
 
decrease
 
occurs
 
at
 
quarter
 
8
 
at
 
about
 
−160,000
 
vehicles
 
per
 
quarter.
 
 
 
 
 
 
 
 
 
 
Figure
 
4:
 
Scatterplot
 
of
 
Rate
 
of
 
change
 
of
 
deliveries
 
vs
 
Time
 
in
 
quarters
 
Discussion
 
The
 
rates
 
of
 
change
 
show
 
that
 
Tesla’s
 
stock
 
price
 
was
 
much
 
more
 
variable
 
than
 
its
 
vehicle
 
deliveries
 
over
 
the
 
period
 
studied.
 
The
 
stock
 
price
 
frequently
 
switches
 
between
 
positive
 
and
 
negative
 
rates,
 
with
 
some
 
large
 
changes
 
such
 
as
 
the
 
increase
 
from
 
May
 
to
 
June
 
2023
 
,
 
as
 
well
 
as
 
the
 
large
 
increase
 
near
 
the
 
end
 
of
 
2024.
 
While
 
vehicle
 
deliveries
 
changed
 
less
 
frequently
 
because
 
they
 
were
 
reported
 
quarterly
 
as
 
opposed
 
to
 
monthly.
 
This
 
is
 
relevant
 
in
 
the
 
real
 
world
 
because
 
a
 
stock
 
price
 
can
 
move
 
quickly
 
due
 
to
 
news
 
and
 
investor
 
expectations,
 
while
 
vehicle
 
deliveries
 
measure
 
actual
 
s
 
over
 
a
 
long
 
period.
 
These
 
factors
 
connect
 
to
 
my
 
research
 
question,
 
“Does
 
Tesla’s
 
stock
 
price
 
react
 
faster
 
or
 
slower
 
than
 
its
 
deliveries
 
growth?”,
 
because
 
the
 
derivative
 
graphs
 
suggest
 
that
 
the
 
stock
 
price
 
is
 
more
 
frequently
 
variable.
 
Overall,
 
the
 
results
 
suggest
 
that
 
Tesla’s
 
stock
 
price
 
is
 
influenced
 
not
 
only
 
by
 
its
 
current
 
deliveries,
 
but
 
many
 
external
 
factors,
 
such
 
as
 
investors’
 
expectations
 
regarding
 
the
 
future
 
of
 
Tesla.
 
 
 
 
 
 

--- Page 11 ---
4.
 
Conclusion
 
 
 
Summary
 
of
 
Findings
 
 
Overall,
 
the
 
results
 
show
 
that
 
Tesla’s
 
stock
 
price
 
changes
 
much
 
more
 
rapidly
 
and
 
frequently
 
than
 
its
 
vehicle
 
deliveries.
 
As
 
shown
 
in
 
the
 
graphs,
 
the
 
stock
 
price
 
had
 
many
 
noticeable
 
increases
 
and
 
decreases
 
throughout
 
2023-2025
 
while
 
maintaining
 
an
 
upward
 
trend,
 
while
 
deliveries
 
moved
 
less
 
frequently
 
with
 
no
 
clear
 
trend.
 
This
 
answers
 
the
 
research
 
question
 
by
 
suggesting
 
that
 
Tesla’s
 
stock
 
price
 
reacts
 
faster
 
than
 
deliveries
 
growth
 
because
 
investors
 
are
 
always
 
active
 
in
 
the
 
market
 
and
 
can
 
respond
 
immediately
 
to
 
new
 
information,
 
while
 
deliveries
 
take
 
time
 
to
 
change
 
and
 
are
 
reported
 
much
 
less
 
often.
 
With
 
more
 
data,
 
I
 
would
 
investigate
 
whether
 
major
 
changes
 
in
 
Tesla’s
 
stock
 
price
 
consistently
 
happen
 
because
 
of
 
specific
 
events,
 
such
 
as
 
earnings
 
reports
 
or
 
production
 
problems,
 
which
 
cause
 
larger
 
or
 
smaller
 
changes
 
than
 
deliveries
 
growth.
 
An
 
upcoming
 
MAT133
 
topic,
 
such
 
as
 
integration,
 
could
 
help
 
me
 
study
 
accumulated
 
change
 
from
 
rates
 
of
 
change.
 
A
 
real-world
 
event
 
I
 
would
 
investigate
 
is
 
how
 
investor
 
expectations
 
and
 
company
 
news
 
affect
 
stock
 
prices.
 
These
 
would
 
help
 
explain
 
not
 
only
 
how
 
quickly
 
Tesla’s
 
stock
 
and
 
deliveries
 
change,
 
but
 
also
 
why
 
they
 
change.
 
 
 
 
Further
 
Questions
 
and
 
Connections
 
How
 
do
 
major
 
company
 
events
 
affect
 
Tesla’s
 
stock
 
price?
 
 
How
 
would
 
integration
 
help
 
measure
 
Tesla’s
 
total
 
change
 
over
 
time?
 
 
Would
 
using
 
daily
 
stock
 
prices
 
instead
 
of
 
monthly
 
prices
 
change
 
the
 
results?
 
 
Does
 
Tesla’s
 
stock
 
price
 
change
 
before
 
or
 
after
 
quarterly
 
deliveries
 
are
 
reported?
 
 
 
 
References
 
[1]
 
Kolodny,
 
L.
 
(2024,
 
April
 
2).
 
Tesla
 
shares
 
fall
 
after
 
deliveries
 
drop
 
8.5%
 
from
 
a
 
year
 
ago.
 
CNBC.
 
[2]
Yahoo
 
Finance.
 
(n.d.).
 
Tesla,
 
Inc.
 
(TSLA)
 
stock
 
historical
 
prices
 
&
 
data.
 
Yahoo
 
Finance.
 
TSLA
 
Historical
 
Data
 
[3]
Tesla,
 
Inc.
 
(n.d.).
 
Investor
 
relations.
 
Tesla.
 
Tesla
 
Investor
 
Relations