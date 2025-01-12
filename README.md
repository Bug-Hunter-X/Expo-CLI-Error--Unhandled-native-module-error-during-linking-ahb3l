# Expo CLI Error: Unhandled native module error during linking

This repository demonstrates a common error in Expo CLI when attempting to use native modules without proper configuration. The `bug.js` file shows the problematic code, while `bugSolution.js` presents the corrected version.

## Problem

The primary cause is using a native module that requires manual linking within Expo's managed workflow. Expo's managed workflow abstracts away native code to ease development, but certain modules require explicit linking, which can be error-prone if not done correctly.

## Solution

The solution involves carefully verifying module installation, configuration, and potentially leveraging Expo's supported modules or using alternative packages designed for the managed workflow. If manual linking is unavoidable, following Expo's instructions for native module integration is crucial to avoid the "Unhandled native module error" during the linking process.