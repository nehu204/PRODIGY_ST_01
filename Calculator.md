*write test cases for a Simple Calculator Application that performs:

* Addition
* Subtraction
* Multiplication
* Division

It also includes handling:

Valid inputs: positive/negative numbers, decimals, BODMAS
Invalid inputs: non-numeric characters, division by zero, etc.

---

 Test Cases for Calculator App (in Markdown format):

 Test Case 1

Test Case ID: TC\_CALC\_001
Test Description: Verify addition of two positive integers.
Preconditions: Calculator app is open.
Test Steps:

  1. Enter `5`
  2. Press `+`
  3. Enter `3`
  4. Press `=`
Expected Result: Output should be `8`

---

 Test Case 2

Test Case ID: TC\_CALC\_002
Test Description: Verify subtraction of a smaller number from a larger one.
Preconditions: Calculator app is running.
Test Steps:

  1. Enter `10`
  2. Press `-`
  3. Enter `4`
  4. Press `=`
Expected Result**: Output should be `6`

---

 Test Case 3

Test Case ID: TC\_CALC\_003
Test Description: Verify multiplication of two negative numbers.
Preconditions: Calculator is functional.
Test Steps:

  1. Enter `-2`
  2. Press `×`
  3. Enter `-3`
  4. Press `=`
* **Expected Result**: Output should be `6`

---

 Test Case 4

Test Case ID: TC\_CALC\_004
Test Description: Check handling of division by zero.
Preconditions: App is running.
Test Steps:

  1. Enter `5`
  2. Press `÷`
  3. Enter `0`
  4. Press `=`
Expected Result: Display error like “Cannot divide by zero”

---

 Test Case 5

Test Case ID: TC\_CALC\_005
Test Description: Check expression with BODMAS logic 2 + 3 × 4
Preconditions: App supports BODMAS
Test Steps:

  1. Enter `2 + 3 × 4`
  2. Press `=`
Expected Result: Output should be `14` (not `20`)

---

 Test Case 6

Test Case ID: TC\_CALC\_006
Test Description: Input non-numeric characters
Preconditions: App is open
Test Steps:

  1. Enter `abc`
Expected Result: Show error or ignore input

---



