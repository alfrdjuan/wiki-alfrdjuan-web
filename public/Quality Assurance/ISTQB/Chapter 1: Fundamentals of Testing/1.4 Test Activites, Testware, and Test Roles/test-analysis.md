# 1.4.3 Test Analysis

> #### Definition by syllabus:
> includes analyzing the test basis to identify testable features and to define and prioritize associated test conditions, together with the related risks and risk levels (see section 5.2). The test basis and the test objects are also evaluated to identify defects they may contain and to assess their testability. Test analysis is often supported by the use of test techniques (see chapter 4). Test analysis answers the question “what to test?” in terms of measurable coverage criteria.

**What to test?**
Analyze the Test Basis. Test basis is the base of what we need to test. For example analyzing the requirements, or risk analysis reports.
In this step, we need to define and prioritize test conditions. This is very important because exhaustive test is impossible [^1].

!!! Capturing bi-directional traceability
**need more information.**
when we want to find a scenario, we should be able to trace the test cases that test the scenario and vice versa.
creating a bi-directional traceability between the scenario (features) and the testing (test cases) so when there are changes to the feature/requirements .
we can find what test cases cover that features because we know that test cases will be failed if we run it due to changes to the requirements.
!!!

[^1]: see seven principle