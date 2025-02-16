# Unexpected Empty String Return in Swift Function

This repository demonstrates a subtle bug in a Swift function that unexpectedly returns an empty string instead of the expected uppercase version when provided with an empty string.  The solution provides a corrected version that correctly handles empty strings.

## Bug Report

The function `myFunc` is intended to return the uppercase version of the input string. However, when an empty string is passed, it incorrectly returns an empty string instead of continuing to the return statement which returns the uppercased string. This issue stems from the conditional statement's early return.