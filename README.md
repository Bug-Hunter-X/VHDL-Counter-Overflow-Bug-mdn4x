# VHDL Counter Overflow Bug
This repository demonstrates a common bug in VHDL code: an integer overflow in a counter.  The original `bug.vhdl` code implements a simple counter that is prone to unexpected behavior when reaching its maximum value. The solution (`bugSolution.vhdl`) demonstrates a corrected implementation.

## Bug Description
The `bug.vhdl` code contains a potential overflow issue.  When the counter reaches its maximum value (15), it incorrectly resets to 0. This issue can lead to unexpected behavior in the overall system, especially in timing-critical applications. The bug is subtle and might not be immediately apparent.

## Solution
The `bugSolution.vhdl` file provides a corrected version that avoids the overflow.  This is accomplished through careful handling of the counter's maximum value and using appropriate range checks. The solution provides robust and predictable behavior for the counter.