FOC BLDCdriver running off micropython
AS5600 encoder and configure other in the code

https://github.com/candyriver/MicroPython-FOC
I was looking for micropython driver for BLDC motors FOC library but this is the only one and its not even started. 
Thus i started from Simple foc algorism to make a library that actually works, and it does

The AS5600 library comes from that.

The gif shows it driving a generator backwards to make it spin. 

![demo](https://github.com/I-am-the-senate/FOCmicropython/blob/main/demo%20(1).gif)

For regular FOC, the functions should be fairly self explainatory, just change your pins and it should just work.
