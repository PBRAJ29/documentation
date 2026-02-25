# What is a Test Suite?

## Test Implementation



A set of several test cases for a component or system under test, where the post condition of one test case is often used as the precondition for the next one.

## Test Suite

A Test Suite (TU) contains a collection of test cases for testing a functionality attribute. The test cases in a test suite can by executed parallel to each other or sequentially in a given order defining a test sequence. Optional the pre-condition of a test case is prepared by the execution of the previous test case.

## Test Suite Sections

Test Suite contains the overall information like state, originator, owner, priority, and its description

<table><tbody class=""><tr class=""><td><p>Summary</p></td><td><p>Contains specific information of the test suite like:</p><p>catalogue (<u>platform</u> or customer specific), test level, test type, test object, feature, test info, regression test (yes or <u>no</u>), candidate for automation (yes or <u>no</u>), and estimate</p></td></tr><tr class=""><td><p>Pre-Condition</p></td><td><p>Defines the items that must occur before this test suite can be executed</p></td></tr><tr class=""><td><p>Test Suite Design</p></td><td><p>Describes the high level design for the test suite</p></td></tr><tr class=""><td><p>Execution Variables</p></td><td><p>Variables (name and value) defined for the execution of the current test suite</p></td></tr><tr class=""><td colspan="1">Test Cases</td><td colspan="1">Contains the list of the test cases used in this test suite in their defined order</td></tr><tr class=""><td><p>Test Suite Execution Records</p></td><td><p>Contains the list of the test suite's execution records (TSER)</p></td></tr></tbody></table>
