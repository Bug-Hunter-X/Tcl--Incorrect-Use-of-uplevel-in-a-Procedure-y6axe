# Tcl Bug: Incorrect Use of uplevel

This repository demonstrates a common error in Tcl involving the misuse of the `uplevel` command within a procedure. The `uplevel` command is used to evaluate commands in a different stack frame, but it must be used carefully to avoid unexpected behavior. The provided example shows an incorrect way to use `uplevel`.  The solution demonstrates how to fix the issue.

## Bug Description
The `badproc` procedure attempts to perform arithmetic within a different stack frame using `uplevel`. This is generally unnecessary and can lead to problems.