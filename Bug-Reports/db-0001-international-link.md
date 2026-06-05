# Bug Report – International Link Does Not Redirect to the International Page

## Bug ID

DB-0001

## Summary

The "Internacional" link located in the footer redirects users to a blank page instead of the Domino's international website.

## Severity

Major

## Priority

Medium

## Environment

* OS: Windows 11
* Browser: Google Chrome (latest)

## Preconditions

User is on the Brazilian Domino's Pizza homepage (dominos.com.br).

## Steps to Reproduce

1. Open a browser and navigate to dominos.com.br
2. Scroll to the footer
3. Click the "Internacional" link

## Expected Result

The user should be redirected to the Domino's international page listing global markets and regions.

## Actual Result

The user is redirected to a blank page. No content, navigation, or error message is displayed.

## Evidence

![International Link Bug](internacional-bug.mp4)

## Related Test Case

[TC-FOOTER-001](../Test-Cases/tc-footer-international-link.md)

## Notes

Issue reproduced consistently in Google Chrome on Windows 11.
