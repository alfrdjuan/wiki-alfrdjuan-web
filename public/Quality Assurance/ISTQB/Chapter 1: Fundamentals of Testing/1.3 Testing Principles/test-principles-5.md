# #5 Test wear out

> #### Definition by syllabus:
> **If the same tests are repeated many times, they become increasingly ineffective in detecting new defects.**
> To overcome this effect, existing tests and test data may need to be modified, and new tests may need to be written. 
> However, in some cases, repeating the same tests can have a beneficial outcome, e.g., in automated regression testing.

**Beware of pesticide paradox.**
If test repeated over and over again, these tests will no longer find defects. Solution: create new test cases or do another testing types (eg. load test). But this can be useful for example regression testing. Running test cases over and over again make sure one module not affected by recent changes is one of the pesticide paradox example.