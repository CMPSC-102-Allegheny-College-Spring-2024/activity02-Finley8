# Data Types

Please remove the markers and notes from this file
so that the final document is written in a professional fashion
suitable for publication. If you have questions about how to
structure, format, and write this document, please ask for a
preliminary assessment of your work in advance of the deadline.

## Finley Banas

## Program Output

### What is the output from running the following commands?

Use a fenced code block to provide the output for this command.

- `python demonstrate-variable-limitations.py`

```python
The value of a feasible number is 115792089237316195423570985008687907853269984665640564039457584007913129639936

The value of another feasible number is 179769313486231590772930519078902473361797697894230657273430081157732675805500963132708477322407536021120113879871393357658789768814416622492847430639474124377767893424865485276302219601246094119453082952085005768838150682342462881473913110540827237163350510684586298239947245938479716304835356329624224137216
```

Use a fenced code block to provide the output for this command.

- `python compare-variables.py`

```python
1.0 is not the same as 1.1
1.0 is the same as 1.0
.33333 + .33333 + .33333 is not equal to 1
.33333333333 + .33333333333 + .3333333333 is not equal to 1
The value of 1/3 is 0.3333333333333333
0.3333333333333333 + 0.3333333333333333 + 0.3333333333333333 is equal to 1
1/3 + 1/3 + 1/3 is equal 1
```

## Program Questions

### Why is it not feasible to perform the computation `2**2**100`?

In this example for "2" to be put to the power of "2" which is put to the power of "100" the output is around 50 digits. This does not make mathmatical sense and if it were to work would produce a very long number which is very hard to read. It may be benefitial to use E notation for the response if possible.  

### What is the value of `1/3` according to the Python language? Why?

The value of 1/3 according to Python is 0.3333333333333333. This is what you get when you ask python to give you the value of 1/3. Within the code this value is set to be equal to 1 if added together by two of the same value. 

### Why is the value of `.33333 + .33333 + .33333 == 1` equal to `False`?

This may be because the number is not long enough. Within the code there is an if statement for this equation and Python has decided that it is false. It is difficult to understand because most of these values seem to be the same yet only some of them will pass.
