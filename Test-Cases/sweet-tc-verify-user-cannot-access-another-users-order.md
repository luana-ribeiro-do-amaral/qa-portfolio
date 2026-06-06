# Test Case – Verify User Cannot Access Another User's Order

## Test Case ID

TC-001

## Module

Orders

## Priority

High

## Type

Security / Functional

## Preconditions

User is logged in to the Sweet Shop website with a valid account.

## Test Steps

| Step | Action                                            |
| ---- | ------------------------------------------------- |
| 1    | Open the Sweet Shop website                       |
| 2    | Log in with a valid user account                  |
| 3    | Navigate to an order that belongs to another user |
| 4    | Attempt to access the order details page          |
| 5    | Observe the system response                       |

## Expected Result

Access to the order should be denied. The system should display an authorization or permission error message and prevent the user from viewing the order details.

## Execution Result

### Actual Result

The order details page loads successfully and displays another user's order information.

## Status

Failed

## Related Defect

[SB-001 - Unauthorized Access to Another User's Order](../Bug-Reports/sweet-bug-unauthorized-order-access.md)

