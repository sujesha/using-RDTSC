#  How-to measure CPU cycles using the time stamp counter (TSC) register

In this document, we present collated information regarding how-to use the
model-specific TSC register to count the number
of ticks or CPU cycles spent for any target set of instructions. For ease of
use, we make available snippets of code that can be pasted into existing
code to quickly perform measurement. We also present a
sample use-case at the end, of measuring CPU cycles incurred for MD5 hashing
and outline our learnings.
