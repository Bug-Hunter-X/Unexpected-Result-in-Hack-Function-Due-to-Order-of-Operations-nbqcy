# Unexpected Result in Hack Function Due to Order of Operations

This repository demonstrates a subtle bug in a Hack program that leads to an unexpected result.  The bug is related to the order of operations and implicit type conversions within the program.

The `baz` function incorrectly calculates the final result due to how it combines the results of the other functions. This leads to a one-unit difference in the final output.

The solution illustrates how to correct the calculation to produce the expected result.  The core issue involves ensuring correct arithmetic order and potentially adding explicit type handling where needed.  The solution highlights a common pitfall when dealing with function composition and numerical operations in Hack.
