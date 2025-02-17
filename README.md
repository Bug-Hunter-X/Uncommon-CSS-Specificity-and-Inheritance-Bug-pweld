# Uncommon CSS Specificity and Inheritance Bug

This repository demonstrates a subtle bug related to CSS specificity and the `inherit` keyword. The issue arises when dealing with multiple inherited styles and how `inherit` interacts with specificity.

## Description

The bug showcases an unexpected behavior of the `inherit` keyword in CSS when it comes to resolving specificity conflicts with multiple inherited styles. In certain cases, `inherit` might not produce the expected outcome, only inheriting from the immediate parent and ignoring others.