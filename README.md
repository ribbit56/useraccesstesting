# User Access Testing Script

This is a simple script to help perform user access testing for auditors and system administrators alike. While many systems come with baked-in user access review functionality, many others do not. This script is designed to take a simple user list and join it to a secondary HR report or other employee/user information report via a shared employee ID. After running the script, an excel file with three tabs is created. Please read below for a summary of the tabs:

**User Access Testing:** Contains the full results of the join, i.e. this is the user list + HR file/other report joined together. The result is the original user list with additional employee information such as role, department, manager, hire date, and termination date.

**New Hires:** Contains all users who were hired on or after a specified date which can be set in the script.

**Terminated Users:** Contains all users with an employment status of terminated or similar value which can be set in the script.
