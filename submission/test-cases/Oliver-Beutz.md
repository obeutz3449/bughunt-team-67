# Test Cases: Oliver B

**Team number:** [67]

<!--
HOW TO USE THIS FILE
1. Copy this file. Name the copy with your first name and last initial, like  maria-g.md
2. Leave TEMPLATE.md untouched for your teammates.
3. Write at least ONE failing test case. More is better.
4. Copy the block between the lines for each new test case.
5. Test IDs: use your initials plus a number, like  MG-01, MG-02. This keeps IDs unique across your team.
6. See docs/TESTING_FIELD_GUIDE.md for the sample test case TC-00.
-->

---

**Test ID:** OTC-1
**Written by:** Oliver Beutz
**Title:** You can vote for your own
**Traces to:** REQ-09
**Test type:** Security
**Preconditions:** Logged in as `ghost_gary` (password `boo12345`). On the Vote page.
**Test data:**
Vote for Vampire Accountant

**Steps:**
1. Open the vote page
2. Vote for Vampire accounant

**Expected result:** It does not change
**Actual result:** The votes changes
**Status:** Fail
**Severity:** Major
**V or V:** Verification

---

**Test ID:** OTC-2
**Written by:** Oliver Beutz
**Title:** Voting open before party
**Traces to:** G1
**Test type:** Security
**Preconditions:** Logged in as `ghost_gary` (password `boo12345`). On the Vote page.
**Test data:**
Vote for Vampire Accountant

**Steps:**
1. Open the vote page
2. Vote for Vampire accounant

**Expected result:** Vote page not open yet
**Actual result:** Vote goes through
**Status:** Fail
**Severity:** Major
**V or V:** Verification

---

**Test ID:** OTC-3
**Written by:** Oliver Beutz
**Title:** Passwords can be fewer than 8 characters 
**Traces to:** REQ-01
**Test type:** Security
**Preconditions:** Register account usernmae `e` password `1234` On the Login page
**Test data:**
Allows account `e` to be created

**Steps:**
1. Navigate to Log In/Regsister Page
2. Type username `e` and password `1234`
3. Press create account

**Expected result:** returns `Password is too short.`
**Actual result:** returns `Account created! You can log in now.`
**Status:**
**Severity:**
**V or V:**

---

