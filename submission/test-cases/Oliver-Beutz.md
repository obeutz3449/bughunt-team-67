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