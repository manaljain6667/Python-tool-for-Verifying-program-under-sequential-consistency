# Python-tool-for-Verifying-program-under-sequential-consistency
This is a tiny software tool that takes program
as input and outputs all valid traces.
Input program can have assert statement in it. If there exists a
sequential execution(valid trace) that violates the assert statement,
then your tool should stop exploring traces and output the result as
“Assertion violation” and display this trace.
