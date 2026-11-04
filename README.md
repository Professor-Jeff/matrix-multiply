# Matrix Multiplication — inside the network

Part 3 of the COMP 138 neural network demos (College of Marin). A single-file page that shows
what the two matrix multiplications in the Pick Activity network actually do, one number at a time:

- one hidden neuron computed by hand (multiply pairs, add, add the bias, ReLU)
- layer 1 and layer 2 laid out portrait-style, with the vector down the left and the matrix beside it; tap a column to see its arithmetic
- the shape rule (inner numbers must match, outer numbers give the answer's shape) as a toy
- a "you try it" exercise with a streak counter
- the whole network as two lines of NumPy

Uses the same names as the previous page (x, W1, b1, h, W2, b2, y) and, when the student has trained a
network on https://professor-jeff.github.io/pick-activity/ in the same browser, the exact weights they trained
(handed over through localStorage). Otherwise it falls back to a saved trained network.

Live: https://professor-jeff.github.io/matrix-multiply/
