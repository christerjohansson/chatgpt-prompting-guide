---
layout: default
title: Writing PseudoCode for AI
parent: N/A
author: Christer Johansson
---

## Login form

This is pseudocode describing a login sequence in a programming language of choice. Just tell the AI service what language you want it in.

Example:
"Write this in React as a server component"
```
IF userlogin = true
    API call to get user data
    Assign data to variables
    Re-route user to dashboard
ELSEIF userlogin failed more than 3 times
    Don't allow more attempts
    Send user notification email
    Re-route user to home page
ELSE
    Log bad login attempt
    Show error message
    Clear login form
```
