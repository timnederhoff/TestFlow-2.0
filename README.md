# The New Test Flow explained

## `<goal>test</goal>`
The goal of the new test flow is to save time. Also being more efficient in test steps. Also to have a better and more representative report.

## `test.how();`
By following certain principles:
1. verifications (assert/expect) are executed in parallel
1. a test has 3 possible outcomes: Passed, Failed and Untested
   * Passed: when a verification action passed
   * Failed: when a verification action failed
   * Untested: one of steps before verification actions fails
1. a scenario is a set of tests that result from one test flow
1. every verification in a flow defines 1 test
1. testing "through": after the verification actions, the flow continues with other steps and verifications
1. the report contains the following matrices for each scenario: executed/aborted tests ratio, passed/executed ratio.

![Flow overview](/images/testflow_2.svg)
