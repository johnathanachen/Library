# One-vs-rest vs. multinomial/softmax

## One-vs-rest
- fit a binary classifier for each
class
- predict with all, take largest
output
- pro: simple, modular
- con: not directly optimizing
accuracy
- common for SVMs as well
- can produce probabilities

## "Multinomial" or "softmax"
- fit a single classifier for all
classes
- prediction directly outputs best
class
- pro: tackle the problem directly
- con: more complicated, new
code
- possible for SVMs, but less
common