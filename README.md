# Boolean Algebra Activity

## 1. Simplify the Boolean Expression

Given:

F = A'B'C' + A'B'C + A'BC + AB'C + ABC'

Group the first two terms:

F = A'B'(C' + C) + A'BC + AB'C + ABC'

Since C' + C = 1:

F = A'B' + A'BC + AB'C + ABC'

Group terms with C:

A'BC + AB'C = C(A'B + AB')

So:

F = A'B' + C(A'B + AB') + ABC'

The simplified expression is:

**F = A'B' + A'BC + AB'C + ABC'**

This expression cannot be reduced much further without changing the logic.

## 2. Motion-Sensing Light System

Inputs:

m = motion sensed
t = test mode
i = illuminate lamp

The lamp turns on if:

1. Motion is sensed and test mode is off: mt'
2. Test mode is on and no motion is sensed: tm'
3. Test mode is on and motion is sensed: tm

Original expression:

i = mt' + tm' + tm

Simplify:

i = mt' + t(m' + m)

Since m' + m = 1:

i = mt' + t

Using Boolean identity t + mt' = t + m:

i = t + m

Final simplified expression:

**i = m + t**

This means the lamp turns on if motion is sensed OR test mode is on.

## 3. Flowchart Description

Start
↓
Identify the Boolean expression
↓
Group similar terms
↓
Apply Boolean algebra rules
↓
Simplify the expression
↓
Check if the simplified expression matches the original conditions
↓
Write the final answer
↓
End

## 4. Challenges

One challenge I had was deciding which terms could be grouped together. Some expressions looked different at first, but after applying Boolean rules like C + C' = 1, they became easier to simplify. Another challenge was making sure the simplified answer still matched the original conditions.
