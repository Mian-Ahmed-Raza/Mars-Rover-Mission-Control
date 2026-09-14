# CR-02 — Mission Expansion

## Change Request

### Original Requirement

**NFR-04:**

> The system should support communication with multiple rovers simultaneously.

### New Requirement

**NFR-04:**

> The system shall support at least 20 simultaneously connected rovers.

## Change Analysis

The original requirement states that the system should support multiple rovers, but the term "multiple" is not specific.

For example, it is unclear whether multiple means 2, 5, 10, or 20 rovers.

The new requirement specifies a minimum of **20 simultaneously connected rovers**.

### Main Change

The vague term **"multiple"** has been replaced with a measurable value:

**At least 20 rovers**

## SVV Impact

The new requirement is more precise, measurable, and testable.

### Example Verification

A test can connect 20 rovers to Mission Control simultaneously and verify that the system can communicate with all of them.

**Expected Result:**

All 20 rovers remain connected and can communicate successfully with Mission Control.

## Conclusion

CR-02 removes ambiguity and provides a measurable scalability requirement for the system.
