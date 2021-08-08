# Test suite
These programs are designed for self test of ForwardCom emulator and softcore.

Link with libc.li for the emulator or with libc-light.li for a softcore without system calls.

##

Files included |  Description
--- | ---
tests_arithmetics.as    |    test all arithmetic instructions on general purpose registers
tests_bool_bit.as    |    test all boolean and bit manipulation instructions on general purpose registers
tests_branch.as    |    test all jump, call, and branch instructions on general purpose registers
test_formats.as    |    test all instruction formats for general purpose registers
