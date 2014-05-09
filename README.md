InvalidCastException when compiled with the Roslyn End User Preview.
==========================

The project APP1 in this repository crashes with an InvalidCastException when compiled with Roslyn in Vs2013. When compiled with the csc no exception occurs.

## What have I figured out so far?

* The output of the MyButton class differs between the csc and Roslyn. The csc makes the interface implementation explicit.
