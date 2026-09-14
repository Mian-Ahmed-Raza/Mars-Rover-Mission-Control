# CR-03 — Security Upgrade

## Change Request

### Original Requirement

**NFR-02:**

> Only authenticated Mission Control operators shall be permitted to issue rover commands.

### New Requirement

**NFR-02:**

> The system shall require authenticated and role-authorized operators before accepting rover commands.

## Change Analysis

The original requirement only requires the operator to be authenticated.

Authentication verifies the identity of the user.

The new requirement adds role-based authorization. This means that even if a user is authenticated, the system must also check whether that user's role has permission to issue rover commands.

### Authentication vs Authorization

**Authentication:**
Determines who the user is.

**Authorization:**
Determines what the authenticated user is allowed to do.

### Example

| User         | Authenticated | Authorized | Command Accepted |
| ------------ | ------------- | ---------- | ---------------- |
| Operator A   | Yes           | Yes        | Yes              |
| Operator B   | Yes           | No         | No               |
| Unknown User | No            | No         | No               |

## SVV Impact

The new requirement provides stronger security and makes the access-control behavior easier to verify.

### Example Verification

Test the system with:

1. An authenticated and authorized operator.
2. An authenticated but unauthorized operator.
3. An unauthenticated user.

**Expected Results:**

* Authorized operator → command accepted.
* Authenticated but unauthorized operator → command rejected.
* Unauthenticated user → command rejected.

## Conclusion

CR-03 strengthens the security requirement by requiring both authentication and role-based authorization before rover commands are accepted.
