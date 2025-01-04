# Tailwind CSS @apply Directive Error: Class Not Found

This repository demonstrates a common error encountered when using Tailwind CSS's `@apply` directive.  The error occurs when the `@apply` directive attempts to use a class that is either misspelled or hasn't been defined in your Tailwind CSS configuration file.

## Bug Description

The `@apply` directive in Tailwind CSS is designed to apply pre-defined styles to an element by referencing the class name.  However, if the class name referenced in the `@apply` directive does not exist, the compilation will either fail or it will simply ignore the `@apply` directive resulting in unexpected behavior.

## Solution

The solution to this problem lies in double-checking the spelling of the class name and ensuring that the class is correctly defined in your Tailwind CSS configuration.

## How to reproduce the bug

1. Clone this repository.
2. Open `bug.html` in your browser.
3. You will see that the styling applied is not correct, because the `@apply` directive refers to a non-existent class.