# Bug Report – Unauthorized Access to Another User's Order

## Bug ID

SB-001

## Summary

A user can access and view an order that was not placed by their account by navigating directly to another user's order page.

## Severity

Critical

## Priority

High

## Environment

OS: Windows 11
Browser: Google Chrome (Latest Version)
Website: Sweet Shop (https://sweetshop.netlify.app/)

## Preconditions

* User is logged in with a valid account.
* At least one order exists in the system belonging to a different user.
* The user has access to the order history or order details functionality.

## Steps to Reproduce

1. Open the Sweet Shop website.
2. Log in using a valid user account.
3. Obtain or modify the URL to reference an order belonging to another user.
4. Navigate to the order details page.
5. Observe the system behavior.

## Expected Result

The system should validate ownership of the order and deny access if the order does not belong to the logged-in user. An authorization or permission error message should be displayed.

## Actual Result

The order details page loads successfully and displays another user's order information without authorization.

## Frequency

5/5 times (100%)

## Evidence

### Screenshot showing unauthorized access to another user's order

![Unauthorized Access to Another User's Order](../Evidence/sweet-evidence-bug.png)

## Impact

Unauthorized users can access sensitive customer information, resulting in a serious security and privacy vulnerability.

## Related Test Case

[TC SWEET-001 - Verify User Cannot Access Another User's Order](../Test-Cases/sweet-tc-verify-user-cannot-access-another-users-order.md)
