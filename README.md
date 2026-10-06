# SimpleSchedule

Based on the open-source project name-dinosaur/SimpleSchedule.

## My changes
- Added a Leave column so employees on leave are not assigned shifts
- Extended scheduling.py with a few lines of code to read the Leave column
- Checked the result: Employee 1 and Employee 9 lost their shifts on their leave days

## How the schedule works
- One shift per person per day
- No morning shift after a night shift
- People with the fewest hours are assigned first
