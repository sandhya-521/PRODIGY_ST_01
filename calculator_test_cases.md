# Test Cases for Simple Calculator Application

---

## TC-001: Addition of Two Positive Numbers
- **Description:** Verify that the calculator correctly adds two positive numbers.
- **Preconditions:** Calculator app is open and ready.
- **Test Steps:**
  1. Enter `5`
  2. Click `+`
  3. Enter `3`
  4. Click `=`
- **Expected Result:** Output displays `8`

---

## TC-002: Subtraction of Two Numbers
- **Description:** Verify subtraction of a smaller number from a larger number.
- **Preconditions:** Calculator app is open.
- **Test Steps:**
  1. Enter `10`
  2. Click `-`
  3. Enter `4`
  4. Click `=`
- **Expected Result:** Output displays `6`

---

## TC-003: Multiplication of Two Numbers
- **Description:** Verify that multiplication works correctly.
- **Preconditions:** Calculator app is open.
- **Test Steps:**
  1. Enter `6`
  2. Click `×`
  3. Enter `7`
  4. Click `=`
- **Expected Result:** Output displays `42`

---

## TC-004: Division of Two Numbers
- **Description:** Verify division of a number by a non-zero number.
- **Preconditions:** Calculator app is open.
- **Test Steps:**
  1. Enter `20`
  2. Click `÷`
  3. Enter `4`
  4. Click `=`
- **Expected Result:** Output displays `5`

---

## TC-005: Division by Zero
- **Description:** Verify that dividing by zero shows an error.
- **Preconditions:** Calculator app is open.
- **Test Steps:**
  1. Enter `10`
  2. Click `÷`
  3. Enter `0`
  4. Click `=`
- **Expected Result:** Error message displayed (e.g., "Cannot divide by zero")

---

## TC-006: Addition with Negative Numbers
- **Description:** Verify addition when one input is negative.
- **Preconditions:** Calculator app is open.
- **Test Steps:**
  1. Enter `-5`
  2. Click `+`
  3. Enter `3`
  4. Click `=`
- **Expected Result:** Output displays `-2`

---

## TC-007: Decimal Number Addition
- **Description:** Verify that the calculator handles decimal inputs.
- **Preconditions:** Calculator app is open.
- **Test Steps:**
  1. Enter `1.5`
  2. Click `+`
  3. Enter `2.5`
  4. Click `=`
- **Expected Result:** Output displays `4`

---

## TC-008: BODMAS / Order of Operations
- **Description:** Verify calculator follows BODMAS rule.
- **Preconditions:** Calculator app supports expression input.
- **Test Steps:**
  1. Enter `2 + 3 × 4`
  2. Click `=`
- **Expected Result:** Output displays `14` (not `20`)

---

## TC-009: Non-Numeric Input
- **Description:** Verify that the calculator rejects non-numeric characters.
- **Preconditions:** Calculator app is open.
- **Test Steps:**
  1. Try typing `abc` into the input field
  2. Click `=`
- **Expected Result:** Input is rejected or an error message is shown

---

## TC-010: Large Number Calculation
- **Description:** Verify that the calculator handles large numbers.
- **Preconditions:** Calculator app is open.
- **Test Steps:**
  1. Enter `999999`
  2. Click `×`
  3. Enter `999999`
  4. Click `=`
- **Expected Result:** Output displays `999998000001`