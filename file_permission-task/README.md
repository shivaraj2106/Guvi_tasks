


# File Permission Task

## Overview
This project demonstrates file permission management in a Linux environment using shell commands. The task involved creating a text file and configuring specific access permissions for different user categories.

## Task Requirements
- Create a file named demo.txt
- Set permissions so that:
  - Owner can read, write, and execute
  - Group members can read and write
  - All other users can only read

## Implementation
The file was created in a WSL (Windows Subsystem for Linux) environment. Permissions were set using the chmod command with octal notation 764, which translates to:
- Owner: full access (rwx)
- Group: read and write access (rw-)
- Others: read-only access (r--)

## Final Result
Successfully created demo.txt with the required permission structure (-rwxrw-r--), meeting all specified access control requirements.

## Environment
- Platform: Windows Subsystem for Linux
- Shell: Bash
- File location: Working directory due to system path restrictions

## Repository
GitHub: https://github.com/shivaraj2106/task_2.git

Contains the demo file, screenshots documenting the process, and this README.

