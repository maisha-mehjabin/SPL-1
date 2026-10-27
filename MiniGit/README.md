# MiniGit — A Simplified Version Control System

**Software Project Lab 1 (SPL-1)**  
**Institute of Information Technology, University of Dhaka**

MiniGit is an offline, command-line based Version Control System inspired by Git. It aims to provide a simplified understanding of how version control works by implementing core operations for tracking file changes, saving project versions, comparing revisions, and managing branches.

## Project Overview

Version control systems help developers track changes to files, preserve previous versions, and manage parallel development. MiniGit aims to implement these essential concepts in a simplified system that operates locally without requiring a remote server.

## Planned Features

- **Repository Initialization (`init`):** Create a local repository and initialize the internal data structures required for version control.
- **File Tracking and Staging (`add`):** Select new or modified files and prepare their changes for the next commit.
- **Commit (`commit`):** Save a version of the project along with a commit message and relevant history information.
- **Status (`status`):** Display untracked, modified, and staged files.
- **Commit History (`log`):** View previous commits and their associated information.
- **Version Comparison (`diff`):** Compare file contents between versions and identify added, removed, or modified lines.
- **Content Hashing:** Identify stored file contents and detect changes using hashing.
- **Branch Management (`branch`):** Create and manage independent lines of development.
- **Branch Switching (`checkout`):** Switch between branches and update working files to match the selected version.
- **Merging (`merge`):** Combine changes from different branches and detect conflicting modifications.
- **Error Handling:** Handle invalid commands, missing files, invalid references, and other common operational errors.

## Technology Stack

- **Programming Language:** C++
- **Version Control and Hosting:** Git and GitHub
- **Development Environment:** Linux / Windows Subsystem for Linux (WSL)
- **Hashing:** Hashing library or custom implementation

## Project Status

**Planning phase — implementation has not started yet.**

The project scope and planned features are based on the SPL-1 project proposal. Implementation details and the internal architecture will be documented as development progresses.

## Author

**Maisha Mehjabin**  
BSSE 1737  
Institute of Information Technology, University of Dhaka