# [JSL02]: Debug the DOM

# Debugging Duplicate Goals

**Debugging Brief:**
In the current code, users can add the same fitness goal multiple times, leading to duplicate entries in the goal list. To enhance the user experience and prevent duplicates, you need to implement a check to ensure that the same goal cannot be added more than once. If a duplicate goal is detected, it should NOT be added to the list.

![alt text](JSL02_Solution.png)

**Issue:** Users can add duplicate fitness goals.
**Debugging Task:** I needed to Prevent users from adding the same goal more than once.

- The goal was to prevent users from adding duplicate fitness goals to the list.
- I need to check if the goal being added already exists in the list before appending it.
- Display an alert to inform the user if they are trying to add a duplicate goal.
- Focus on the code structure within the function and how to handle duplicates.