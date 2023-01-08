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
test_muldiv.as    |    test integer multiplication and division instructions
test_pipeline_stalls.as    |    test if pipeline stalls are handled correctly
test_pushpop.as    |    test push and pop instructions
