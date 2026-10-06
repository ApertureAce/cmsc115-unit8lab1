# Lab Reflection: Unit 8 Lab 1 - Git Version Control + Debugging (BuggyProgram)

## Student Name
Hayden Bourgeois

## GitHub Repository URL
https://github.com/ApertureAce/cmsc115-unit8lab1

---

# Commit 1: Initial Commit

## What did you include in this commit?
- Starter project files for Unit 8 Lab 1 before changes.


## What was the purpose of this commit?
- To create a baseline and record of the first version of this project.

---

# Commit 2: Task 1 (getGrade)

## Which tests in Task1Test were failing before your fix?
- testEdges()
- testGrades()

## What was the issue in the code?
- The print appropriate print statements for score > 90 and score > 80 were swapped.
- Edge case issues associated with '>' operator.

## What change did you make to fix it?
- Swapped print statements for 90 and 80 edge cases.
- Changed '>' operator to '>=' for scores, '80' and '90'.

## How did the tests help guide your fix?
- By examining the test cases used in the test code, I made the connection that the program expected >= 90 to return "Exceed" and >= 80 to return "Meets".

---

# Commit 3: Task 2 (sumEvenNumbers)

## Which tests in Task2Test were failing before your fix?
- testEmpty()
- testOddNumber()
- testSumEvenNumbers()

## What was the issue in the code?
- sum variable was initialized to '1' instead of 0.
- Program did not check for null array.
- for loop comparison had bounds issue related to <= operator.

## What change did you make to fix it?
- Initialized 'sum' to 0.
- Added section to return false if array length is 0.
- Changed for loop comparison operator from '<=' to '<'.

## How did the tests help guide your fix?
- The test program showed me which conditions failed so I could consult examine the code that tested those conditions.

---

# Commit 4: Task 3 (sumRange)

## Which tests in Task3Test were failing before your fix?
- testSumRangeReverseOrder()


## What was the issue in the code?
- The code didn't check to see if if 'start' was greater than 'end' so the program loop incremented i instead of decrementing

## What change did you make to fix it?
- Created an if-else statement that changes for loop inc/dec for i variable.

## How did the tests help guide your fix?
- By observing that only testSumRangeReverseOrder() failed, I could narrow the down the precise issue.

---

# Overall Reflection

## Which task was the easiest to fix? Why?
-

## Which task was the most difficult? Why?
-

## How did Git help you track your progress through the debugging process?
-

## Why is it important to make small, frequent commits when debugging code?
-

## What did you learn about using JUnit tests to guide debugging?
-

---

# Commit 5: Final Reflection

## What did you complete or update before making this final commit?
-

## Why is it useful to document your work after completing a programming task?
-