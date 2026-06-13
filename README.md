# NUC-TV Automation Overview

This project describes the intended behavior of a future automation script that runs on an Intel NUC controlling three TVs. The goal is to automatically open and manage browser tabs on boot while recovering from human interaction if it occurs.

## Boot and Startup
- On NUC startup, the automation should automatically begin.
- The script should power on all three TVs.

## Browser Session Management
- Once the NUC and TVs are running, new browser tabs should open and log into the desired websites.
- Each tab should be placed in full-screen mode and assigned to the correct TV display.
- Every 30 seconds, the script should reload the tab and ensure that the reloaded tab is brought to the front.

## Recovery After Human Interaction
- If a keyboard or mouse event is detected, the script should start a five-minute timer.
- After five minutes of inactivity, the script should check all open tabs and windows, restoring the original state if anything has been changed.
- Once restored, it should resume the automated sequence.

This README only documents the desired functionality. Further development is required to implement the automation on the NUC.


This APP is AI built. I did not do anything...
