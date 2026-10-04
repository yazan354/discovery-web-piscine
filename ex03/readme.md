# Git Version Control & Authentication Guide

## Overview
This project documents core software engineering practices using Git version control and secure SSH key authentication.

## Why Git Makes Development Easier
Version control is a foundational pillar of modern software engineering. Git improves the development workflow in three essential ways:

1. **Safeguarding Code Base**: Git acts as an safety net. By keeping tracked history intact, you can experiment freely on separate branches without risking production code. If a bug or regression is introduced, you can roll back to a known stable state with minimal effort.
2. **Comprehensive History Tracking**: Every commit serves as a snapshot in time with a unique identifier, timestamp, and message. This chronological audit trail allows developers to understand *why* changes were made, track down when bugs were introduced, and review code evolution over time.
3. **Streamlined Team Collaboration**: Multiple developers can work on the same codebase simultaneously without overwriting each other's work. Git enables parallel development via branching and handles merging changes systematically, making asynchronous team workflows possible.

## Project Structure
- `README.md`: Project overview and Git rationale.
- `git_workflow.txt`: Step-by-step terminal record of the edit-add-commit-push cycle.
- `id_ed25519_pub.txt`: Public SSH key generated for secure authentication.
