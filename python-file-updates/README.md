# Algorithm for File Updates in Python

## Overview

This activity focused on using Python to automate the process of updating an IP address allow list. The algorithm identifies IP addresses that should no longer have access and removes them from the `allow_list.txt` file.

## Tasks Completed

- Opened and read the `allow_list.txt` file.
- Converted the file contents from a string into a list of IP addresses.
- Iterated through the remove list using a `for` loop.
- Checked whether each IP address existed in the allow list.
- Removed IP addresses that were no longer authorized.
- Converted the updated list back into a string.
- Updated the `allow_list.txt` file with the revised list.

## Python Concepts Demonstrated

- `open()`
- `with` statements
- `.read()`
- `.split()`
- `for` loops
- Conditional statements
- `.remove()`
- `.join()`
- Writing updated data to a file

## Cybersecurity Skills Demonstrated

- Access control
- IP allow-list management
- Automation
- File handling
- Basic security scripting

## Key Takeaway

This activity strengthened my ability to use Python to automate access-control tasks. I learned how programming can be used to efficiently update security-related data and remove unauthorized IP addresses from an organization's allow list.
