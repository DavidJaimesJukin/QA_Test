# Test Plan: ACME Vacuum Cleaner & Anvil Co. Feedback Form

### Prepared By: David Jaimes
#### Created: 04/24/17
#### Last Updated: 04/24/17
#### Status: Pending Approval

#### Test Revision History:

|   Date  | Version | Revised By   | Changes Made    | Approved By | Approval Date|
|:-------:|---------|--------------|-----------------|-------------|--------------|
| 4/24/17 | 1.0     | David Jaimes | Initial Version | Pending     |  Pending     |

#### Site Revision History:

|   Date  | Version | Revised By   | Changes Made    |
|:-------:|---------|--------------|-----------------|
| 8/12/15 | 1.0     | Max Rasovsky | Initial Version |

#### Approvers List:

|     Name     | Role             | Approver/Reviewer | Approval/Review Date |
|:------------:|------------------|-------------------|----------------------|
| David Jaimes | QA Manual Tester | Max Rasovsky      | Pending              |

#### Reference Documents:

| Version | Date    | Document Name                               |
|:-------:|---------|---------------------------------------------|
| 1.0     | 8/18/15 | Vacuum Cleaner & Anvil Co Feedback Form.pdf |
| 1.0     | 4/24/17 | Manual Test Case               |


### Table of Contents
1. [Introduction](#introduction)
2. [Objective and Tasks](#objectiveAndTasks)
3. [Scope](#scope)
4. [Testing Strategy](#testingStrategy) 
5. [Test Execution](#testExecution)
6. [Test Review & Reporting](#testReview&Reporting)
7. [Tools](#tools)
8. [Approvals](#approvals)

## 1. Introduction <a name='introduction'></a>
#### Purpose: 
This test plan describes the testing approach and overall framework that will drive the testing of the
ACME Vacumm Cleaner & Anvil Co. Feedback Form. The document introduces:

- Test Strategy: rules the test will be based on, including the givens of the project (e.g.: start / end
dates, objectives, assumptions); description of the process to set up a valid test (e.g.: entry / exit
criteria, creation of test cases, specific tasks to perform, scheduling).

- Execution Strategy: describes how the test will be performed and process to identify and report
defects, and to fix and implement fixes.

- Test Management: process to handle the logistics of the test and all the events that come up
during execution (e.g.: communications, escalation procedures, risk and mitigation, team roster)

#### Project Overview: 
The ACME Vacuum Cleaner & Anvil Co. Feedback Form provides the company with insights from it's customers, and along with analytics helps determine customer sentiment.

#### Audience:

- Project team members(David) perform tasks specified in this document, and provide input and
recommendations on this document. 
 
- Project Manager(Max) Plans for the testing activities in the overall project schedule, reviews the
document, tracks the performance of the test according to the task herein specified, approves
the document and is accountable for the results.


## 2. Objectives<a name="objectiveAndTasks"></a>

The objective of the test is to verify that the functionality of The ACME Vacuum Cleaner & Anvil Co. Feedback Form and that it works according to the specifications.

The final product of the test is twofold: 

- A production-ready site
- A set of stable and reusable tests

### Testing Assumptions:

 - Testing would be carried out once the build is ready for testing
 - Performance testing is not considered for this plan
 - All bugs should come with a snapshot image

### Testing Principals:

- Testing will focused on meeting the business objectives, cost efficiency, and quality
- Testing processes will be well defined, yet flexible, with the ability to change as needed 
- Testing activities will build upon previous stages to avoid redundancy or duplication of effort
- Testing will be a repeatable, quantifiable, and measurable activity
- Testing will be divided into distinct phases, each with clearly defined objectives and goals
- Bugs are ranked in this order: cosmetic,low, medium, high, and critical

|   Severity  | Impact                                                                                                           |
|:-----------:|------------------------------------------------------------------------------------------------------------------|
| Critical(1) | -It causes a lack of vital program functionality without a workaround                                            |
| High(2)    | -It causes a lack of vital program functionality with workaround                                                 |
| Medium(3)  | -This bug prevents other areas of the product from being tested.However other areas can be independently tested. |
| Low(4)     | -There is an insufficient or unclear error message, which has minimumimpact on product use                       |
| Cosmetic(5) | -There is an insufficient or unclear error message that has no impact on product use.                            |

## 3. Scope <a name="scope"></a>

The scope of this test plan is focused on the general functionality of the site and that it maintains the style as designated 
in the PRD requirements

## 4. Testing Strategy <a name="testingStrategy"></a>
###Manual Testing 
#### Purpose: 
Manual testing will be performed to check the functions and styling of the application. 

#### Testers: 
David Jaimes

#### Method:
Manual

## 5. Test Execution <a name="testExecution"></a>
### Entry Criteria
- Required tools have been installed
- All required components within the test environment have been initialized
- All required Functional and Style test cases have been documented, reviewed, and validated

## 6. Test Review & Reporting
### Exit Cirteria
- All tests cases have been executed
- All high and critical issues discovered during testing have been fixed and Functional testing has been re-run as a Regression test
- All test results have been reviewed and approved by Max
- All remaining low and medium issues discovered during testing have been logged

## 7. Required Tools <a name="tools"></a>
- The latest versions of Chrome, Safari, and Firefox or an plugin like(Browserstack)
- Developer tools on chosen browser

## 8. Approvals <a name="approvals"></a>

| Role | Name | Signature | Date |
|:-----|------|-----------|------|
|      |      |           |      |