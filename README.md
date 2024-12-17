# Expo CLI Android Build Failure: AGP Version Mismatch

This repository demonstrates a common issue encountered when building Android apps with the Expo CLI: a mismatch in Android Gradle Plugin (AGP) versions.  This incompatibility leads to build failures, often presenting cryptic error messages.

## Problem
The core problem is a conflict between the AGP version used by your Expo project and the version expected or supported by other parts of the Android build system.  This can manifest in many different error messages.

## Solution
The solution involves ensuring all AGP versions are consistent and up-to-date.  This often requires updating the `android/build.gradle` files and possibly the Android build tools.  Specific steps are detailed in the provided `bugSolution.js` file.  Note that cleaning and rebuilding the project can also be beneficial.

## Reproducing the Bug
1. Clone this repository.
2. Follow the instructions in `bug.js` to setup and run the problematic build command.
3. Observe the build failure and resulting error messages.