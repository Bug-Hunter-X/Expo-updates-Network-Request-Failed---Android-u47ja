# Expo-updates Network Request Failed - Android

This repository demonstrates a bug encountered when using the expo-updates package within an Expo managed workflow.  The error, "Network request failed", appeared only on Android devices and was unhelpful in pinpointing the root cause. Standard troubleshooting such as network checks and cache clearing did not resolve the problem.

The `bug.js` file shows the relevant code snippet where the error occurred.  `bugSolution.js` presents a potential fix that addressed the issue in my project. The solution involved carefully examining the update URL and ensuring it was accessible and correctly configured for the target Android environment.

This bug report provides detailed steps to reproduce the problem and a potential solution to help others avoid similar issues.