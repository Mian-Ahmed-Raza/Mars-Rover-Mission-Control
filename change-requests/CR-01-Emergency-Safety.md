# CR-01 — Emergency Safety

## Change Request

### Original Requirement

**FR-04:**

> The rover shall enter Safe Mode when a critical battery or thermal condition is detected.

### New Requirement

**FR-04:**

> The rover shall enter Safe Mode within 3 seconds when battery temperature exceeds the critical threshold or battery capacity falls below the defined emergency level.

## Change Analysis

The original requirement states that the rover must enter Safe Mode when a critical battery or thermal condition occurs.

However, it does not specify how quickly the rover must enter Safe Mode.

The new requirement introduces a **3-second time limit** and clearly defines the conditions that trigger Safe Mode.

### Main Changes

1. A maximum response time of **3 seconds** has been added.
2. The thermal condition is defined as the battery temperature exceeding the critical threshold.
3. The battery condition is defined as the battery capacity falling below the emergency level.

## SVV Impact

The new requirement is more specific, measurable, and testable.

### Example Verification

A test can introduce a critical battery or thermal condition and measure the time taken for the rover to enter Safe Mode.

**Expected Result:**

The rover enters Safe Mode within **3 seconds**.

## Conclusion

CR-01 improves the safety requirement by adding a measurable response time and clearer triggering conditions.
